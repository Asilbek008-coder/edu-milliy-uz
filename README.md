# edu-milliy-uz
Public
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EDU.MILLIY.UZ</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>EDU.MILLIY.UZ</h1>
        <nav>
            <ul>
                <li><a href="#home">Bosh Sahifa</a></li>
                <li><a href="#about">Biz Haqimizda</a></li>
                <li><a href="#contact">Aloqa</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Ta'lim platformasiga xush kelibsiz</h2>
            <p>O'qish va o'rganish uchun eng yaxshi joy!</p>
            <button onclick="alert('Ro‘yxatdan o‘ting va o‘rganishni boshlang!')">Boshlash</button>
        </section>
        <section id="about">
            <h2>Biz haqimizda</h2>
            <p>EDU.MILLIY.UZ — bu o‘quvchilar va o‘qituvchilar uchun yaratilgan ta’lim platformasidir. Bu yerda siz turli darslar va testlardan foydalanishingiz mumkin.</p>
        </section>
        <section id="contact">
            <h2>Aloqa</h2>
            <form id="contactForm">
                <label for="name">Ism:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Xabar:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Jo'natish</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 EDU.MILLIY.UZ. Barcha huquqlar himoyalangan.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #0077cc;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
    text-align: center;
}

section {
    margin-bottom: 40px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
document.getElementById("contactForm").addEventListener("submit", function(e) {
    e.preventDefault(); // Formni jo'natishni to'xtatadi
    alert("Xabaringiz jo'natildi. Rahmat!");
    this.reset(); // Formani tozalash
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edu Milliy</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Edu Milliy</h1>
            <nav>
                <ul>
                    <li><a href="#home">Bosh sahifa</a></li>
                    <li><a href="#about">Biz haqimizda</a></li>
                    <li><a href="#courses">Kurslar</a></li>
                    <li><a href="#contact">Bog'lanish</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <h2>Onlayn Ta'lim Platformasi</h2>
        <p>Eng yaxshi o'quv kurslarini biz bilan boshlang!</p>
    </section>

    <section id="about">
        <h2>Biz haqimizda</h2>
        <p>Edu Milliy – bu o‘quvchilar va o‘qituvchi uchun eng yaxshi ta’lim platformasi.</p>
    </section>

    <section id="courses">
        <h2>Kurslar</h2>
        <div class="course-list">
            <div class="course-item">
                <h3>Dasturlash</h3>
                <p>Python, JavaScript va boshqa tillarni o'rganing.</p>
            </div>
            <div class="course-item">
                <h3>Matematika</h3>
                <p>Matematikaning asosiy va ilg'or mavzularini o'rganing.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Bog'lanish</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Ismingiz" required>
            <input type="email" name="email" placeholder="Email" required>
            <textarea name="message" placeholder="Xabar..." required></textarea>
            <button type="submit">Yuborish</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Edu Milliy. Barcha huquqlar himoyalangan.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #007BFF;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
}

section#home {
    background-color: #F8F9FA;
    text-align: center;
}

section#courses .course-list {
    display: flex;
    gap: 20px;
}

section#courses .course-item {
    border: 1px solid #CCC;
    padding: 10px;
    flex: 1;
    text-align: center;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}
