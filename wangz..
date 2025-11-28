<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Confess ❤️</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            background-color: #ffbddb;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        #text {
            font-size: 25px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        button {
            padding: 12px 20px;
            margin: 10px;
            border: none;
            background-color: #ff4f8b;
            color: white;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.1);
        }

        #btnEngga {
            position: relative;
        }
    </style>
</head>
<body>

    <div id="text">📌 WAJIB DI BACA!!</div>
    <button id="startBtn">💌 KLIK INI UNTUK LIHAT 📩</button>

    <div id="choiceButtons" style="display:none;">
        <button id="btnMau">💗 MAU 💗</button>
        <button id="btnEngga">🚫 ENGGA</button>
    </div>

<script>
    const textElement = document.getElementById("text");
    const startBtn = document.getElementById("startBtn");
    const btnMau = document.getElementById("btnMau");
    const btnEngga = document.getElementById("btnEngga");
    const choiceButtons = document.getElementById("choiceButtons");

    function typeEffect(text, speed = 80) {
        let index = 0;
        textElement.innerHTML = "";
        const interval = setInterval(() => {
            textElement.innerHTML += text[index];
            index++;
            if (index === text.length) clearInterval(interval);
        }, speed);
    }

    startBtn.addEventListener("click", () => {
        startBtn.style.display = "none";
        typeEffect("I HAVE CRUSH ON YOU ❤️");

        setTimeout(() => {
            textElement.innerHTML = "";
            typeEffect("MAU GA JADI PACAR KU? 💞");
            choiceButtons.style.display = "block";
        }, 3000);
    });

    btnMau.addEventListener("click", () => {
        choiceButtons.style.display = "none";
        typeEffect("YEAY!! SEKARANG KITA RESMI PACARAN YA 💘😍");
    });

    btnEngga.addEventListener("mouseover", () => {
        const x = Math.random() * 200 - 100;
        const y = Math.random() * 200 - 100;
        btnEngga.style.transform = `translate(${x}px, ${y}px)`;
        typeEffect("WAJIB MAU!! 😤❤️");
    });
</script>

</body>
</html>
