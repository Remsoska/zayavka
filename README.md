<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style/style.css">
</head>
<body>
    <header class="AuthRegistr">
        <h1>"Я буду кушац"</h1> 
    </header>
    <main class="forms">
        <form action="registr.php" method="POST">
            <input type="text" placeholder="Введите телефон" required>
            <input type="number" placeholder="Количество гостей" min="1" max="10"> 
            <input type="date" placeholder="Введи дата" required>
            <input type="time" placeholder="Введи время" required>
            <input type="submit" value="Отправить"/> <br>
            <a href="index.html">На главную</a>
        </form>
    </main>
    <footer>
        "Я буду кушац" 2025. Сделал сайт Баянов Артём 
    </footer>
</body>
</html>
