<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smartmind Entertainment Limited</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to Smartmind Entertainment Limited</h1>
        <p>Where art meets innovation</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Smartmind Entertainment Limited, founded on June 25, 2024, is a premier art and entertainment company...</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Event Planning</li>
            <li>Production Services</li>
            <li>Creative Development</li>
        </ul>
    </section>

    <section id="events">
        <h2>Upcoming Events</h2>
        <!-- Event details will go here -->
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <!-- Gallery images will go here -->
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Smartmind Entertainment Limited. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
