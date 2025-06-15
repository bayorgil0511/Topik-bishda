# Topik-bishda
<!DOCTYPE html>
<html lang="mn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOPIK 3-5 Бэлтгэл</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>TOPIK 3-5 Шалгалтын Бэлтгэл</h1>
        <nav>
            <ul>
                <li><a href="#home">Нүүр хуудас</a></li>
                <li><a href="#vocab">Үгс ба Дүрэм</a></li>
                <li><a href="#practice">Дасгал</a></li>
                <li><a href="#test">Шалгалт</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>TOPIK Шалгалт</h2>
        <p>TOPIK 3, 4, 5 түвшний бэлтгэлийн сайт руу тавтай морилно уу. Бид танд хэрэгтэй бүх хичээлүүдийг бэлдсэн!</p>
    </section>

    <section id="vocab">
        <h2>Үгс ба Дүрэм</h2>
        <ul>
            <li><a href="#">TOPIK 3-ийн үгс</a></li>
            <li><a href="#">TOPIK 4-ийн үгс</a></li>
            <li><a href="#">TOPIK 5-ийн үгс</a></li>
        </ul>
    </section>

    <section id="practice">
    
        <h2>Дасгал</h2>
        <p>Дасгал хийх хэсэг энд байна...</p>
    </section>

    <section id="test">
        <h2>Шалгалт</h2>
        <p>Өнгөрсөн TOPIK шалгалтын бодлогууд...</p>
    </section>

    <footer>
        <p>© 2025 TOPIK Бэлтгэл</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
}
document.addEventListener("DOMContentLoaded", function() {
    const vocabLinks = document.querySelectorAll('#vocab a');
    vocabLinks.forEach(function(link) {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            alert('Энэ хэсэг нь TOPIK 3, 4, 5-ийн үгсийг агуулна!');
        });
    });

    const testLinks = document.querySelectorAll('#test a');
    testLinks.forEach(function(link) {
        link.addEventListener('click', function(e) {
            e.preventDefault();
            alert('Шалгалтын бодлогын хэсэг');
        });
    });
});
