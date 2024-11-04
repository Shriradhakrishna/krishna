<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>furniture Store</title>
	<link rel="stylesheet"href="style.css">
</head>
<body>
	<header>
        <h1>Furniture Store</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Our Furniture Store</h2>
        <p>Find the best furniture for your home.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="C:\Users\DELL\Downloads\furniture.jfif" alt="Sofa">
            <h3>Comfortable Sofa</h3>
            <p>Price: $250</p>
            <button onclick="addToCart('Comfortable Sofa', 250)">Add to Cart</button>
        </div>
        <div class="product">
            <img src="C:\Users\DELL\Downloads\chair.jfif" alt="Chair">
            <h3>Elegant Chair</h3>
            <p>Price: $100</p>
            <button onclick="addToCart('Elegant Chair', 100)">Add to Cart</button>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are a leading furniture store providing quality products for your home.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" required>
            <label for="message">Message:</label>
            <textarea id="message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Furniture Store</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
