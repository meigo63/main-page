<!DOCTYPE html>
<html lang="en">
<head>
    <title>Main Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to the Online I.V</h1>
        
            <ul>
                <li><a href="#Your Interest">Interest</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        
    </header>
    <main>
        <section id="Your Interest">
            <h2>CHOSEN INTERESTS</h2>
         <a href="https://meigo63.github.io/realmadrid/" title="real marid.html">SPORTS </a>
<p>View your sport intrsts<p>  
<a href="/semester%205/projects/DR%20HISHAM/WEB/carmuseum.html" title="carmuseum.html">CARS </a>
<p> View cars that have your interest <p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Our Website is dedicated to preserving and showcasing Your Interests In different Subjects.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out!</p>
            <p>Email: info@online I.V.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Online I.V</p>
    </footer>
</body>
</html>
<?php
$counterFile = 'counter.txt';
if (!file_exists($counterFile)) {
    file_put_contents($counterFile, 0);
}
$counter = (int)file_get_contents($counterFile);
$counter++;
file_put_contents($counterFile, $counter);
echo "This page has been visited $counter times.";
?>
