<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NormanArts - Artistic Expression</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }

        header {
            background-color: #ff6347;
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #ffa07a;
        }

        nav a {
            padding: 14px 20px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #ff4500;
        }

        section {
            padding: 40px;
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
        }

        .gallery img {
            max-width: 100%;
            height: auto;
            margin: 10px;
            border: 2px solid #333;
            border-radius: 8px;
        }

        .skills, .contact-info {
            background-color: #f8f8ff;
            padding: 20px;
            border-radius: 8px;
            margin: 20px;
            text-align: left;
        }

        footer {
            background-color: #ffa07a;
            padding: 20px;
            text-align: center;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>NormanArts</h1>
        <p>Where Artistic Expression Meets the Soul</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#gallery">Gallery</a>
        <a href="#on-sale">On Sale</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact Info</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Norman Shoe Sitali, an artist whose work transcends languages and touches hearts worldwide. My creations reflect my passion for expressing the beauty of existence, love, and the human experience. Through various art forms, I aim to spark deep reflection and connection.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery">
            <img src="artwork1.jpg" alt="Artwork 1">
            <img src="artwork2.jpg" alt="Artwork 2">
            <img src="artwork3.jpg" alt="Artwork 3">
            <!-- Add more images as needed -->
        </div>
    </section>

    <section id="on-sale">
        <h2>On Sale</h2>
        <p>Explore my latest artwork available for purchase:</p>
        <ul>
            <li><strong>Piece 1:</strong> A reflection on love and unity - $200</li>
            <li><strong>Piece 2:</strong> The beauty of transcendent existence - $350</li>
            <li><strong>Piece 3:</strong> Unconditional human connection - $500</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <p><strong>Creative Expression:</strong> Using various mediums to evoke emotions and thoughts.</p>
            <p><strong>Multilingual Artistry:</strong> Incorporating languages like English, Spanish, Portuguese, and more into artistic works.</p>
            <p><strong>Philosophical Depth:</strong> Exploring themes such as love, existence, and unity in all creations.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Info</h2>
        <div class="contact-info">
            <p><strong>Email:</strong> normanshoe@example.com</p>
            <p><strong>Phone:</strong> (123) 456-7890</p>
            <p><strong>Social Media:</strong> Follow me on Instagram @NormanArts</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 NormanArts. All rights reserved.</p>
    </footer>

</body>
</html>
