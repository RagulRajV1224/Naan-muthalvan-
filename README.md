# Naan-muthalvan-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmetics Store</title>
    <style>
        /* Reset some default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            line-height: 1.6;
        }

        header {
            background-color: #ffcccb;
            padding: 20px 0;
            text-align: center;
        }

        h1 {
            font-size: 36px;
            color: #e74c3c;
        }

        nav {
            background-color: #e74c3c;
            color: #fff;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            text-align: center;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
        }

        .product {
            border: 1px solid #ddd;
            margin: 10px;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #e74c3c;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cosmetics Store</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Products</a></li>
            <li><a href="#">Brands</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h2>Product 1</h2>
            <p>Description of Product 1.</p>
            <p>Price: $XX.XX</p>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h2>Product 2</h2>
            <p>Description of Product 2.</p>
            <p>Price: $XX.XX</p>
        </div>
        <!-- Add more products here -->
    </div>
    <footer>
        &copy; 2023 Cosmetics Store
    </footer>
</body>
</html>
