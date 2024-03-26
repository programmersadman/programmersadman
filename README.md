<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Study Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to Our Study Website</h2>
            <p>This website is designed to help you with your studies.</p>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are a team of educators dedicated to providing high-quality study resources.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or feedback, feel free to contact us.</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Study Website. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


