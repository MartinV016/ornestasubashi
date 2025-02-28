<!DOCTYPE html>
<html lang="sq">
<head>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Zyra Juridike Pronesore Ornesta Subashi ofron konsulencë ligjore dhe ndihmë në çështje pronësore.">
    <title>Zyrë Juridike Pronesore - Ornesta Subashi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ecf0f1;
            color: #2c3e50;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 30px 15px;
            text-align: center;
            font-size: 1.3em;
        }
        .container, .services, .contact {
            width: 90%;
            margin: 10px auto;
            padding: 15px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: left;
        }
        h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 5px;
            text-align: center;
            font-size: 1.2em;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            padding: 8px;
            transition: 0.3s;
        }
        ul li:hover {
            background-color: #bdc3c7;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact-btn {
            display: block;
            width: 85%;
            margin: 10px auto;
            padding: 8px;
            background-color: #27ae60;
            color: white;
            text-align: center;
            font-size: 1em;
            text-decoration: none;
            border-radius: 5px;
        }
        .contact-btn:hover {
            background-color: #2ecc71;
        }
        .map-container {
            width: 90%;
            height: 250px;
            margin: 10px auto;
            border-radius: 10px;
            overflow: hidden;
        }
        .map-container iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        @media (max-width: 768px) {
            header {
                padding: 20px 15px;
                font-size: 1.1em;
            }
            h2 {
                font-size: 1.1em;
            }
            .contact-btn {
                width: 90%;
                font-size: 0.9em;
            }
            .map-container {
                width: 95%;
                height: 220px;
            }
            .container, .services, .contact {
                width: 95%;
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Zyra Juridike Pronesore - Ornesta Subashi</h1>
    </header>
    <div id="about" class="container">
        <h2>Miresevini</h2>
        <p>Ne ofrojme sherbime juridike te specializuara ne ceshtjet pronesore.</p>
    </div>
    <div id="services" class="services">
        <h2>Shërbimet Tona</h2>
        <ul>
            <li>Konsulencë juridike</li>
            <li>Ndihmë në procese pronësore</li>
            <li>Hartim kontratash</li>
            <li>Zgjidhje mosmarrëveshjesh</li>
        </ul>
    </div>
    <div id="contact" class="contact">
        <h2>Kontakt</h2>
        <p><strong>Email:</strong> info@ornestasubashi.al</p>
        <p><strong>Telefon:</strong> +355 123 456 789</p>
        <p><strong>Adresa:</strong> Rruga Panorama, përballë Hipotekës, Tirana, Albania</p>
        <a class="contact-btn" href="tel:+355123456789">📞 Telefononi Tani</a>
        <div class="map-container">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3112.9374518931424!2d19.80975!3d41.335944!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x135031004971455f%3A0xee0a0a34cdd4442a!2sJustice%20Ornesta%20Subashi!5e0!3m2!1ssq!2s!4v1709158278452" allowfullscreen></iframe>
        </div>
    </div>
</body>
</html>
