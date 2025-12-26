<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Students</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Students</h1>
        <p>Talabalar uchun eng kerakli ma’lumotlar</p>
        <button id="themeToggle">Tungi rejim</button>
    </header>

    <nav>
        <a href="#" class="tab-link" data-target="home">Bosh sahifa</a>
        <a href="#" class="tab-link" data-target="guides">Qo‘llanmalar</a>
        <a href="#" class="tab-link" data-target="suggestions">Takliflar</a>
        <a href="#" class="tab-link" data-target="library">Adabiyotlar</a>
    </nav>

    <section id="home" class="tab-content">
        <h2>Bosh sahifa</h2>
        <p>Salom! Bu yerda talabalar uchun eng kerakli ma’lumotlar jamlangan.</p>
    </section>

    <section id="guides" class="tab-content">
        <h2>Qo‘llanmalar</h2>
        <div class="card-container">
            <div class="card">
                <h3>Matematika qo‘llanmasi</h3>
                <a href="files/matematika.pdf" download>Yuklab olish</a>
            </div>
            <div class="card">
                <h3>Fizika qo‘llanmasi</h3>
                <a href="files/fizika.pdf" download>Yuklab olish</a>
            </div>
            <div class="card">
                <h3>Kimyo qo‘llanmasi</h3>
                <a href="files/kimyo.pdf" download>Yuklab olish</a>
            </div>
        </div>
    </section>

    <section id="suggestions" class="tab-content">
        <h2>Takliflar</h2>
        <form id="suggestionForm">
            <input type="text" id="name" placeholder="Ismingiz" required><br><br>
            <textarea id="suggestion" placeholder="Taklifingiz..." required></textarea><br><br>
            <button type="submit">Yuborish</button>
        </form>
        <h3>Yuborilgan takliflar:</h3>
        <ul id="suggestionList"></ul>
    </section>

    <section id="library" class="tab-content">
        <h2>Adabiyotlar</h2>
        <div class="card-container">
            <div class="card">
                <h3>Kitob 1</h3>
                <a href="files/kitob1.pdf" download>Yuklab olish</a>
            </div>
            <div class="card">
                <h3>Maqola 1</h3>
                <a href="files/maqola1.pdf" download>Yuklab olish</a>
            </div>
            <div class="card">
                <h3>Online resurs</h3>
                <a href="files/online_resurs.html" target="_blank">Ko‘rish</a>
            </div>
        </div>
    </section>

    <footer>
        &copy; 2025 Students. Barcha huquqlar himoyalangan.
    </footer>

    <script src="script.js"></script>
</body>
</html>
