# paintX
painting gallery 
<!DOCTYPE html>
<html lang="en">
<head>
<link rel="stylesheet" href="https://cdn.snipcart.com/themes/v3.0.31/default/snipcart.css" />
<script async src="https://cdn.snipcart.com/themes/v3.0.31/default/snipcart.js"></script>
<div hidden id="snipcart" data-api-key="YOUR_PUBLIC_API_KEY"></div>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Art Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Art Gallery</h1>
        <nav>
            <ul>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
           <div class="gallery-item">
    <img src="C:\Users\jagan\Pictures\1234.jpg"alt="Painting 1">
    <p>Painting 1</p>
    <button class="snipcart-add-item"
        data-item-id="painting1"
        data-item-price="100.00"
        data-item-url="/"
        data-item-description="A beautiful painting."
        data-item-image="C:\Users\jagan\Pictures\1234.jpg"
        data-item-name="Painting 1">
        Add to Cart
    </button>
</div>
<div class="gallery-item">
    <img src="C:\Users\jagan\Pictures\landscape.jpg" alt="Painting 2">
    <p>Painting 2</p>
    <button class="snipcart-add-item"
        data-item-id="painting2"
        data-item-price="150.00"
        data-item-url="/"
        data-item-description="Another beautiful painting."
        data-item-image="C:\Users\jagan\Pictures\landscape.jpg"
        data-item-name="Painting 2">
        Add to Cart
    </button>
</div>
 
<!-- Add more paintings as needed -->
</section>
    <section id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
<section id="newsletter">
    <h2>Subscribe to Our Newsletter</h2>
    <form action="subscribe.php" method="post">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <button type="submit">Subscribe</button>
    </form>
</section>
<footer>
        <p>© 2024 My Art Gallery</p>
    </footer>
</body>
</html>
