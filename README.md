# protfolio-webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
</head>
<body>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #2C2C2C;
    color: #fff;
}

header {
    background-color: #1A1A1A;
    padding: 20px;
    text-align: center;
}

header .navbar h1 {
    color: #f5a623;
    font-size: 2.5em;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2em;
}

.hero {
    background-color: #6a1b9a;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.5em;
    margin-bottom: 30px;
}

.hero button {
    background-color: #f5a623;
    color: #fff;
    padding: 10px 20px;
    font-size: 1.2em;
    border: none;
    cursor: pointer;
}

.hero button:hover {
    background-color: #e59414;
}

.about {
    background-color: #3C3C3C;
    padding: 60px 20px;
    text-align: center;
}

.about h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.profile {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.profile-img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
}

.bio {
    text-align: left;
    max-width: 600px;
}

.bio h3 {
    font-size: 2em;
    margin-bottom: 10px;
}

.bio p {
    font-size: 1.2em;
    margin-bottom: 10px;
}

footer {
    background-color: #1A1A1A;
    text-align: center;
    padding: 40px 20px;
}

footer h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

footer p {
    font-size: 1.2em;
}
    </style>

    <header>
        <div class="navbar">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to My Personal Portfolio</h2>
            <p>Showcasing my skills, projects, and accomplishments as a web developer.</p>
            <button onclick="scrollToAbout()">Learn More</button>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Me</h2>
        <div class="profile">
            <img src="WhatsApp Image 2025-05-31 at 17.00.47_13a3c81a.jpg" alt="Your Photo" class="profile-img">
            <div class="bio">
                <h3>John Doe</h3>
                <p>I am a passionate web developer with a background in full-stack development, and I love creating dynamic websites and web applications.</p>
                <p>Education: BSc in Computer Science | University XYZ</p>
                <p>Experience: 3+ years in web development</p>
            </div>
        </div>
    </section>

    <footer>
        <div id="contact">
            <h2>Contact Me</h2>
            <p>Feel free to reach out for collaborations or questions!</p>
            <p>Email: johndoe@example.com</p>
        </div>
    </footer>



    <script>
        function scrollToAbout() {
    document.getElementById('about').scrollIntoView({ behavior: 'smooth' });
}


    </script>
</body>
</html>
