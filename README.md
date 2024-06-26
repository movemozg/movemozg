<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moja Prosta Strona WWW</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            margin: 20px;
            text-align: center;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }
        main {
            padding: 20px;
        }
        section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Witamy na Mojej Prostej Stronie WWW</h1>
    </header>
    <nav>
        <a href="#about">O mnie</a>
        <a href="#gallery">Galeria</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <main>
        <section id="about">
            <h2>O mnie</h2>
            <p>Cześć! Nazywam się Jan Kowalski i jestem pasjonatem tworzenia stron internetowych. Na tej stronie znajdziesz informacje o mnie oraz moje projekty.</p>
        </section>
        <section id="gallery">
            <h2>Galeria</h2>
            <img src="https://via.placeholder.com/300" alt="Przykładowy obrazek" style="width:100%;max-width:300px;">
            <p>To jest przykładowy obrazek.</p>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Możesz skontaktować się ze mną poprzez email: <a href="mailto:jan.kowalski@example.com">jan.kowalski@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Jan Kowalski</p>
    </footer>
</body>
</html>
