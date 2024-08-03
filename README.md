<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Food</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #ff4500;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .food-item {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin-bottom: 20px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .food-item img {
            width: 100%;
            height: auto;
        }
        .food-item h2 {
            padding: 15px;
            margin: 0;
        }
        .food-item p {
            padding: 0 15px 15px;
            margin: 0;
        }
        footer {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Delicious Food</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div class="food-item">
            <img src="https://via.placeholder.com/800x400" alt="Food Image">
            <h2>Food Item 1</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum.</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/800x400" alt="Food Image">
            <h2>Food Item 2</h2>
            <p>Cras ultricies ligula sed magna dictum porta. Proin eget tortor risus.</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/800x400" alt="Food Image">
            <h2>Food Item 3</h2>
            <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus. Nulla quis lorem ut libero malesuada feugiat.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Delicious Food. All rights reserved.</p>
    </footer>
</body>
</html>
