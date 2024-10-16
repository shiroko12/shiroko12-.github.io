<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="這是一個簡單的圖片展示網站範例。">
    <title>圖片展示網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: #333;
            padding: 14px 20px;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }
        nav a:hover {
            color: #555;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- 頁首區塊 -->
    <header>
        <h1>歡迎來到圖片展示網站</h1>
        <p>這裡可以展示各式圖片</p>
    </header>

    <!-- 導航欄 -->
    <nav>
        <a href="#gallery">圖片展示</a>
        <a href="#about">關於我們</a>
        <a href="#contact">聯絡我們</a>
    </nav>

    <!-- 圖片展示區域 -->
    <section id="gallery">
        <h2>圖片展示</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300" alt="https://i.imgur.com/QK22lhB.jpeg">
            <img src="https://via.placeholder.com/300" alt="圖片2">
            <img src="https://via.placeholder.com/300" alt="圖片3">
            <img src="https://via.placeholder.com/300" alt="圖片4">
            <img src="https://via.placeholder.com/300" alt="圖片5">
        </div>
    </section>

    <!-- 關於我們區域 -->
    <section id="about">
        <h2>關於我們</h2>
        <p>我們專注於創造優質的圖片展示網站，讓每一張照片都能被完美展示。</p>
    </section>

    <!-- 聯絡我們區域 -->
    <section id="contact">
        <h2>聯絡我們</h2>
        <p>如有任何問題，請隨時透過電子郵件與我們聯絡：info@example.com</p>
    </section>

    <!-- 頁尾區塊 -->
    <footer>
        <p>&copy; 2024 圖片展示網站 | 版權所有</p>
    </footer>

</body>
</html>
