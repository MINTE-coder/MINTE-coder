<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vantirra</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: #fff;
            padding: 10px 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media(max-width: 600px) {
            nav {
                display: block;
            }
            nav a {
                display: block;
                margin: 5px 0;
                  }
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Vantirra</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>Vantirra is a platform dedicated to fostering creativity and innovation. We believe in the power of collaboration and strive to provide tools that empower individuals and teams to achieve their goals.</p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <ul>
        <li>Creative Consulting</li>
        <li>Project Management Tools</li>
        <li>Web Development Solutions</li>
        <li>Data Visualization Services</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Vantirra. All Rights Reserved.</p>
</footer>

</body>
</html>
