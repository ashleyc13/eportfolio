
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ashley Chun | Counselor Education</title>

    <style>

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            background-color: #ffffff;
            color: #222222;
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        /* Header */

        header {
            padding: 40px 5% 25px;
            text-align: center;
        }

        .site-name h1 {
            font-size: 32px;
            font-weight: 400;
            letter-spacing: 4px;
            margin: 0;
        }

        .site-name p {
            font-size: 12px;
            letter-spacing: 2px;
            color: #777777;
            margin-top: 12px;
        }

        /* Navigation menu */

        .main-nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 35px;
            padding-bottom: 25px;
            border-bottom: 1px solid #eeeeee;
        }

        .main-nav a {
            font-size: 14px;
            color: #222222;
            transition: color 0.2s;
        }

        .main-nav a:hover {
            color: #999999;
        }

        /* Main introduction */

        .hero {
            max-width: 1150px;
            margin: 60px auto 100px;
            padding: 0 6%;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: center;
        }

        .artwork {
            margin: 0;
        }

        .artwork img {
            display: block;
            width: 100%;
            height: auto;
        }

        .art-credit {
            font-size: 11px;
            color: #888888;
            margin-top: 10px;
        }

        .intro-label {
            font-size: 11px;
            letter-spacing: 2px;
            color: #777777;
        }

        .hero-text h2 {
            font-size: clamp(36px, 5vw, 60px);
            font-weight: 400;
            line-height: 1.2;
            letter-spacing: -1.5px;
            margin: 25px 0;
        }

        .hero-text p {
            font-size: 16px;
            color: #555555;
        }

        /* Footer */

        footer {
            border-top: 1px solid #eeeeee;
            padding: 40px 5%;
            text-align: center;
            font-size: 12px;
            color: #777777;
        }

        /* Mobile layout */

        @media (max-width: 700px) {

            header {
                padding: 30px 5% 15px;
            }

            .site-name h1 {
                font-size: 24px;
            }

            .main-nav {
                gap: 15px;
                margin-top: 25px;
            }

            .main-nav a {
                font-size: 12px;
            }

            .hero {
                grid-template-columns: 1fr;
                gap: 35px;
                margin: 30px auto 60px;
                padding: 0 8%;
            }

            .hero-text h2 {
                font-size: 42px;
            }

        }

    </style>
</head>

<body>

    <!-- Header and navigation -->

    <header>

        <div class="site-name">

            <h1>
                <a href="index.html">ASHLEY CHUN</a>
            </h1>

            <p>COUNSELOR EDUCATION</p>

        </div>

        <nav class="main-nav">

            <a href="cv.html">CV</a>

            <a href="research.html">
                Research and Scholarship
            </a>

            <a href="teaching.html">Teaching</a>

            <a href="counseling.html">Counseling</a>

            <a href="supervision.html">Supervision</a>

            <a href="leadership.html">
                Leadership and Advocacy
            </a>

        </nav>

    </header>


    <!-- Main homepage -->

    <main>

        <section class="hero">

            <figure class="artwork">

                <img
                    src="cover.jpg"
                    alt="Open Window, Collioure by Henri Matisse"
                >

                <figcaption class="art-credit">
                    Henri Matisse,
                    <i>Open Window, Collioure</i> (1905).
                    National Gallery of Art.
                </figcaption>

            </figure>

            <div class="hero-text">

                <span class="intro-label">
                    WELCOME TO MY PORTFOLIO
                </span>

                <h2>
                    Counselor.<br>
                    Educator.<br>
                    Researcher.
                </h2>

                <p>
                    I am a doctoral student in Counselor
                    Education at the University of Florida.
                </p>

                <p>
                    My professional interests include
                    school counseling, counselor education,
                    and student development.
                </p>

            </div>

        </section>

    </main>


    <!-- Footer -->

    <footer>

        <p>ASHLEY CHUN</p>

        <p>
            Counselor Education | University of Florida
        </p>

        <p>&copy; 2026 Ashley Chun</p>

    </footer>

</body>
</html>
