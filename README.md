# NguynnGitMoi 
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="Năm <title>Chúc Mừng Năm Mới Mọi margin/title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #d00000, #ffcc70);
            font-family: "Segoe UI", sans-serif;
        }
        .card {
            background: #fff8e7;
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }
        h1 {
            color: #d00000;
            font-size: 32px;
        }
        p {
            font-size: 18px;
            color: #333;
            line-height: 1.6;
        }
        button {
            margin-top: 20px;
            padding: 12px 25px;
            border: none;
            border-radius: 30px;
            background: #d00000;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background: #a80000;
        }
        .emoji {
            font-size: 40px;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="emoji">🌸🧧🎉</div>
        <h1>Chúc Mừng Năm Mới</h1>
        <p>
            Chúc bạn năm mới<br>
            <b>An Khang – Thịnh Vượng – Vạn Sự Như Ý</b><br>
            Tiền vô như nước, nụ cười luôn trên môi 😄
        </p>
        <button onclick="liXi()">Nhận lì xì 💰</button>
    </div>

    <script>
        function liXi() {
            const wishes = [
                "🧧 Lì xì sức khỏe dồi dào!",
                "🎉 Lì xì thành công rực rỡ!",
                "💰 Lì xì tiền vô ào ào!",
                "🌸 Lì xì bình an cả năm!"
            ];
            const randomWish = wishes[Math.floor(Math.random() * wishes.length)];
            alert(randomWish);
        }
    </script>
</body>
</html>
