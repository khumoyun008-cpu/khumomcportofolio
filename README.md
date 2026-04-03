<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KhumoMC Portfolio</title>
    
    <style>
        /* CSS KODLARI SHU YERDA */
        body {
            background: #0b0f1a;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
        }

        nav {
            background: #000;
            padding: 15px;
            text-align: center;
        }

        .logo {
            color: #00d4ff;
            font-size: 22px;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
        }

        .hero h1 {
            color: #00d4ff;
        }

        .section {
            padding: 30px;
            text-align: center;
        }

        .card {
            background: #111827;
            margin: 15px auto;
            padding: 15px;
            max-width: 400px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 212, 255, 0.2);
        }

        a {
            color: #00d4ff;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #000;
            margin-top: 30px;
        }

        #typing {
            font-size: 1.2rem;
            min-height: 1.5em;
        }
    </style>
</head>

<body>

    <nav>
        <div class="logo">🎮 KhumoMC</div>
    </nav>

    <section class="hero">
        <h1>🔥 KhumoMC haqida ma'lumotlar</h1>
        <p id="typing"></p>
    </section>

    <section class="section">
        <h2>⚔️ Minecraft turlaridagi skillar</h2>
        <div class="card">🗡 PvP (2022-2024): <b>85%</b></div>
        <div class="card">⚔ PvP (2025): <b>55-65%</b></div>
        <div class="card">🏗 Building (2018-2026): <b>92%</b></div>
        <div class="card">🧠 IQ (2020-2026): <b>94%</b></div>
    </section>

    <section class="section">
        <h2>📡 Kanallar</h2>
        <div class="card">
            📺 YouTube: 
            <a href="https://www.youtube.com/channel/UCQHDnJq_WNBrOXQaaySiu3w" target="_blank">Ochish</a>
        </div>
        <div class="card">
            ✈ Telegram: 
            <a href="https://t.me/khumominecraft" target="_blank">Ochish</a>
        </div>
    </section>

    <section class="section">
        <h2>📩 Bog‘lanish</h2>
        <div class="card">
            ❌ Ushbu bo‘lim hozirda ishlamaydi!<br><br>
            👉 Telegram kanalga o‘tib Admin bilan bog‘laning.
        </div>
    </section>

    <footer>
        ⚡ KhumoMC | Minecraft Player
    </footer>

    <script>
        // JAVASCRIPT KODLARI SHU YERDA
        const text = "🎮 Minecraft Player | PvP | Builder | Pro Gamer";
        let i = 0;

        function typing(){
            if(i < text.length){
                document.getElementById("typing").innerHTML += text.charAt(i);
                i++;
                setTimeout(typing, 50);
            }
        }

        // Sahifa yuklanganda yozish effektini boshlash
        window.onload = typing;
    </script>

</body>
</html>
