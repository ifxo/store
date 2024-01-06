<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resin Jewelry Shop</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 15px;
            padding: 20px;
            width: 300px;
            transition: transform 0.3s ease-in-out;
        }

        .product-card:hover {
            transform: scale(1.05);
        }

        .product-image {
            max-width: 100%;
            border-radius: 8px;
        }

        h2 {
            color: #333;
        }

        p {
            color: #666;
        }

        button {
            background-color: #333;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out;
        }

        button:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .contact-info {
            text-align: center;
            margin-top: 30px;
        }

        .contact-info p {
            margin: 5px;
        }

        .featured-product {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 30px;
            padding: 20px;
            background-color: #333;
            color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .featured-product img {
            max-width: 100%;
            border-radius: 8px;
        }

        .featured-product-info {
            max-width: 50%;
            padding: 20px;
        }

        .featured-product-info h2 {
            font-size: 24px;
        }

        .new-products,
        .old-products {
            text-align: center;
            margin: 30px;
        }

        .new-products img,
        .old-products img {
            max-width: 100%;
            border-radius: 8px;
            margin: 10px;
            transition: transform 0.3s ease-in-out;
        }

        .new-products img:hover,
        .old-products img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <header>
        <h1>Resin Jewelry Shop</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#new-products">New Products</a>
        <a href="#old-products">Old Products</a>
        <!-- Add more links as needed -->
    </nav>

    <div class="featured-product">
        <img src="featured_product_image.jpg" alt="Featured Product">
        <div class="featured-product-info">
            <h2>Featured Product</h2>
            <p>Description of the featured product goes here.</p>
            <p>Price: $XX.XX</p>
            <button>Add to Cart</button>
        </div>
    </div>

    <div class="new-products">
        <h2>New Products</h2>
        <div class="product-container">
            <!-- New Products -->
            <div class="product-card">
                <img class="product-image" src="new_product_1.jpg" alt="New Product 1">
                <h2>New Product 1</h2>
                <p>Description of new product 1 goes here.</p>
                <p>Price: $XX.XX</p>
                <button>Add to Cart</button>
            </div>

            <div class="product-card">
                <img class="product-image" src="new_product_2.jpg" alt="New Product 2">
                <h2>New Product 2</h2>
                <p>Description of new product 2 goes here.</p>
                <p>Price: $XX.XX</p>
                <button>Add to Cart</button>
            </div>

            <!-- Add more new product cards as needed -->

        </div>
    </div>

    <div class="old-products">
        <h2>Old Products</h2>
        <div class="product-container">
            <!-- Old Products -->
            <div class="product-card">
                <img class="product-image" src="old_product_1.jpg" alt="Old Product 1">
                <h2>Old Product 1</h2>
                <p>Description of old product 1 goes here.</p>
                <p>Price: $XX.XX</p>
                <button>Add to Cart</button>
            </div>

            <div class="product-card">
                <img class="product-image" src="old_product_2.jpg" alt="Old Product 2">
                <h2>Old Product 2</h2>
                <p>Description of old product 2 goes here.</p>
                <p>Price: $XX.XX</p>
                <button>Add to Cart</button>
            </div>

            <!-- Add more old product cards as needed -->

        </div>
    </div>

    <footer>
        <div class="contact-info">
            <h2>Contact Us</h2>
            <p>Email: info@resinjewelry.ae</p>
            <p>Phone: +1 (555) 123-4567</p>
            <p>Follow us on Instagram: @resinjewelry</p>
        </div>
    </footer>

</body>
</html>
