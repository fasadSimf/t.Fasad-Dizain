<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фасад-дизайн</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #fff;
            color: #9d794d;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-top: 5px solid #9d794d;
            border-bottom: 5px solid #9d794d;
        }
        header .content {
            display: flex;
            align-items: center;
            width: 1200px;
        }
        header .logo {
            flex: 0 0 auto;
            margin-right: 30px;
        }
        header .logo img {
            width: 202px;
        }
        header .text {
            flex: 1;
            text-align: left;
            color: #9d794d;
        }
        header .text h1 {
            margin: 0;
            font-size: 24px;
        }
        header .text p {
            margin: 0;
            font-size: 16px;
            color: #9d794d;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #9d794d;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background: #9d794d;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            text-align: center;
            font-weight: bold;
        }
        .button:hover {
            background: #7e6238;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #9d794d;
            color: #fff;
            margin-top: 20px;
        }
        #contact-messenger ul {
            list-style: none;
            padding: 0;
        }
        #contact-messenger li {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="content">
            <div class="logo">
                <img src="лого.png" alt="Логотип Фасад-дизайн">
            </div>
            <div class="text">
                <h1>Фасад-дизайн</h1>
                <p>Информация о заказах и стоимость продукции</p>
            </div>
        </div>
    </header>
    <nav>
        <a href="#auth">Главная</a>
        <a href="#orders">Мои заказы</a>
        <a href="#calculator">Калькулятор стоимости</a>
        <a href="#contacts">Контакты</a>
    </nav>
    <div class="container" id="auth">
        <h2>Авторизация</h2>
        <p>Введите номер телефона для входа:</p>
        <form>
            <label for="phone">Номер телефона:</label><br>
            <input type="text" id="phone" name="phone" placeholder="+7 (___) ___-__-__" required><br><br>
            <button type="submit" class="button">Войти</button>
        </form>
    </div>
    <div class="container" id="orders">
        <h2>Мои заказы</h2>
        <p>Информация о текущих заказах будет отображаться здесь после авторизации.</p>
    </div>
    <div class="container" id="calculator">
        <h2>Калькулятор стоимости</h2>
        <p>Введите параметры продукции для расчета:</p>
        <form>
            <label for="material">Материал:</label><br>
            <select id="material" name="material">
                <option value="mdf">МДФ</option>
                <option value="hpl">HPL</option>
            </select><br><br>
            <label for="dimensions">Размеры (см):</label><br>
            <input type="text" id="dimensions" name="dimensions" placeholder="100x50" required><br><br>
            <button type="submit" class="button">Рассчитать</button>
        </form>
    </div>
    <div class="container" id="contacts">
        <h2>Контакты</h2>
        <p><strong>г. Симферополь, ул. Коммунальная, 53</strong></p>
        <ul>
            <li><a href="https://t.me/+79784643268" target="_blank" class="button">+7 (978) 464-32-68</a></li>
            <li><a href="https://t.me/+79787822268" target="_blank" class="button">+7 (978) 782-22-68</a></li>
            <li><a href="https://t.me/+79788369968" target="_blank" class="button">+7 (978) 836-99-68</a></li>
        </ul>
        <p><strong>г. Краснодар, ул. Новороссийская, 172</strong></p>
        <ul>
            <li><a href="https://t.me/+79182324454" target="_blank" class="button">+7 (918) 232-44-54</a></li>
            <li><a href="https://t.me/+79182324033" target="_blank" class="button">+7 (918) 232-40-33</a></li>
        </ul>
    </div>
    <footer>
        
<p>
    Контакты: <a href="mailto:simf@fasad-dizain.ru">simf@fasad-dizain.ru</a> | 
    <a href="https://shop.fasad-dizain.ru/" target="_blank">Сайт фурнитуры</a> | 
    <a href="https://fasad-dizain.ru/" target="_blank">Сайт мебельных фасадов</a> <br>
    
    г. Симферополь: +7 (978) 464-32-68, +7 (978) 782-22-68, +7 (978) 836-99-68<br>
    г. Краснодар: +7 (918) 232-44-54, +7 (918) 232-40-33
</p>

    </footer>
</body>
</html>
