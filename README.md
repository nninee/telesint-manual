<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Анализ Telegram аккаунтов</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1, h2 {
            color: #2c3e50;
        }
        h1 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            margin-top: 25px;
            color: #2980b9;
        }
        p {
            margin-bottom: 15px;
        }
        .highlight {
            background-color: #fffde7;
            padding: 2px 5px;
            border-radius: 3px;
            font-weight: bold;
        }
        .tip {
            background-color: #e3f2fd;
            padding: 10px 15px;
            border-left: 4px solid #2196f3;
            margin: 20px 0;
            border-radius: 0 3px 3px 0;
        }
        .important {
            background-color: #ffebee;
            padding: 10px 15px;
            border-left: 4px solid #f44336;
            margin: 20px 0;
            border-radius: 0 3px 3px 0;
            font-weight: bold;
        }
        .code {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f5f5f5;
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>Анализ Telegram аккаунтов</h1>
    
    <h2>Определение UserID</h2>
    <p>Сперва, нам нужно понять какой у Telegram аккаунта айди. Это нужно для определения примерной даты создания профиля и последующей разведки.</p>
    
    <p>Для поиска айди лучше всего скачать моды на Telegram по типу:</p>
    <ul>
        <li><span class="highlight">AyuGram</span>, <span class="highlight">Ime</span> – на ПК</li>
        <li><span class="highlight">NiceGram</span> или <span class="highlight">SwiftGram</span> – на iPhone</li>
        <li><span class="highlight">NekoGram</span> – на Android</li>
    </ul>
    
    <p>Если вы боитесь скачивать что-либо и желаете все сделать внутри Telegram, то зайдите в бота <span class="code">@usinfobot</span>, перешлите туда сообщение от пользователя или его <span class="code">@username</span>.</p>
    
    <div class="tip">
        <p>Итак, перейдем к анализу UserID. В том же боте вам выдаст имя, фамилию, айди и примерную дату создания аккаунта. Если аккаунту меньше полутора лет – 70% того, что этот аккаунт зарегистрирован на ненастоящий номер юзера, сидящего на нем.</p>
    </div>
    
    <h2>Поиск чатов аккаунта</h2>
    <p>Лучший бот для этого – <span class="highlight">Фанстат</span>. Так как его много кто использует, вам достаточно просто написать в поиске <span class="code">FunStat</span> и использовать любое зеркало.</p>
    
    <p>В данном боте вы можете узнать очень много полезной информации об аккаунте, например:</p>
    <ul>
        <li>Прошлые юзернеймы</li>
        <li>Чаты</li>
        <li>Сообщения в чатах</li>
        <li>Имена и другое</li>
    </ul>
    
    <p><span class="highlight">Telesint bot</span> – хороший инструмент для поиска чатов аккаунта. На старте дается три бесплатных поиска.</p>
    
    <h2>Поиск старых профилей</h2>
    <p>И теперь <span class="highlight">САМОЕ НУЖНОЕ И ИНТЕРЕСНОЕ</span>, как же найти старые профили человека в сети. Для этого нам нужно зайти в бота <span class="highlight">Фанстат</span> или <span class="highlight">Unamer</span>. И по отдельности искать информацию по каждому юзернейму или имени (не путать). Если человек ранее использовал какие-то из них, вы сразу это заметите.</p>
    
    <div class="tip">
        <p>Совет: чтобы искать пользователя по имени аккаунта в Фанстат – нужно написать команду <span class="code">люди имя</span> (писать без кавычек).</p>
    </div>
    
    <div class="important">
        <p>Так же настоятельно рекомендую проверять каждое имя и юзернейм через инструменты <span class="highlight">Maigret</span> или <span class="highlight">Sherlock</span>. <span class="highlight">ОБЯЗАТЕЛЬНО</span> используйте dork <span class="code">intext:</span> для работы.</p>
    </div>
    
    <p>Скорее всего вы найдете профили человека в других социальных сетях, что значительно облегчит работу.</p>
</body>
</html>
