<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(to right, #6a11cb, #2575fc);
            margin: 0;
        }
        .container {
            display: flex;
            gap: 20px;
            padding: 30px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
        }
        .card {
            background: white;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            text-align: center;
            width: 220px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
        .price-date {
            font-size: 26px;
            font-weight: bold;
            margin-bottom: 12px;
            color: #222;
        }
        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
        }
        .logo-container img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            margin-right: 12px;
            border: 3px solid #ddd;
        }
        .logo-container span {
            font-size: 20px;
            font-weight: bold;
            color: #333;
        }
        .button {
            margin-top: 15px;
            padding: 14px 28px;
            background-color: #ff6600;
            color: white;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            text-decoration: none;
            font-size: 18px;
            transition: background 0.3s, transform 0.2s;
        }
        .button:hover {
            background-color: #cc5200;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Company 3 -->
        <div class="card">
            <div class="price-date">$30 / 18 Dec</div>
            <div class="logo-container">
                <img src="https://cdn-icons-png.flaticon.com/128/732/732217.png" alt="Company Logo">
                <span>Company 3</span>
            </div>
            <a href="R13.html" class="button">Start</a>
        </div>
        <!-- Company 4 -->
        <div class="card">
            <div class="price-date">$35 / 20 Dec</div>
            <div class="logo-container">
                <img src="https://cdn-icons-png.flaticon.com/128/732/732228.png" alt="Company Logo">
                <span>Company 4</span>
            </div>
            <a href="R14.html" class="button">Start</a>
        </div>
    </div>
</body>
</html>

