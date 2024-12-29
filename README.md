<!DOCTYPE html>
<html lang="en">
<head>
    <title>Online Museum</title>
    <link rel="stylesheet" href="styles.css">
</head>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: gray;
}

header {
    background-color: black;
    color: white;
    text-align: center;
    padding: 1em 0;
}

 ul {
    list-style-type: none;
    padding: 0;
}

 ul li {
    display: inline;
    margin: 0 15px;
}

 a {
    color: red;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 30px;
    background-color: white;
    padding: 15px;
    border: 8px;
}

img {
aligen:"center";
    width: 200px
    height: 200px;
    border-radius: 4px;
<br>;
}

footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    width: 100%;
}

<body>
    <header>
        <h1>Welcome to the Online Museum</h1>
        
            <ul>
                <li><a href="#Your Interest">Interest</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        
    </header>
    <main>
        <section id="exhibits">
            <h2>Featured Exhibits</h2>
            <article>
                <h3>The Ancient Artifacts</h3>
                <p>Explore our collection of ancient artifacts from various civilizations.</p>
                <img src="IMG_20210910_100729.jpg" alt="Ancient Artifact">
  <img src="my passport.jpg" alt="Ancient Artifact">
            </article>
            <article>
                <h3>Modern Art Gallery</h3>
                <p>Discover contemporary art pieces from talented artists around the world.</p>
                <img src="modernart.jpg" alt="Modern Art">
            </article>
            <article>
                <h3>Science and Nature</h3>
                <p>Learn about the wonders of science through our interactive displays.</p>
                <img src="science.jpg" alt="Science Exhibit">
            </article>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Our museum is dedicated to preserving and showcasing art and history for future generations.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out!</p>
            <p>Email: info@onlinemuseum.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Online Museum</p>
    </footer>
</body>
</html>
