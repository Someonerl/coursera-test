<!DOCTYPE html>
# coursera-test
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee Flavored Homemade Ice Cream</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #5D4037;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .hero {
            background-image: url('hero-image.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
        }
        .hero p {
            font-size: 1.5em;
        }
        .container {
            padding: 20px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin: 20px;
            padding: 20px;
            width: 300px;
            text-align: center;
        }
        .product-item img {
            width: 100%;
            border-radius: 5px;
        }
        .product-item h2 {
            margin: 10px 0;
        }
        footer {
            background-color: #5D4037;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Coffee Flavored Homemade Ice Cream</h1>
        <nav>
            <a href="#home" style="color: white; margin: 0 10px;">Home</a>
            <a href="#about" style="color: white; margin: 0 10px;">About</a>
            <a href="#products" style="color: white; margin: 0 10px;">Products</a>
            <a href="#contact" style="color: white; margin: 0 10px;">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Delicious Coffee Flavored Ice Cream</h1>
        <p>Made with love and the finest ingredients</p>
        <button style="padding: 10px 20px; background-color: #FFC107; border: none; border-radius: 5px; cursor: pointer;">Shop Now</button>
    </section>

    <section class="container" id="about">
        <h2>About Us</h2>
        <p>We are passionate about creating the finest coffee-flavored ice cream using the best ingredients. Our journey started in a small kitchen and has grown into a beloved brand cherished by ice cream lovers everywhere.</p>
    </section>

    <section class="container" id="products">
        <h2>Our Products</h2>
        <div class="product">
            <div class="product-item">
                <img src="icecream1.jpg" alt="Coffee Ice Cream">
                <h2>Classic Coffee</h2>
                <p>Rich and creamy coffee-flavored ice cream.</p>
                <button style="padding: 10px 20px; background-color: #FFC107; border: none; border-radius: 5px; cursor: pointer;">Add to Cart - $5.99</button>
            </div>
            <div class="product-item">
                <img src="icecream2.jpg" alt="Vanilla Coffee Ice Cream">
                <h2>Vanilla Coffee</h2>
                <p>A delightful blend of vanilla and coffee.</p>
                <button style="padding: 10px 20px; background-color: #FFC107; border: none; border-radius: 5px; cursor: pointer;">Add to Cart - $5.99</button>
            </div>
            <!-- Add more product items as needed -->
        </div>
    </section>

    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
            <button type="submit" style="padding: 10px 20px; background-color: #FFC107; border: none; border-radius: 5px; cursor: pointer;">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Coffee Flavored Homemade Ice Cream. All rights reserved.</p>
        <div>
            <a href="https://facebook.com" style="color: white; margin: 0 10px;">Facebook</a>
            <a href="https://instagram.com" style="color: white; margin: 0 10px;">Instagram</a>
            <a href="https://twitter.com" style="color: white; margin: 0 10px;">Twitter</a>
        </div>
    </footer>
</body>
</html>
