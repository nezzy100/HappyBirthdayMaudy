<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine? 💕</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #fecfef 100%);
            height: 100vh;
            overflow: hidden;
            position: relative;
            cursor: none;
        }

        /* Floating hearts background */
        .heart {
            position: absolute;
            font-size: 20px;
            color: #ff69b4;
            animation: float 6s ease-in-out infinite;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 1; }
            50% { transform: translateY(-20px) rotate(180deg); opacity: 0.8; }
        }

        /* Custom cursor */
        .cursor {
            position: fixed;
            width: 20px;
            height: 20px;
            background: radial-gradient(circle, #ff69b4, transparent);
            border-radius: 50%;
            pointer-events: none;
            z-index: 9999;
            transition: transform 0.1s ease;
        }

        /* Screen containers */
        .screen {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
        }

        .screen.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* Proposal screen */
        .proposal h1 {
            font-size: 3.5rem;
            color: #fff;
            text-shadow: 0 4px 8px rgba(0,0,0,0.3);
            margin-bottom: 3rem;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .yes-btn {
            font-size: 2rem;
            padding: 20px 40px;
            background: linear-gradient(45deg, #ff6b9d, #ff8fab);
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 10px 30px rgba(255, 107, 157, 0.4);
            transition: all 0.3s ease;
            position: relative;
            z-index: 10;
        }

        .yes-btn:hover {
            transform: scale(1.1) translateY(-5px);
            box-shadow: 0 20px 40px rgba(255, 107, 157, 0.6);
        }

        /* NO button - magical disappearing */
        .no-btn {
            font-size: 1.5rem;
            padding: 15px 30px;
            background: linear-gradient(45deg, #a8e6cf, #b8f2e6);
            color: #333;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 8px 25px rgba(168, 230, 207, 0.4);
            transition: all 0.3s ease;
            position: absolute;
            z-index: 5;
        }

        .no-btn:hover {
            transform: scale(0.1) rotate(360deg);
            opacity: 0;
        }

        /* Celebration screen */
        .celebration {
            text-align: center;
        }

        .celebration h2 {
            font-size: 4rem;
            color: #fff;
            text-shadow: 0 4px 8px rgba(0,0,0,0.3);
            margin-bottom: 2rem;
        }

        /* Date questions */
        .question-screen {
            max-width: 600px;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.2);
            text-align: center;
        }

        .question-screen h3 {
            font-size: 2rem;
            color: #ff6b9d;
            margin-bottom: 2rem;
        }

        .question-screen input, .question-screen select {
            width: 100%;
            padding: 15px;
            font-size: 1.2rem;
            border: 2px solid #ff9a9e;
            border-radius: 10px;
            margin-bottom: 1.5rem;
            transition: border-color 0.3s ease;
        }

        .question-screen input:focus, .question-screen select:focus {
            outline: none;
            border-color: #ff6b9d;
            box-shadow: 0 0 20px rgba(255, 107, 157, 0.3);
        }

        .next-btn {
            background: linear-gradient(45deg, #ff6b9d, #ff8fab);
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 25px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .next-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(255, 107, 157, 0.4);
        }

        /* Final summary */
        .summary {
            max-width: 700px;
            padding: 3rem;
            background: rgba(255, 255, 255, 0.98);
            border-radius: 25px;
            box-shadow: 0 25px 70px rgba(0,0,0,0.2);
            text-align: center;
        }

        .summary h2 {
            color: #ff6b9d;
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }

        .answer-item {
            background: linear-gradient(135deg, #ff9a9e, #fecfef);
            padding: 1.5rem;
            margin: 1rem 0;
            border-radius: 15px;
            color: white;
            font-size: 1.2rem;
        }

        .save-btn {
            background: linear-gradient(45deg, #4ecdc4, #44a08d);
            color: white;
            border: none;
            padding: 15px 40px;
            border-radius: 30px;
            font-size: 1.2rem;
            cursor: pointer;
            margin-top: 2rem;
            transition: all 0.3s ease;
        }

        .save-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 35px rgba(78, 205, 196, 0.4);
        }

        /* Confetti particles */
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background: #ff69b4;
            pointer-events: none;
            z-index: 100;
        }

        /* Hide screens initially */
        .proposal { z-index: 20; }
    </style>
</head>
<body>
    <!-- Custom cursor -->
    <div class="cursor" id="cursor"></div>

    <!-- Proposal Screen -->
    <div class="screen proposal active" id="proposal">
        <div class="heart" style="left: 10%; animation-delay: 0s;">💖</div>
        <div class="heart" style="left: 20%; animation-delay: 1s;">💕</div>
        <div class="heart" style="left: 80%; animation-delay: 2s;">💗</div>
        <div class="heart" style="right: 10%; animation-delay: 3s;">💝</div>
        
        <h1>Will you be my Valentine? 💕</h1>
        <button class="yes-btn" id="yesBtn">YES! 💖</button>
        <button class="no-btn" id="noBtn">NO 😢</button>
    </div>

    <!-- Celebration Screen -->
    <div class="screen celebration" id="celebration">
        <h2>YAYYY! 💖✨</h2>
        <p style="font-size: 1.5rem; color: #fff; margin-bottom: 2rem;">Aku seneng banget! Sekarang yuk rencanain kencan kita! 💕</p>
    </div>

    <!-- Question Screens -->
    <div class="screen question-screen" id="q1">
        <h3>1. Kapan kita ketemu lagi? 📅</h3>
        <input type="date" id="dateInput">
        <button class="next-btn" onclick="nextQuestion(1)">Next 💕</button>
    </div>

    <div class="screen question-screen" id="q2">
        <h3>2. Nonton film apa bareng? 🎬</h3>
        <select id="movieInput">
            <option value="">Pilih film romantis favoritmu...</option>
            <option value="Titanic">Titanic 💔</option>
            <option value="The Notebook">The Notebook 💕</option>
            <option value="La La Land">La La Land ✨</option>
            <option value="Your Name">Your Name 🌸</option>
            <option value="Lainnya (ketik sendiri)">Lainnya...</option>
        </select>
        <input type="text" id="customMovie" placeholder="Kalau lainnya, tulis di sini..." style="display: none;">
        <button class="next-btn" onclick="nextQuestion(2)">Next 💕</button>
    </div>

    <div class="screen question-screen" id="q3">
        <h3>3. Liburan ke mana depan? ✈️</h3>
        <input type="text" id="travelInput" placeholder="Bali? Jepang? Paris? Atau ke warung kopi? ☕">
        <button class="next-btn" onclick="nextQuestion(3)">Selesai! 💖</button>
    </div>

    <!-- Final Summary -->
    <div class="screen summary" id="summary">
        <h2>Memory Kita 💕</h2>
        <p style="font-size: 1.3rem; color: #666; margin-bottom: 2rem;">
            Aku nggak salah pilih kamu! Ini rencana kencan kita:
        </p>
        <div id="answersList"></div>
        <p style="font-size: 1.5rem; color: #ff6b9d; margin: 2rem 0; font-style: italic;">
            "Semuanya bakal lebih indah bareng kamu" 💖
        </p>
        <button class="save-btn" onclick="saveMemory()">💾 Save This Memory</button>
    </div>

    <script>
        // Global variables
        let currentScreen = 0;
        let answers = {};
        let noButton = document.getElementById('noBtn');
        let screens = document.querySelectorAll('.screen');

        // Custom cursor
        document.addEventListener('mousemove', (e) => {
            const cursor = document.getElementById('cursor');
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';
        });

        // NO button magic - moves away from cursor
        document.addEventListener('mousemove', (e) => {
            const rect = noButton.getBoundingClientRect();
            const cursorX = e.clientX;
            const cursorY = e.clientY;
            
            const distance = Math.sqrt(
                Math.pow(cursorX - (rect.left + rect.width/2), 2) + 
                Math.pow(cursorY - (rect.top + rect.height/2), 2)
            );
            
            if (distance < 100) {
                // Move button randomly
                const maxX = window.innerWidth - 150;
                const maxY = window.innerHeight - 100;
                noButton.style.left = Math.random() * maxX + 'px';
                noButton.style.top = Math.random() * maxY + 'px';
                noButton.style.transform = `scale(${0.8 + Math.random() * 0.4})`;
            }
        });

        // YES button click
        document.getElementById('yesBtn').addEventListener('click', function() {
            showScreen('celebration');
            createConfetti();
            setTimeout(() => showScreen('q1'), 2000);
        });

        // Custom movie input
        document.getElementById('movieInput').addEventListener('change', function() {
            const customInput = document.getElementById('customMovie');
            if (this.value === 'Lainnya (ketik sendiri)') {
                customInput.style.display = 'block';
            } else {
                customInput.style.display = 'none';
                answers.movie = this.value;
            }
        });

        document.getElementById('customMovie').addEventListener('input', function() {
            answers.movie = this.value;
        });

        // Screen navigation
        function showScreen(screenId) {
            screens.forEach(screen => screen.classList.remove('active'));
            document.getElementById(screenId).classList.add('active');
        }

        function nextQuestion(questionNum) {
            // Save answer
            if (questionNum === 1) {
                answers.date = document.getElementById('dateInput').value;
            } else if (questionNum === 2) {
                answers.movie = document.getElementById('movieInput').value || 
                               document.getElementById('customMovie').value;
            } else if (questionNum === 3) {
                answers.travel = document.getElementById('travelInput').value;
            }

            if (questionNum < 3) {
                showScreen(`q${questionNum + 1}`);
            } else {
                showSummary();
            }
        }

        function showSummary() {
            const answersList = document.getElementById('answersList');
            answersList.innerHTML = `
                <div class="answer-item">📅 Ketemu lagi tanggal: <strong>${answers.date || 'Belum dipilih'}</strong></div>
                <div class="answer-item">🎬 Nonton: <strong>${answers.movie || 'Belum dipilih'}</strong></div>
                <div class="answer-item">✈️ Liburan ke: <strong>${answers.travel || 'Belum dipilih'}</strong></div>
            `;
            showScreen('summary');
        }

        function saveMemory() {
            // Create a screenshot-friendly version
            html2canvas(document.body).then(canvas => {
                const link = document.createElement('a');
                link.download = 'valentine-memory.png';
                link.href = canvas.toDataURL();
                link.click();
            });
        }

        // Confetti effect
        function createConfetti() {
            for (let i = 0; i < 100; i++) {
                const confetti = document.createElement('div');
                confetti.className = 'confetti';
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.backgroundColor = `hsl(${Math.random() * 60 + 300}, 100%, 60%)`;
                confetti.style.animation = `fall ${2 + Math.random() * 3}s linear forwards`;
                document.body.appendChild(confetti);

                setTimeout(() => confetti.remove(), 5000);
            }
        }

        // Add falling animation
        const style = document.createElement('style');
        style.textContent = `
            @keyframes fall {
                to {
                    transform: translateY(100vh) rotate(720deg);
                    opacity: 0;
                }
            }
        `;
        document.head.appendChild(style);

        // Generate floating hearts continuously
        setInterval(() => {
            const heart = document.createElement('div');
            heart.className = 'heart';
            heart.innerHTML = ['💖', '💕', '💗', '💝', '✨'][Math.floor(Math.random() * 5)];
            heart.style.left = Math.random() * 100 + '%';
            heart.style.animationDuration = (3 + Math.random() * 3) + 's';
            heart.style.animationDelay = Math.random() * 2 + 's';
            document.body.appendChild(heart);
            
            setTimeout(() => heart.remove(), 8000);
        }, 1000);

        // Auto-focus first input
        setTimeout(() => {
            const dateInput = document.getElementById('dateInput');
            if (dateInput) dateInput.focus();
        }, 2500);
    </script>

    <!-- html2canvas for screenshot -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
</body>
</html>
