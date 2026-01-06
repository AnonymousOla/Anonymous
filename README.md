<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To My Love 💕</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            overflow-x: hidden;
        }

        .hearts {
            position: fixed;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .heart {
            position: absolute;
            color: rgba(255, 255, 255, 0.3);
            font-size: 20px;
            animation: float 15s infinite;
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
                opacity: 0;
            }
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }

        .header {
            text-align: center;
            color: white;
            margin-bottom: 40px;
            animation: fadeInDown 1s ease;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header p {
            font-size: 1.3em;
            font-style: italic;
        }

        .card {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.3);
            animation: fadeInUp 1s ease;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .card h2 {
            color: #764ba2;
            margin-bottom: 20px;
            font-size: 2em;
            text-align: center;
        }

        .card p {
            color: #333;
            line-height: 1.8;
            font-size: 1.1em;
            margin-bottom: 15px;
        }

        .love-list {
            list-style: none;
            padding: 0;
        }

        .love-list li {
            padding: 15px;
            margin: 10px 0;
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
            border-radius: 10px;
            color: #333;
            font-size: 1.1em;
            animation: slideIn 0.5s ease;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-30px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .love-list li:before {
            content: "💕 ";
            margin-right: 10px;
        }

        .wishes-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .wish-card {
            background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .wish-card:hover {
            transform: scale(1.05);
        }

        .wish-card .emoji {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .wish-card h3 {
            color: #764ba2;
            margin-bottom: 10px;
        }

        .wish-card p {
            color: #555;
            font-size: 0.95em;
        }

        .footer {
            text-align: center;
            color: white;
            margin-top: 50px;
            font-size: 1.3em;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }
            .card {
                padding: 25px;
            }
            .wishes-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="hearts" id="heartsContainer"></div>
    
    <div class="container">
        <div class="header">
            <h1>To My Beloved 💕</h1>
            <p>A love letter written with my whole heart</p>
        </div>

        <div class="card">
            <h2>My Dearest Love 💗</h2>
            <p>From the moment I wake up to the moment I fall asleep, you are my every thought, my every dream, my every wish. You've transformed my world from ordinary to extraordinary, from black and white to vibrant colors.</p>
            <p>You are not just my love - you are my home, my peace, my adventure, my forever. Every day with you is a blessing I never knew I needed, and now I can't imagine life without you.</p>
            <p>This page is my heart speaking to yours, across any distance, across any time, carrying all the love I have for you. ✨</p>
        </div>

        <div class="card">
            <h2>Reasons Why I Love You 💖</h2>
            <ul class="love-list">
                <li>Your smile lights up my entire world</li>
                <li>Your voice is my favorite sound</li>
                <li>You make me believe in magic and miracles</li>
                <li>You love me exactly as I am</li>
                <li>You're my safe place in this chaotic world</li>
                <li>You inspire me to be better every day</li>
                <li>Your laugh is contagious and beautiful</li>
                <li>You support my dreams like they're your own</li>
                <li>You make ordinary moments extraordinary</li>
                <li>You're my answered prayer</li>
            </ul>
        </div>

        <div class="card">
            <h2>My Wishes For You 🌟</h2>
            <div class="wishes-grid">
                <div class="wish-card">
                    <div class="emoji">💪</div>
                    <h3>Strength</h3>
                    <p>May you always have the strength to overcome any challenge</p>
                </div>
                <div class="wish-card">
                    <div class="emoji">🌈</div>
                    <h3>Happiness</h3>
                    <p>May your days be filled with endless joy and laughter</p>
                </div>
                <div class="wish-card">
                    <div class="emoji">🏆</div>
                    <h3>Success</h3>
                    <p>May all your dreams come true and goals be achieved</p>
                </div>
                <div class="wish-card">
                    <div class="emoji">💖</div>
                    <h3>Health</h3>
                    <p>May you be blessed with perfect health and long life</p>
                </div>
                <div class="wish-card">
                    <div class="emoji">🕊️</div>
                    <h3>Peace</h3>
                    <p>May your heart always find peace and tranquility</p>
                </div>
                <div class="wish-card">
                    <div class="emoji">✨</div>
                    <h3>Magic</h3>
                    <p>May every day bring you beautiful surprises</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Forever & Always 💍</h2>
            <p>I promise to love you through every season of life. Through sunny days and storms, through laughter and tears, through distance and togetherness.</p>
            <p>I promise to be your biggest cheerleader, your safe haven, your partner in everything. I promise to choose you, every single day, for the rest of my life.</p>
            <p>Our love story is my favorite, and I can't wait for all the chapters still to be written. Until we're together, know that you carry my heart with you, always.</p>
        </div>

        <div class="footer">
            <p>I Love You More Than Words Can Say 💕</p>
            <p>Forever Yours ♾️</p>
        </div>
    </div>

    <script>
        // Create floating hearts
        const heartsContainer = document.getElementById('heartsContainer');
        const heartSymbols = ['❤️', '💕', '💖', '💗', '💓', '💝'];
        
        function createHeart() {
            const heart = document.createElement('div');
            heart.className = 'heart';
            heart.textContent = heartSymbols[Math.floor(Math.random() * heartSymbols.length)];
            heart.style.left = Math.random() * 100 + '%';
            heart.style.animationDuration = (Math.random() * 10 + 10) + 's';
            heart.style.animationDelay = Math.random() * 5 + 's';
            heartsContainer.appendChild(heart);
            
            setTimeout(() => {
                heart.remove();
            }, 20000);
        }
        
        // Create hearts periodically
        setInterval(createHeart, 1000);
        
        // Create initial hearts
        for(let i = 0; i < 10; i++) {
            createHeart();
        }

        // Add stagger animation to love list items
        const listItems = document.querySelectorAll('.love-list li');
        listItems.forEach((item, index) => {
            item.style.animationDelay = (index * 0.1) + 's';
        });
    </script>
</body>
</html>
