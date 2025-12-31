
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالتي إلى شمام 💜</title>
    <style>
        body {
            background: 
                /* خلفية ورود */
                url('https://i.imgur.com/6VnLQ7P.png') center/cover no-repeat,
                /* تدرج بنفسجي */
                linear-gradient(135deg, #7B1FA2, #E1BEE7);
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }
        
        /* تأثير شفافية على الخلفية */
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.2);
            z-index: -1;
        }
        
        .letter {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(15px);
            border-radius: 25px;
            padding: 50px;
            max-width: 700px;
            box-shadow: 
                0 15px 35px rgba(0, 0, 0, 0.3),
                inset 0 1px 0 rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            position: relative;
            overflow: hidden;
        }
        
        /* زخارف جانبية */
        .letter::before {
            content: '💜';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 40px;
            opacity: 0.3;
        }
        
        .letter::after {
            content: '🌸';
            position: absolute;
            bottom: 20px;
            right: 20px;
            font-size: 40px;
            opacity: 0.3;
        }
        
        h1 {
            color: #FFD700;
            font-size: 2.8em;
            margin-bottom: 40px;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.4);
            background: linear-gradient(45deg, #FFD700, #FFECB3);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            padding-bottom: 15px;
            border-bottom: 2px solid rgba(255, 255, 255, 0.2);
        }
        
        .message {
            font-size: 1.3em;
            line-height: 1.9;
            text-align: right;
            direction: rtl;
            position: relative;
            z-index: 1;
        }
        
        .message p {
            margin-bottom: 25px;
            padding-right: 20px;
            border-right: 3px solid rgba(255, 105, 180, 0.5);
            transition: all 0.3s ease;
        }
        
        .message p:hover {
            border-right-color: #FF69B4;
            transform: translateX(-5px);
        }
        
        .heart {
            color: #FF69B4;
            font-size: 1.8em;
            margin: 0 8px;
            animation: heartbeat 1.5s infinite;
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
        
        .emoji {
            font-size: 1.6em;
            margin: 0 5px;
        }
        
        .signature {
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.3);
            font-style: italic;
            font-size: 1.4em;
            color: #FFD700;
            text-align: center;
        }
        
        .rose {
            position: absolute;
            font-size: 60px;
            opacity: 0.1;
            z-index: 0;
        }
        
        .rose1 { top: 10%; left: 5%; }
        .rose2 { bottom: 10%; right: 5%; }
        
        /* تأثيرات للجوال */
        @media (max-width: 768px) {
            .letter {
                padding: 30px;
                margin: 15px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .message {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <div class="rose rose1">🌹</div>
    <div class="rose rose2">🌹</div>
    
    <div class="letter">
        <h1>💌 رسالة رأس السنة إلى حبيبي شمام 💜</h1>
        
        <div class="message">
            <p>مع بداية السنة الجديدة، أجد قلبي يعود إليك. <span class="heart">💜</span></p>
            <p>في كل لحظة هادئة، حضورك يشبه الوطن. <span class="heart">💜</span></p>
            <p>أنت الدفء الذي تبحث عنه روحي في كل فصل. <span class="heart">💜</span></p>
            <p>معك، حتى الوقت يبدو ألطف وأكثر رقة. <span class="heart">💜</span></p>
            <p>أحمل حبك كأعظم يقين في حياتي.</p>
            <p>لتحتضن هذه السنة أيدينا أقرب من قبل. <span class="heart">💜</span></p>
            <p>لتصير أيامنا أكثر لطفاً وليالينا أكثر أملاً. <span class="heart">💜</span></p>
            <p>وليتعمق حبي لك مع كل صفحة تقلب. <span class="heart">💜</span></p>
            
            <p>لتظل هذه السنة تحضنك بالحب والنور، يا شمامي. <span class="emoji">🥰</span></p>
            <p>لك إلى الأبد، بقلب يختارك كل يوم. <span class="emoji">🥺</span></p>
            
            <div class="signature">
                سنة جديدة سعيدة يا شوشتي <span class="emoji">💜💋</span><br>
                <small style="opacity:0.8;">مع كل حبي وتقديري</small>
            </div>
        </div>
    </div>
    
    <script>
        // تأثير بسيط عند التمرير
        document.addEventListener('DOMContentLoaded', function() {
            const hearts = document.querySelectorAll('.heart');
            hearts.forEach(heart => {
                heart.addEventListener('click', function() {
                    this.style.color = '#FF1493';
                    setTimeout(() => {
                        this.style.color = '#FF69B4';
                    }, 300);
                });
            });
        });
    </script>
</body>
</html>
