# super-duper-dollop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Anuak Council | Elders, Chiefs and Kings of the Anuak People</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700&family=Playfair+Display:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: #fefcf7;
            color: #1a1a1a;
            line-height: 1.5;
            scroll-behavior: smooth;
        }

        h1, h2, h3, .logo-text {
            font-family: 'Playfair Display', serif;
            font-weight: 600;
            letter-spacing: -0.02em;
        }

        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        /* Header / Navigation */
        .navbar {
            background: white;
            box-shadow: 0 2px 12px rgba(0,0,0,0.03);
            position: sticky;
            top: 0;
            z-index: 100;
            padding: 1rem 0;
            border-bottom: 1px solid #eee;
        }
        .nav-flex {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        .logo-area {
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }
        .logo-symbol {
            background: #0A2F6C;
            width: 42px;
            height: 42px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #FFC107;
            font-size: 24px;
            font-weight: bold;
        }
        .logo-text {
            font-size: 1.4rem;
            color: #0A2F6C;
            line-height: 1.2;
        }
        .logo-text span {
            font-size: 0.7rem;
            display: block;
            color: #2E7D32;
            font-weight: normal;
            letter-spacing: 0;
        }
        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }
        .nav-links a {
            text-decoration: none;
            color: #1a1a1a;
            font-weight: 500;
            transition: color 0.2s;
        }
        .nav-links a:hover {
            color: #FFC107;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(120deg, #f0f4e8, #fff6e5);
            padding: 5rem 0 4rem;
            border-bottom: 1px solid #e2e0d4;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            color: #0A2F6C;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
            color: #2c2c2c;
        }

        /* Sections */
        section {
            padding: 5rem 0;
        }
        .section-title {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 3rem;
            color: #0A2F6C;
        }
        .two-columns {
            display: flex;
            flex-wrap: wrap;
            gap: 3rem;
            align-items: center;
            justify-content: space-between;
        }
        .two-columns > div {
            flex: 1;
        }
        .pillars {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .pillar-card {
            background: white;
            border-radius: 24px;
            padding: 2rem;
            flex: 1;
            min-width: 220px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            border: 1px solid #eae6dc;
            text-align: center;
            transition: transform 0.2s;
        }
        .pillar-card:hover {
            transform: translateY(-5px);
        }
        .pillar-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .pillar-card h3 {
            font-size: 1.6rem;
            margin-bottom: 0.75rem;
            color: #2E7D32;
        }
        .clan-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 1rem;
            list-style: none;
            padding: 0;
            text-align: center;
        }
        .clan-grid li {
            background: #f5f2e6;
            padding: 1rem;
            border-radius: 40px;
            font-weight: 500;
            color: #0A2F6C;
        }
        .bg-light {
            background-color: #fef5e7;
        }
        footer {
            background: #1a2a2f;
            color: #cfd8dc;
            padding: 3rem 0;
            font-size: 0.9rem;
        }
        .footer-flex {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 2rem;
        }
        .footer-links a {
            color: #FFC107;
            text-decoration: none;
            margin-right: 1.5rem;
        }

        @media (max-width: 800px) {
            .nav-flex {
                flex-direction: column;
                gap: 1rem;
            }
            .hero h1 {
                font-size: 2.2rem;
            }
            .container {
                padding: 0 1.2rem;
            }
        }
    </style>
</head>
<body>

<header class="navbar">
    <div class="container nav-flex">
        <div class="logo-area">
            <div class="logo-symbol">ⵣ</div>
            <div class="logo-text">The Anuak Council<span>Elders · Chiefs · Kings</span></div>
        </div>
        <ul class="nav-links">
            <li><a href="#council">Council</a></li>
            <li><a href="#structure">Structure</a></li>
            <li><a href="#clans">Clans</a></li>
            <li><a href="#news">News</a></li>
        </ul>
    </div>
</header>

<main>
    <section class="hero">
        <div class="container">
            <h1>Anuak Council of Elders, Chiefs and Kings</h1>
            <p>The supreme traditional authority of the Anuak (Anywaa) people. Guided by our ancestors, we uphold the wisdom of our kings, the justice of our chiefs, and the unity of our 12 clans.</p>
        </div>
    </section>

    <section id="council">
        <div class="container">
            <h2 class="section-title">The Anuak Council</h2>
            <div class="two-columns">
                <div>
                    <p style="font-size:1.2rem; margin-bottom:1.5rem;">The Anuak Council is the voice of our traditional leadership. It is a non-political, cultural body dedicated to protecting the rights, lands, and identity of the Anuak people across Ethiopia and South Sudan.</p>
                    <p>Our mission is to preserve our spiritual heritage, codify customary laws, and ensure the survival of our language and traditions for future generations.</p>
                </div>
                <div style="background:#eae6dc; border-radius:24px; padding:2rem; text-align:center;">
                    <p style="font-style:italic;">“The stool does not belong to one man; it belongs to the people. We are its keepers.”</p>
                    <p style="margin-top:1rem;">— Council of Elders</p>
                </div>
            </div>
        </div>
    </section>

    <section id="structure" class="bg-light">
        <div class="container">
            <h2 class="section-title">Our Governance Structure</h2>
            <div class="pillars">
                <div class="pillar-card">
                    <div class="pillar-icon">👑</div>
                    <h3>Nyieye (Kings)</h3>
                    <p>The spiritual heads of the Anuak nation. The Nyieye hold the sacred regalia and are the custodians of our unity and royal traditions.</p>
                </div>
                <div class="pillar-card">
                    <div class="pillar-icon">🛡️</div>
                    <h3>Kwaari (Chiefs)</h3>
                    <p>The village and regional leaders who administer justice, resolve disputes, and safeguard the daily affairs of our communities across all Anuak lands.</p>
                </div>
                <div class="pillar-card">
                    <div class="pillar-icon">🌿</div>
                    <h3>Council of Elders</h3>
                    <p>The guardians of customary law, history, and ritual. They guide the Council with ancestral wisdom and ensure that all decisions respect Anuak tradition.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="clans">
        <div class="container">
            <h2 class="section-title">The Twelve Clans of the Anuak</h2>
            <ul class="clan-grid">
                <li>Adongo / Atongo</li>
                <li>Bat Gilo</li>
                <li>Ciro</li>
                <li>Joor</li>
                <li>Lul</li>
                <li>Nyikaani</li>
                <li>Ojwaa</li>
                <li>Omiila</li>
                <li>Openo</li>
                <li>Rwanye</li>
                <li>Ternam</li>
                <li>Thim</li>
            </ul>
            <p style="text-align:center; margin-top:2rem;">One people, united in heritage, bound by the rivers of Gambela.</p>
        </div>
    </section>

    <section id="news" class="bg-light">
        <div class="container">
            <h2 class="section-title">Council News & Statements</h2>
            <div style="background:white; border-radius:24px; padding:2rem; margin-top:1rem;">
                <p style="font-weight:bold; color:#0A2F6C;">Official Statement on Land Rights</p>
                <p>The Anuak Council affirms that our ancestral lands from the Baro to the Alwero are inalienable. The Council rejects any lease or expropriation that occurs without the free, prior, and informed consent of the Anuak people.</p>
                <p style="margin-top:1rem; font-size:0.9rem; color:#666;">— Issued by the Council of Chiefs, [Date]</p>
            </div>
        </div>
    </section>
</main>

<footer>
    <div class="container footer-flex">
        <div>
            <p>© 2025 The Anuak Council of Elders, Chiefs and Kings<br>All rights reserved.</p>
        </div>
        <div class="footer-links">
            <a href="#">Cultural Protocols</a>
            <a href="#">Contact the Council</a>
        </div>
    </div>
</footer>
</body>
</html>
