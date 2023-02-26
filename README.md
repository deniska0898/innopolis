# innopolis<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <title>Сайт группы</title>
    <script async src="./JS/popup.js">
    </script>
</head>
<body class="page">
    <header class="header">
        <img src="img/logo.svg" class="site-logo" alt="site-logo">
        <div class="site-menu">
            <a class="menu-link" href="#">Главная</a>
            <a class="menu-link" href="./pages/students.html">Студенты</a>
            <a class="menu-link" href="./pages/about.html">О курсе</a>
            <a class="menu-link" href="./pages/contact.html">Контакты</a>
        </div>
        <a class="login-button" href="login.html">Войти</a>
        <div class="login-popup">
            <h2 class="login-heading">Войти на сайт</h2>
            <form class="login-form">
                <input class="login-input" name="login" type="text" placeholder="Логин" required>
                <input class="login-password" name="password" type="text" placeholder="Пароль" required>
                <button class="popup-button" type="submit">Войти</button>
            </form>
        </div>
    </header>
    <main class="main">
        <h1 class="main-heading"> Добро пожаловать на курс “Создание веб-сайтов (HTML, CSS)”!</h1>
        <img class="class-photo" src="img/class 2.png" width="523" height="316">
        <h2>Для кого этот курс</h2>
        <p class="intro-text">Этот курс рассчитан на новичков, которые только начинают знакомство 
            с веб-разработкой. В начале курса вы узнаете о том, как устроен 
            Интернет и веб-сайты. 
        Для обучения необходимо только владеть компьютерной грамотностью 
        (пользоваться браузером, создавать папки и файлы, устанавливать программы).</p>
        <h2>Чему вы научитесь</h2>
        <p class="intro-text">На этом курсе вы узнаете, как устроены веб-сайты и как создавать их с 
            нуля. Изучите основы языков <strong>HTML</strong>, <strong>CSS</strong> и немного <strong>JavaScript.</strong> Мы вместе 
            сверстаем сайт нашей группы по этому макету. А затем вы <em>сами</em>
            сверстаете свои личные странички в качестве домашнего задания и мы выложим все это на сервер.</p>    
    </main>
    <footer class="footer">
        <p class="copyright">
        2022 &copy; <a href="" class="innop-link"> учебный центр </a>
    </p>
    </footer>
</body>
</html>
