## Hi there 👋
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Выдвигающийся текст</title>
    <style>
        .container {
            overflow: hidden; /* Скрывает текст за пределами контейнера */
            width: 200px; /* Ширина контейнера */
            border: 1px solid #ccc; /* Граница контейнера */
        }

        .text {
            transform: translateX(-100%); /* Начальная позиция текста */
            animation: slideIn 1s forwards; /* Запуск анимации */
        }

        @keyframes slideIn {
            to {
                transform: translateX(0); /* Конечная позиция текста */
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="text">Это выдвигающийся текст!</div>
</div>

</body>
</html>
<!--
**Kiselyaka/Kiselyaka** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
