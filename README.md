# Te-ador-piticotu-meuuuuuuuuu
Multumesc ca faci parte din viata meaaa, te ador pingu meu perfeeectttt
Cu drag, nebunu' tău
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Te iubesc</title>
    <style>
        body {
            background-color: #ffc0cb; /* fundal roz intens */
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            overflow: hidden;
        }

        h1 {
            color: #d63384;
            font-size: 3em;
            margin-bottom: 60px;
            max-width: 90%;
        }

        .hearts {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            max-width: 800px;
        }

        .heart {
            width: 60px;
            height: 60px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            animation: pulse 1.2s infinite ease-in-out;
        }

        .heart::before,
        .heart::after {
            content: "";
            width: 60px;
            height: 60px;
            background-color: red;
            border-radius: 50%;
            position: absolute;
        }

        .heart::before {
            top: -30px;
            left: 0;
        }

        .heart::after {
            left: 30px;
            top: 0;
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1) rotate(-45deg);
            }
            50% {
                transform: scale(1.3) rotate(-45deg);
            }
        }
    </style>
</head>
<body>

    <h1>Te iubesc și te ador, piticotu’ meu 💖</h1>

    <div class="hearts">
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
    </div>

</body>
</html>
