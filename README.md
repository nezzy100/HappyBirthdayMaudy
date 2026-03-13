# HappyBirthdayMaudy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine? ❤️</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="particles-js"></div>

    <div class="container">
        <div id="screen1" class="screen active">
            <div class="icon-header">💝</div>
            <h1>Will you be my Valentine?</h1>
            <p>I have a special question for you...</p>
            <div class="btn-group">
                <button id="yesBtn" class="btn btn-yes">YES!</button>
                <button id="noBtn" class="btn btn-no">NO</button>
            </div>
        </div>

        <div id="screen2" class="screen">
            <h1>Yay! ❤️</h1>
            <p>Kapan kita jalan bersama?</p>
            <input type="date" id="dateInput">
            <button class="btn btn-next" onclick="saveData('date', 3)">Lanjut ✨</button>
        </div>

        <div id="screen3" class="screen">
            <h1>🎬 Movie Night</h1>
            <p>Nonton film apa bareng?</p>
            <input type="text" id="movieInput" placeholder="Judul film favoritmu...">
            <button class="btn btn-next" onclick="saveData('movie', 4)">Lanjut ✨</button>
        </div>

        <div id="screen4" class="screen">
            <h1>✈️ Dream Trip</h1>
            <p>Liburan ke mana nanti?</p>
            <input type="text" id="travelInput" placeholder="Ke mana kita pergi?">
            <button class="btn btn-next" onclick="saveData('travel', 5)">Selesai 💖</button>
        </div>

        <div id="screen5" class="screen">
            <div class="icon-header">✨</div>
            <h1>It's a Date!</h1>
            <div id="summaryResult" class="summary-box"></div>
            <p class="closing-text">"Aku nggak sabar ngelewatin semuanya bareng kamu!"</p>
            <button class="btn btn-save" onclick="window.print()">Simpan Kenangan 📸</button>
        </div>
    </div>

    <script src="script
