# index.html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projet de Fin d'Études | Houria Merad</title>
    <title>Projet de Fin d'Études | Houria Merad</title>
    <style>
        :root {
            --primary-color: #1a2a6c;
            --secondary-color: #b21f1f;
            --accent-color: #fdbb2d;
            --bg-color: #f8f9fa;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            text-align: center;
            padding: 60px 20px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .logo-univ {
            width: 130px;
            background: white;
            padding: 10px;
            border-radius: 50%;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .container {
            max-width: 900px;
            margin: -40px auto 40px;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        h1 { font-size: 28px; margin-bottom: 10px; }
        h2 { color: var(--primary-color); border-left: 5px solid var(--secondary-color); padding-left: 15px; margin-top: 30px; font-size: 22px; }

        .info-grid {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 15px;
            margin-top: 20px;
            background: #f1f3f5;
            padding: 20px;
            border-radius: 10px;
        }

        .info-item { font-weight: bold; color: var(--primary-color); }
        
        .description-box {
            background: #fff;
            border-right: 5px solid var(--accent-color);
            padding: 20px;
            margin-top: 20px;
            text-align: right; /* للنص العربي */
            direction: rtl;
        }

        .footer {
            text-align: center;
            padding: 20px;
            font-size: 14px;
            color: #666;
        }

        /* Responsive */
        @media (max-width: 600px) {
            .info-grid { grid-template-columns: 1fr; }
            .container { width: 90%; margin-top: -20px; }
        }
    </style>
</head>
<body>

<header>
    <img src="https://upload.wikimedia.org/wikipedia/dz/4/45/Logo_University_of_Mascara.png" alt="Université de Mascara" class="logo-univ">
    <h1>Université Mustapha Stambouli de Mascara</h1>
    <p>Département d'Électrotechnique / Filière Électronique</p>
</header>

<div class="container">
    <h2>Fiche Technique du Projet</h2>
    <div class="info-grid">
        <div class="info-item">Titre du Projet:</div>
        <div>Conception et Réalisation d’un Système Intelligent de Détection d’Incidents Dangereux Monté sur un Drone</div>
        
        <div class="info-item">Réalisé par:</div>
        <div>Houria Merad</div>
        
        <div class="info-item">Niveau:</div>
        <div>2ème Année Électronique</div>
        
        <div class="info-item">Encadré par:</div>
        <div>(Mourad hebali)</div>
        
        <div class="info-item">Année Universitaire:</div>
        <div>2026 - 2027</div>
    </div>

    <h2>Description du Projet (Résumé)</h2>
    <div class="description-box">
        هذا المشروع يهدف إلى تصميم نظام مدمج يعتمد على حساسات  محمول على درون للكشف عن المخاطر مثل الحرائق وتسرب الغاز بشكل آلي وسريع، باستخدام تقنيات ESP32 و arduino uno.
    </div>

    <h2>Technologies Utilisées</h2>
    <ul>
        <li><strong>Hardware:</strong> ESP32s3, ESP32-CAM, MQ2, DHT22, BMP180, flamme,capteur pluie, pulse,led rouge et vert, lcd, oled,buzzer,gps,sim900,arduino uno,capteur de neveau de leau,esp8266.</li>
        <li><strong>Software:</strong> Arduino IDE, GitHub Pages.</li>
    </ul>
</div>

<div class="footer">
    &copy; 2026 Houria Merad - Rachida Merad - Faculté de Technologie - Mascara
</div>

</body>
</html>
