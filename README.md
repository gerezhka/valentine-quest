# valentine-quest[index.html](https://github.com/user-attachments/files/25286080/index.html)
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Для Тебе ❤️</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden; 
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #fff5f7;
        }
        .scroll-container {
            height: 100vh;
            overflow-y: scroll;
            scroll-snap-type: y mandatory; 
            scroll-behavior: smooth;
        }
        section {
            height: 100vh;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            scroll-snap-align: start;
            padding: 20px;
            box-sizing: border-box;
        }
        h1 { color: #d81b60; font-size: 1.8rem; margin: 10px 0; }
        p { color: #444; font-size: 1rem; line-height: 1.4; max-width: 300px; margin: 10px 0; }
        .quote { font-style: italic; color: #ad1457; border-left: 3px solid #f48fb1; padding-left: 15px; text-align: left; }
        
        .arrow {
            font-size: 24px;
            animation: bounce 2s infinite;
            color: #f48fb1;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
            40% {transform: translateY(-10px);}
            60% {transform: translateY(-5px);}
        }

        .gift-photo {
            max-width: 85%;
            max-height: 45vh;
            object-fit: contain;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin: 10px 0;
        }
    </style>
</head>
<body>

<div class="scroll-container">
    <section>
        <h1>Привіт, Кицюнь! ❤️</h1>
        <p>Я підготував для тебе дещо особливе... Прогорни нижче.</p>
        <div class="arrow">↓</div>
    </section>

    <section style="background-color: #ffebee;">
        <h1>Тільки для тебе</h1>
        <p class="quote">
            "Ти поруч і в душі квітує літо,<br>
             Хоч за вікном сніги чи холоди.<br>
            Ти та людина, що навчила жити,<br>
            Я хочу бути поряд назавжди."
        </p>
        <p>Ти — моє натхнення і мій спокій. Кохаю тебе!</p>
        <div class="arrow">↓</div>
    </section>

    <section>
        <h1>Крок до сюрпризу 😁</h1>
        <p>Наступне фото — це твоя підказка. Спробуй знайти)</p>
        <div class="arrow">↓</div>
    </section>

    <section style="background-color: #fce4ec;">
        <h1>Ти точно знаєш, де це місце ☺️:</h1>
        <img src="https://i.postimg.cc/xTQN5w26/5222011110851023234.jpg" alt="Підказка" class="gift-photo">
        <p style="font-weight: bold; font-size: 0.9rem;">Шукай, там я заховав наступну підказочку! 😉</p>
    </section>
</div>

</body>
</html>
