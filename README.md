# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Application</title>
    <link rel="stylesheet" href="app-styles.css">
    <script src="app.js" defer></script>
</head>
<body>
    <header class="navbar">
        <h1>My Web Application</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home" class="section">
            <h2>Welcome to My Web App</h2>
            <p>This is a fully responsive, multi-page web application built with HTML, CSS, and JavaScript. Explore the different sections to learn more.</p>
        </section>
        
        <section id="about" class="section">
            <h2>About</h2>
            <p>Our mission is to deliver high-quality web experiences that engage and inspire.</p>
        </section>
        
        <section id="shop" class="section">
            <h2>Shop</h2>
            <div class="product-grid">
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Product 1">
                    <h3>Product 1</h3>
                    <p>$25</p>
                    <button onclick="addToCart('Product 1', 25)">Add to Cart</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Product 2">
                    <h3>Product 2</h3>
                    <p>$30</p>
                    <button onclick="addToCart('Product 2', 30)">Add to Cart</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Product 3">
                    <h3>Product 3</h3>
                    <p>$40</p>
                    <button onclick="addToCart('Product 3', 40)">Add to Cart</button>
                </div>
            </div>
        </section>
        
        <section id="contact" class="section">
            <h2>Contact</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" required>
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email" required>
                <br>
                <label for="message">Message:</label>
                <textarea id="message" required></textarea>
                <br>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>© 2025 My Web Application. All rights reserved.</p>
    </footer>
</body>
</html>
