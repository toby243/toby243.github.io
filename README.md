<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>王学峰艺术设计职称介绍</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', 'Helvetica Neue', sans-serif;
            background: linear-gradient(135deg, #2c3e50, #bdc3c7);
            color: #fff;
            transition: background 0.8s ease;
        }

     
        .color-switcher {
            position: fixed;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(8px);
            padding: 8px 15px;
            border-radius: 25px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
            display: flex;
            gap: 8px;
            z-index: 1000;
        }

        .color-btn {
            width: 20px;
            height: 20px;
            border-radius: 50%;
            border: none;
            cursor: pointer;
            outline: none;
        }


        .title-section {
            text-align: center;
            padding: 100px 20px 50px;
            background: rgba(255, 255, 255, 0.08);
            border-radius: 15px;
            max-width: 900px;
            margin: 100px auto;
            backdrop-filter: blur(8px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        .english-title {
            font-size: 28px;
            letter-spacing: 3px;
            font-weight: 300;
            color: #f8f8f8;
        }

        .chinese-title {
            font-size: 36px;
            font-family: "STSong", "SimSun", serif;
            font-weight: bold;
            margin-top: 15px;
            color: #fff;
        }

        .divider {
            margin: 25px auto 0;
            width: 60px;
            height: 2px;
            background-color: #ddd;
        }
    </style>
</head>
<body>
、
    <div class="color-switcher">
        <button class="color-btn" style="background: linear-gradient(135deg, #283c86, #45a247)" onclick="changeBackground('#283c86', '#45a247')"></button>
        <button class="color-btn" style="background: linear-gradient(135deg, #b993d6, #8ca6db)" onclick="changeBackground('#b993d6', '#8ca6db')"></button>
        <button class="color-btn" style="background: linear-gradient(135deg, #d7d2cc, #304352)" onclick="changeBackground('#d7d2cc', '#304352')"></button>
        <button class="color-btn" style="background: linear-gradient(135deg, #0f2027, #2c5364)" onclick="changeBackground('#0f2027', '#2c5364')"></button>
        <button class="color-btn" style="background: linear-gradient(135deg, #ff9a9e, #fad0c4)" onclick="changeBackground('#ff9a9e', '#fad0c4')"></button>
    </div>

    <div class="title-section">
        <div class="english-title">Xuefeng Wang · Academic & Artistic Journey</div>
        <div class="chinese-title">用设计诠释世界：王学峰的艺术历程</div>
        <div class="divider"></div>
    </div>

    <script>
        function changeBackground(color1, color2) {
            document.body.style.background = `linear-gradient(135deg, ${color1}, ${color2})`;
        }
    </script>

</body>
</html>

