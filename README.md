# HappyBirthdayMaudy
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine? 💕</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Landing Page -->
    <div class="page landing-page active">
        <div class="background-decoration">
            <div class="heart heart-1">❤️</div>
            <div class="heart heart-2">💕</div>
            <div class="heart heart-3">💖</div>
            <div class="heart heart-4">✨</div>
            <div class="heart heart-5">⭐</div>
            <div class="heart heart-6">💑</div>
        </div>

        <div class="landing-content">
            <h1 class="main-title">Will you be my</h1>
            <h2 class="valentine-text">Valentine? 💕</h2>
            
            <div class="buttons-container">
                <button class="btn btn-yes" onclick="goToQuestions()">YES 💗</button>
                <button class="btn btn-no" id="noBtn">NO 💔</button>
            </div>

            <p class="subtitle">Choose wisely... 😉</p>
        </div>
    </div>

    <!-- Questions Page -->
    <div class="page questions-page">
        <div class="questions-container">
            <button class="back-btn" onclick="goToLanding()">← Back</button>
            
            <div class="question-item active" id="question1">
                <h3>Kapan kita bersama? 📅</h3>
                <input type="date" id="dateAnswer" class="input-field">
                <button class="next-btn" onclick="nextQuestion()">Next →</button>
            </div>

            <div class="question-item" id="question2">
                <h3>Nonton film apa bareng? 🎬</h3>
                <input type="text" id="movieAnswer" class="input-field" placeholder="Contoh: Pulp Fiction">
                <button class="next-btn" onclick="nextQuestion()">Next →</button>
            </div>

            <div class="question-item" id="question3">
                <h3>Liburan ke mana depan? 🌴</h3>
                <input type="text" id="vacationAnswer" class="input-field" placeholder="Contoh: Paris">
                <button class="next-btn" onclick="submitAnswers()">Selesai ✨</button>
            </div>
        </div>
    </div>

    <!-- Summary Page -->
    <div class="page summary-page">
        <button class="back-btn" onclick="goToQuestions()">← Back</button>
        
        <div class="summary-container">
            <h2 class="summary-title">Our Beautiful Journey 💕</h2>
            
            <div class="summary-content">
                <div class="summary-item">
                    <span class="summary-label">Kita bersama:</span>
                    <span class="summary-value" id="summaryDate">-</span>
                </div>
                <div class="summary-item">
                    <span class="summary-label">Film favorit kita:</span>
                    <span class="summary-value" id="summaryMovie">-</span>
                </div>
                <div class="summary-item">
                    <span class="summary-label">Liburan impian kita:</span>
                    <span class="summary-value" id="summaryVacation">-</span>
                </div>
            </div>

            <p class="romantic-text">
                "Aku nggak salah semuanya bareng kamu... 
                <br>dan aku ingin terus begini selamanya." 💖
            </p>

            <div class="action-buttons">
                <button class="btn btn-memory" onclick="saveMemory()">💾 Save This Memory</button>
                <button class="btn btn-screenshot" onclick="takeScreenshot()">📸 Screenshot</button>
            </div>

            <p class="footer-text">Made with love 💕 for you</p>
        </div>
    </div>

    <!-- Confetti Container -->
    <div id="confetti-container"></div>

    <script src="script.js"></script>
</body>
</html>
