# Mausund-B-ttaxi
Mausund båttaxi nettsiden 
<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <title>Båt Taxi - Iver Johan Arnesen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #e6f7ff;
        }

        header {
            background: #0077b6;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #023e8a;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        .box {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        footer {
            background: #0077b6;
            color: white;
            text-align: center;
            padding: 10px;
        }

        .button {
            background: #0096c7;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            box-sizing: border-box;
        }

        .info-box {
            background: #fff3cd;
            padding: 15px;
            margin: 15px 0;
            border-left: 5px solid #ffc107;
            border-radius: 5px;
        }

        .price-list {
            background: #d4edda;
            padding: 15px;
            margin: 15px 0;
            border-left: 5px solid #28a745;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>🚤 Båt Taxi Mausund</h1>
    <p>Rask og trygg transport på sjøen</p>
</header>

<nav>
    <a href="#om">Om oss</a>
    <a href="#tilgjengelig">Tilgjengelighet</a>
    <a href="#priser">Priser</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<section id="om">
    <div class="box">
        <h2>Om oss</h2>
        <p>Velkommen til Båt Taxi! Vi tilbyr rask og trygg båttransport rundt <strong>Mausund</strong>. Vi er stolte deltakere i <strong>Ut i havet festival</strong>!</p>
        
        <div class="info-box">
            <h3>📋 Viktig informasjon:</h3>
            <ul>
                <li>👥 <strong>Kapasitet:</strong> Max 5 personer per båt</li>
                <li>🔄 <strong>Flere turer:</strong> Vi kan kjøre flere turer hvis det trengs</li>
                <li>🎉 <strong>Festival:</strong> Vi kjører under "Ut i havet festival"</li>
            </ul>
        </div>
    </div>
</section>

<section id="priser">
    <div class="price-list">
        <h2>💰 Priser</h2>
        <ul>
            <li><strong>125 kr per person</strong> - Rundt Mausund</li>
            <li><strong>Høyere pris</strong> - For lengere distanser (avtales ved henvendelse)</li>
        </ul>
        <p><em>Vi tilbyr flere turer hvis det trengs for din gruppe!</em></p>
    </div>
</section>

<section id="tilgjengelig">
    <div class="box">
        <h2>📅 Bestill tur</h2>

        <label>Dato:</label>
        <input type="date">

        <label>Tid:</label>
        <input type="time">

        <label>Rute (f.eks. Bergen - Askøy):</label>
        <input type="text" placeholder="f.eks. Mausund - Hovedøy">

        <label>Antall personer:</label>
        <input type="number" min="1" max="5" placeholder="Maks 5 personer">

        <br><br>
        <button class="button">Lagre bestilling</button>
    </div>
</section>

<section id="kontakt">
    <div class="box">
        <h2>📞 Kontakt oss</h2>

        <div class="info-box">
            <h3>Direkte kontakt:</h3>
            <p><strong>Navn:</strong> Iver Johan Arnesen</p>
            <p><strong>Telefon:</strong> <a href="tel:93004432" style="color: #0077b6;">93004432</a></p>
            <p><strong>Email:</strong> <a href="mailto:iver.johan.arnesen@gmail.com" style="color: #0077b6;">iver.johan.arnesen@gmail.com</a></p>
        </div>

        <h3>Send oss en melding:</h3>
        <label>Navn:</label>
        <input type="text" placeholder="Ditt navn">

        <label>Email:</label>
        <input type="email" placeholder="Din epostadresse">

        <label>Melding:</label>
        <textarea rows="4" placeholder="Din melding..."></textarea>

        <br><br>
        <button class="button">Send melding</button>
    </div>
</section>

<footer>
    <p>© 2026 Båt Taxi Mausund - Iver Johan Arnesen | Tlf: 93004432</p>
</footer>

</body>
</html>
