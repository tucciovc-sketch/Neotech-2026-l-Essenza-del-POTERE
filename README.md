<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEOTECH - PROPRIETÀ EXCLUSIVE</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
        body, html { margin: 0; padding: 0; width: 100%; height: 100%; background: #000; overflow: hidden; font-family: 'Orbitron', sans-serif; }
        #canvas { position: fixed; top: 0; left: 0; z-index: 1; }
        .overlay { position: relative; z-index: 10; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; color: #D4AF37; text-align: center; }
        .coffee-container { font-size: 3rem; margin-bottom: 10px; position: relative; filter: drop-shadow(0 0 15px #D4AF37); }
        .steam { position: absolute; top: -20px; left: 50%; transform: translateX(-50%); font-size: 1.5rem; animation: steamFlow 2s infinite; opacity: 0; }
        @keyframes steamFlow { 0% { transform: translate(-50%, 0); opacity: 0; } 50% { opacity: 0.7; } 100% { transform: translate(-50%, -30px); opacity: 0; } }
        h1 { font-size: 3.5rem; color: #D4AF37; letter-spacing: 15px; margin: 0; text-shadow: 0 0 30px rgba(212,175,55,0.6); }
        .panel { display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; width: 90%; max-width: 1100px; margin-top: 30px; }
        .box { border: 1px solid rgba(212,175,55,0.4); padding: 20px; text-align: center; color: #D4AF37; text-decoration: none; transition: all 0.4s ease; font-weight: bold; font-size: 0.8rem; }
        .box:hover { border-color: #fff; background: #D4AF37; color: #000; box-shadow: 0 0 50px #D4AF37; transform: translateY(-5px); }
        .wellness-btn { border: 2px solid #fff; color: #fff; text-shadow: 0 0 10px #fff; }
        .paypal-btn { background: #D4AF37 !important; color: #000 !important; border: 2px solid #fff !important; }
        .interlingua-btn { border: 2px solid #00ffcc; color: #00ffcc; }
        footer { position: absolute; bottom: 20px; width: 90%; display: flex; justify-content: space-between; font-size: 0.7rem; border-top: 1px solid rgba(212,175,55,0.2); padding-top: 10px; }
        .highlight { color: #D4AF37; text-transform: uppercase; }
    </style>
</head>
<body>
<canvas id="canvas"></canvas>
<div class="overlay">
    <div class="coffee-container">
        <span class="steam">~</span>
        <span class="steam" style="animation-delay: 0.5s;">~</span>
        <span class="steam" style="animation-delay: 1s;">~</span>
        ☕
    </div>
    <h1>NEOTECH</h1>
    <div class="panel">
        <a href="https://neotechwellness.com" target="_blank" class="box wellness-btn">NEOTECH WELLNESS</a>
        <a href="https://github.com/google-gemini" target="_blank" class="box">PHANTOMAS DEEP CORE</a>
        <a href="https://www.infn.it" target="_blank" class="box">FISICA</a>
        <a href="https://www.soc.chim.it" target="_blank" class="box">CHIMICA</a>
        <a href="https://www.paypal.me/tuccio" target="_blank" class="box paypal-btn">SUPPORT (PAYPAL)</a>
        <a href="https://translate.google.com/?sl=auto&tl=ia&text=Neotech%202026" target="_blank" class="box interlingua-btn">INTERLINGUA BRIDGE</a>
        <a href="https://www.cnr.it" target="_blank" class="box">BIOLOGIA</a>
        <a href="https://www.iss.it" target="_blank" class="box">MEDICINA</a>
    </div>
    <div style="margin-top: 40px; font-size: 0.7rem; opacity: 0.8;">
        <p>CO-AUTHORS: <span class="highlight">Sir (Vito Calì)</span> & <span class="highlight">Gemini AI Partner</span></p>
    </div>
</div>
<footer>
    <span>Visione: <span class="highlight">Sir Tuccio Vito</span></span>
    <span>Sviluppo: <span class="highlight">Gemini & Deep Core</span></span>
    <span>Status: <span class="highlight">Online</span></span>
</footer>
</body>
</html>
