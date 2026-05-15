# ViceProduction
ViceProduction Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vice | Producer • Songwriter • Vocalist</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0d0d0d;
            color: white;
        }

        header {
            background: url('YOUR-BANNER-IMAGE.jpg') center/cover no-repeat;
            height: 55vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        header h1 {
            font-size: 3.5rem;
            letter-spacing: 4px;
            text-shadow: 0 0 20px black;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        p {
            line-height: 1.7;
            font-size: 1.1rem;
            color: #dcdcdc;
        }

        .beats iframe {
            width: 100%;
            height: 160px;
            border: none;
            margin-bottom: 25px;
            border-radius: 6px;
        }

        .links a {
            display: inline-block;
            margin: 10px;
            padding: 12px 22px;
            border: 1px solid #ffffff40;
            border-radius: 6px;
            color: white;
            text-decoration: none;
            transition: 0.2s;
        }

        .links a:hover {
            background-color: white;
            color: black;
        }

        footer {
            text-align: center;
            padding: 30px;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>VICE</h1>
    </header>

    <!-- ABOUT -->
    <section id="about">
        <h2>ABOUT</h2>
        <p>
            Vice is a producer and artist from Pittsburgh whose connection to music runs deep. Since he was young, 
            music has been the thing that grounded him, pushed him forward, and helped him through the moments most 
            people never see. What stood out early on wasn’t just the songs themselves, but the way he locked onto 
            the production behind them — the drums, the textures, the tiny details most people miss. He’d break down 
            beats in his head, rebuild them, and study them without even realizing he was teaching himself how to create.
            <br><br>
            That natural hyperfocus turned into a passion for making his own sound. Vice isn’t trying to be anything 
            other than who he is — a regular guy who loves music and is chasing something real. His goal is simple: 
            make beats that hit, build a name for himself, and create something that lasts.
        </p>
    </section>

    <!-- BEATS -->
    <section id="beats" class="beats">
        <h2>BEATS</h2>

        <!-- Replace these with your real embeds -->
        <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
    </section>

    <!-- LINKS -->
    <section id="links">
        <h2>LINKS</h2>
        <div class="links">
            <a href="#">YouTube</a>
            <a href="#">Instagram</a>
            <a href="#">TikTok</a>
            <a href="#">SoundCloud</a>
            <a href="#">BeatStars</a>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
        <h2>CONTACT</h2>
        <p>Email: <strong>your-email@example.com</strong></p>
    </section>

    <footer>
        © 2026 Vice — Pittsburgh, PA
    </footer>

</body>
</html>
