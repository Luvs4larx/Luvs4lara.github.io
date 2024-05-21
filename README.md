<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laras Welt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffe4e1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffb6c1;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
        }
        header::after {
            content: "";
            display: block;
            width: 100px;
            height: 100px;
            background-image: url('https://img.icons8.com/emoji/96/bow-emoji.png');
            background-size: contain;
            background-repeat: no-repeat;
            position: absolute;
            top: 20px;
            right: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff69b4;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #ffb6c1;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .games {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .game {
            background-color: white;
            border: 2px solid #ff69b4;
            border-radius: 10px;
            padding: 20px;
            width: 200px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .game a {
            color: #ff69b4;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen in Laras Welt</h1>
    </header>
    <nav>
        <a href="#about">Über mich</a>
        <a href="#games">Spiele</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <main>
        <section id="about">
            <h2>Über mich</h2>
            <p>Hallo! Ich heiße Lara und bin Schülerin. Ich interessiere mich sehr für verschiedene Kulturen und Sprachen. In meiner Freizeit häkle ich gerne und backe leckere Sachen. Hier auf meiner Webseite könnt ihr Spaß haben und verschiedene Spiele spielen. Viel Spaß!</p>
        </section>
        <section id="games">
            <h2>Spiele</h2>
            <div class="games">
                <div class="game">
                    <h3>Puzzle-Spiel</h3>
                    <p>Setze die Puzzleteile zusammen und entdecke das Bild!</p>
                    <a href="#">Spielen</a>
                </div>
                <div class="game">
                    <h3>Memory-Spiel</h3>
                    <p>Finde die passenden Paare in diesem Memory-Spiel.</p>
                    <a href="#">Spielen</a>
                </div>
                <div class="game">
                    <h3>Quiz-Spiel</h3>
                    <p>Teste dein Wissen in verschiedenen Kategorien!</p>
                    <a href="#">Spielen</a>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Du kannst mich über <a href="mailto:lara@example.com">lara@example.com</a> erreichen.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Laras Welt</p>
    </footer>
</body>
</html>
