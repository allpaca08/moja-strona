<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BikeZone - Twój świat rowerów</title>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    color: #222;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

header {
    background: #172b24;
    color: white;
    padding: 20px 0;
}

.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 18px;
}

nav a:hover {
    color: #8be28b;
}

.hero {
    background: linear-gradient(135deg, #214b37, #78a96b);
    color: white;
    text-align: center;
    padding: 110px 20px;
}

.hero h2 {
    font-size: 42px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background: #75c76b;
    color: #14261b;
    padding: 12px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
}

.btn:hover {
    background: #9be28f;
}

.oferta {
    padding-top: 65px;
    padding-bottom: 70px;
    text-align: center;
}

.oferta h2,
.onas h2,
.kontakt h2 {
    font-size: 30px;
    margin-bottom: 25px;
}

.produkty {
    display: flex;
    gap: 25px;
    margin-top: 35px;
}

.karta {
    flex: 1;
    padding: 30px 20px;
    background: #f4f7f4;
    border-radius: 10px;
    border-bottom: 4px solid #75c76b;
    transition: transform 0.3s;
}

.karta:hover {
    transform: translateY(-5px);
}

.ikona {
    font-size: 45px;
    margin-bottom: 15px;
}

.karta h3 {
    margin-bottom: 10px;
}

.onas {
    background: #edf3ed;
    text-align: center;
    padding: 65px 20px;
}

.onas p {
    max-width: 700px;
    margin: auto;
}

.kontakt {
    text-align: center;
    padding-top: 65px;
    padding-bottom: 70px;
}

footer {
    background: #172b24;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Wygląd na telefonach */
@media (max-width: 700px) {
    .nav {
        flex-direction: column;
    }

    nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 12px;
    }

    nav a {
        margin-left: 0;
    }

    .hero h2 {
        font-size: 32px;
    }

    .produkty {
        flex-direction: column;
    }
}
    </style>
</head>
<body>

    <header>
        <div class="container nav">
            <h1>🚲 BikeZone</h1>
            <nav>
                <a href="#home">Strona główna</a>
                <a href="#oferta">Oferta</a>
                <a href="#onas">O nas</a>
                <a href="#kontakt">Kontakt</a>
            </nav>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="container">
            <h2>Znajdź swój idealny rower</h2>
            <p>Sprzedaż rowerów, akcesoria i profesjonalny serwis.</p>
            <a href="#oferta" class="btn">Zobacz ofertę</a>
        </div>
    </section>

    <section class="oferta container" id="oferta">
        <h2>Nasza oferta</h2>

        <div class="produkty">
            <div class="karta">
                <div class="ikona">🚵</div>
                <h3>Rowery górskie</h3>
                <p>Idealne na leśne ścieżki i trudne trasy.</p>
            </div>

            <div class="karta">
                <div class="ikona">🚴</div>
                <h3>Rowery miejskie</h3>
                <p>Wygodna jazda na co dzień i do pracy.</p>
            </div>

            <div class="karta">
                <div class="ikona">🔧</div>
                <h3>Serwis rowerowy</h3>
                <p>Naprawy, przeglądy i profesjonalna obsługa.</p>
            </div>
        </div>
    </section>

    <section class="onas" id="onas">
        <div class="container">
            <h2>O naszej firmie</h2>
            <p>
                BikeZone to miejsce dla wszystkich miłośników rowerów.
                Pomagamy wybrać odpowiedni sprzęt, oferujemy akcesoria
                oraz dbamy o to, aby każdy rower był zawsze gotowy do jazdy.
            </p>
        </div>
    </section>

    <section class="kontakt container" id="kontakt">
        <h2>Skontaktuj się z nami</h2>
        <p>Masz pytania? Chętnie pomożemy!</p>
        <p><strong>E-mail:</strong> kontakt@bikezone.pl</p>
        <p><strong>Telefon:</strong> 123 456 789</p>
        <p><strong>Adres:</strong> ul. Rowerowa 10, Warszawa</p>
        <a href="mailto:kontakt@bikezone.pl" class="btn">Napisz do nas</a>
    </section>

    <footer>
        <p>&copy; 2026 BikeZone. Wszelkie prawa zastrzeżone.</p>
    </footer>

</body>
</html>
