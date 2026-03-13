<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine? 💙</title>
    <style>
        /* CSS Variabel untuk Tema Biru Romantis */
        :root {
            --bg-gradient: linear-gradient(135deg, #a2c2e1 0%, #d4e5ff 100%);
            --glass-bg: rgba(255, 255, 255, 0.4);
            --glass-border: rgba(255, 255, 255, 0.6);
            --accent-blue: #5d9cec;
            --dark-blue: #4a90e2;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: var(--bg-gradient);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            color: #333;
        }

        /* Latar Belakang Bergerak */
        .ocean-bg {
            position: absolute;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }

        .bubble {
            position: absolute;
            background: rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            animation: rise 10s infinite ease-in;
            bottom: -20px;
        }

        @keyframes rise {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            100% { transform: translateY(-110vh) scale(1.5); opacity: 0; }
        }

        /* Container Utama (Glassmorphism) */
        .container {
            background: var(--glass-bg);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid var(--glass-border);
            padding: 40px;
            border-radius: 30px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.15);
            text-align: center;
            width: 90%;
            max-width: 450px;
            transition: all 0.5s ease;
        }

        .screen { display: none; }
        .active { display: block; animation: slideUp 0.6s ease-out; }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h1 { font-size: 26px; color: var(--dark-blue); margin-bottom: 10px; }
        p { font-size: 16px; margin-bottom: 25px; opacity: 0.8; }

        /* Buttons */
        .btn-wrapper {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            height: 60px;
            position: relative;
        }

        .btn {
            padding: 12px 35px;
            border-radius: 50px;
            border: none;
            cursor: pointer;
            font-weight: 600;
            font-size: 16px;
            transition: all 0.3s;
            box-shadow: 0 4px 1
