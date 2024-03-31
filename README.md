<!DOCTYPE html>
<html>
<head>
    <title>E-commerce Website</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header class="header">
        <div class="logo">
            <h1>E-commerce Website</h1>
        </div>
        <nav class="nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main class="main">
        <section class="hero">
            <h2>Welcome to our E-commerce Website</h2>
            <p>Find the best products at unbeatable prices.</p>
            <a href="#" class="button">Shop Now</a>
        </section>
        <section class="featured-products">
            <h2>Featured Products</h2>
            <ul class="product-list">
                <li class="product-item">
                    <img src="product1.jpg" alt="Product 1">
                    <h3>Product 1</h3>
                    <p>$100.00</p>
                    <a href="#" class="button">Add to Cart</a>
                </li>
                <li class="product-item">
                    <img src="product2.jpg" alt="Product 2">
                    <h3>Product 2</h3>
                    <p>$150.00</p>
                    <a href="#" class="button">Add to Cart</a>
                </li>
                <li class="product-item">
                    <img src="product3.jpg" alt="Product 3">
                    <h3>Product 3</h3>
                    <p>$200.00</p>
                    <a href="#" class="button">Add to Cart</a>
                </li>
            </ul>
        </section>
    </main>
    <footer class="footer">
        <p>&copy; 2023 E-commerce Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
/* style.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.header {
    background-color: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    padding: 1rem;
}

.header .logo {
    margin: 0;
}

.header .nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

.header .nav ul li {
    margin: 0 1rem;
}

.header .nav a {
    color: #fff;
    text-decoration: none;
}

.main {
    padding: 2rem;
}

.hero {
    background-image: url("hero.jpg");
    background-size: cover;
    background-position: center;
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 500px;
    text-align: center;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}
