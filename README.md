# latelier-moderne
Official website for L’ATELIER MODERNE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact – L’ATELIER MODERNE</title>

    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header class="header">
    <div class="container" style="display:flex; justify-content:space-between; align-items:center; height:80px;">
        <div class="logo">
            <h1>L’ATELIER MODERNE</h1>
        </div>

        <nav>
            <ul class="nav-list">
                <li><a href="index.html">Home</a></li>
                <li><a href="index.html#collections">Collections</a></li>
                <li><a href="index.html#products">Products</a></li>
                <li><a href="index.html#about">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>

        <div class="mobile-menu-toggle" id="mobile-toggle">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </div>
</header>

<section class="contact">
    <div class="container">
        <h2>Contact Us</h2>

        <div class="contact-info">
            <div class="info-item">
                <h3>Email</h3>
                <p>contact@lateliermoderne.com</p>
            </div>

            <div class="info-item">
                <h3>Phone</h3>
                <p>+33 6 00 00 00 00</p>
            </div>

            <div class="info-item">
                <h3>Location</h3>
                <p>France</p>
            </div>
        </div>

        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message"></textarea>
            <button class="cta-button" type="submit">Send Message</button>
        </form>
    </div>
</section>

<footer class="footer">
    <p>© 2026 L’ATELIER MODERNE. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
