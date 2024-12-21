<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="An interactive website showcasing responsive design, interactivity, multimedia, and SEO optimization.">
    <meta name="keywords" content="Interactive Website, Responsive Design, API Integration, Multimedia">
    <meta name="author" content="Your Name">
    <title>Interactive Website</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Home Section -->
        <section id="home">
            <h1>Welcome to Our Interactive Website</h1>
            <p>Explore the power of responsive design, interactivity, and multimedia.</p>
        </section>

        <!-- Features Section -->
        <section id="features">
            <h2>Features</h2>

            <!-- Responsive Image Slider -->
            <div class="slider">
                <img src="image1.jpg" alt="Image 1" class="slide active">
                <img src="image2.jpg" alt="Image 2" class="slide">
                <img src="image3.jpg" alt="Image 3" class="slide">
                <button id="prev">&#10094;</button>
                <button id="next">&#10095;</button>
            </div>

            <!-- API Integration: Weather Info -->
            <div id="weather">
                <h3>Current Weather</h3>
                <p id="weather-data">Loading weather data...</p>
            </div>

            <!-- Accordion -->
            <div class="accordion">
                <button class="accordion-btn">What is this website about?</button>
                <div class="accordion-content">
                    <p>This website demonstrates advanced web design principles.</p>
                </div>
                <button class="accordion-btn">How do I navigate?</button>
                <div class="accordion-content">
                    <p>Use the navigation bar at the top of the page.</p>
                </div>
            </div>

            <!-- Multimedia Integration -->
            <div id="media">
                <h3>Introduction Video</h3>
                <video controls>
                    <source src="intro.mp4" type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject">

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Interactive Website. All Rights Reserved.</p>
    </footer>
</body>
</html>
