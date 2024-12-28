
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MK Tech - Votre expert en maintenance logicielle</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0e1f3d, #2c3e50);
            color: #fff;
        }
        header {
            background-color: #0e1f3d;
            color: white;
            padding: 20px 0;
            text-align: center;
            position: relative;
        }
        header img {
            max-width: 145px;
            position: absolute;
            top: 10px;
            left: 20px;
            animation: rotateLogo 4s infinite linear;
        }
        header h1 {
            display: inline-block;
            opacity: 0;
            animation: fadeInText 3s forwards;
            letter-spacing: 0.1em;
        }
        header h1 span {
            display: inline-block;
            opacity: 0;
            animation: fadeInLetter 3s forwards;
            animation-delay: calc(0.1s * var(--i));
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #00c4cc;
            padding: 10px 0;
            animation: slideDown 1s;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            margin: 0 15px;
            transition: transform 0.3s, color 0.3s;
        }
        nav a:hover {
            text-decoration: underline;
            transform: scale(1.1);
            color: #ffcc00;
        }

        section {
            padding: 20px;
            animation: fadeIn 1.5s;
        }

        .section-title {
            color: #ffcc00;
            margin-bottom: 10px;
        }

        footer {
            background-color: #00c4cc;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
            animation: fadeIn 2s;
        }

        .contact {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border: 1px solid #d6e4f5;
            animation: zoomIn 1s;
        }

        ul {
            list-style-type: disc;
            margin: 10px 0 20px 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            animation: fadeIn 1.5s;
        }

        table th, table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }

        table th {
            background-color: #00c4cc;
            color: white;
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideDown {
            from {
                transform: translateY(-20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes zoomIn {
            from {
                transform: scale(0.9);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        @keyframes spin {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        @keyframes backgroundGlow {
            0% {
                background: linear-gradient(135deg, #0e1f3d, #2c3e50);
            }
            100% {
                background: linear-gradient(135deg, #1a3b6b, #3a5c7f);
            }
        }

        @media (max-width: 768px) {
            header img {
                max-width: 100px;
                top: 5px;
                left: 10px;
            }
            nav {
                flex-direction: column;
                align-items: center;
            }
            nav a {
                margin: 5px 0;
            }
            table th, table td {
                font-size: 14px;
                padding: 6px;
            }
        }

        @keyframes fadeInText {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInLetter {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes rotateLogo {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="2.png" alt="MK Tech Logo">
        <h1>
            <span style="--i:1">B</span>
            <span style="--i:2">i</span>
            <span style="--i:3">e</span>
            <span style="--i:4">n</span>
            <span style="--i:5">v</span>
            <span style="--i:6">e</span>
            <span style="--i:7">n</span>
            <span style="--i:8">u</span>
            <span style="--i:9">e</span>
            <span style="--i:10"> </span>
            <span style="--i:11">c</span>
            <span style="--i:12">h</span>
            <span style="--i:13">e</span>
            <span style="--i:14">z</span>
            <span style="--i:15"> </span>
            <span style="--i:16">M</span>
            <span style="--i:17">K</span>
            <span style="--i:18"> </span>
            <span style="--i:19">T</span>
            <span style="--i:20">e</span>
            <span style="--i:21">c</span>
            <span style="--i:22">h</span>
        </h1>
        <p>Votre partenaire fiable pour la maintenance logicielle et les solutions informatiques</p>
    </header>
    <nav>
        <a href="#introduction">Introduction</a>
        <a href="#services">Nos Services</a>
        <a href="#tarifs">Tarifs</a>
        <a href="#avantages">Avantages</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="introduction">
        <p>Chez MK Tech, nous nous engageons à fournir des solutions rapides, efficaces et abordables pour vos besoins logiciels et informatiques. Avec une expertise dans la maintenance logicielle, nous garantissons des services de qualité adaptés à vos besoins spécifiques. Que ce soit pour un particulier ou une entreprise, nous sommes là pour optimiser vos outils numériques.</p>
    </section>

    <section id="services">
        <h2 class="section-title">Nos Offres de Services</h2>
        <ul>
            <li><strong>Diagnostic et conseil</strong> : Identification rapide des problèmes avec des conseils gratuits pour toute intervention.</li>
            <li><strong>Maintenance logicielle</strong> : Mise à jour, installation de logiciels, optimisation des performances, sécurité logicielle et plus encore.</li>
            <li><strong>Installation de jeux sur PC</strong> : Configuration optimale pour jeux légers ou lourds.</li>
            <li><strong>Maintenance ponctuelle et préventive</strong> : Interventions ponctuelles et plans de maintenance pour éviter les pannes.</li>
            <li><strong>Interventions d’urgence</strong> : Résolution rapide des pannes sur site ou à distance.</li>
            <li><strong>Sauvegarde et récupération de données</strong> : Sauvegarde sécurisée et récupération de données perdues.</li>
            <li><strong>Formation et assistance</strong> : Sessions pratiques pour améliorer vos compétences informatiques.</li>
        </ul>
    </section>

    <section id="tarifs">
        <h2 class="section-title">Nos Tarifs</h2>
        <table>
            <thead>
                <tr>
                    <th>Service</th>
                    <th>Tarif (FCFA)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Diagnostic rapide </td>
                    <td>3 000</td>
                </tr>
                <tr>
                    <td>Mise à jour logicielle</td>
                    <td>5 000</td>
                </tr>
                <tr>
                    <td>Installation de logiciels</td>
                    <td>5 000 - 7 000</td>
                </tr>
                <tr>
                    <td>Installation de jeux sur PC</td>
                    <td>1000 - 6000</td>
                </tr>
                <tr>
                    <td>Maintenance préventive mensuelle</td>
                    <td>15 000</td>
                </tr>
                <tr>
                    <td>Récupération de données</td>
                    <td>10 000 - 20 000</td>
                </tr>
                <tr>
                    <td>Formation de base sur logiciels</td>
                    <td>15 000</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="special">
        <h2 class="section-title">Offres spéciales</h2>
        <ul>
            <li><strong>Pack Entreprise : 30 000fcfa/mois (maintenance et assistance incluses)</strong></li>
            <li><strong>Fidélité client : 30 % de réduction après 3 interventions et des gadgets offerts.</strong></li>
        </ul>
    </section>

    <section id="avantages">
        <h2 class="section-title">Pourquoi choisir MK Tech ?</h2>
        <p>MK Tech se distingue par :</p>
        <ul>
            <li>Des services abordables et adaptés à tous les budgets.</li>
            <li>Une équipe experte et dévouée pour résoudre vos problèmes rapidement.</li>
            <li>Une assistance personnalisée et des conseils gratuits avec chaque intervention.</li>
            <li>Des solutions préventives pour garantir la longévité de vos systèmes.</li>
            <li>Une disponibilité même en cas d’urgence pour vous assurer une tranquillité d’esprit.</li>
        </ul>
    </section>

    <section id="contact">
        <h2 class="section-title">Contactez-nous</h2>
        <div class="contact">
            <p><strong>Adresse :</strong> Bobo Dioulasso, Burkina Faso</p>
            <p><strong>Téléphone :</strong> +226 64 77 27 99</p>
            <p><strong>Email :</strong> mktech2024@gmail.com</p>
            <p>Vous avez une question ou besoin d’une assistance ? N’hésitez pas à nous écrire ou à nous appeler, nous sommes là pour vous !</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 MK Tech Votre expert en maintenance logicielle</p>
    </footer>
</body>
</html>
