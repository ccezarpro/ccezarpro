<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Carlos Cezar Nunes</h1>
            <p>IT Developer with 3 years of experience | Learning Python</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I am an IT professional with 3 years of experience, currently diving into Python development. My passion for technology and software development drives me to continuously learn and adapt to new trends and technologies.</p>
        </div>
    </section>
    <section id="experience">
        <div class="container">
            <h2>Experience</h2>
            <ul>
                <li>
                    <h3>IT Analyst - Bioenergetica Aroeira S/A</h3>
                    <p><strong>Period:</strong> 03/08/2022 - Present</p>
                    <p>Responsible for perform maintenance on servers, computers and other network-related items. I also carry out cloud innovations</p>
                </li>
                <!-- Add more experiences as needed -->
            </ul>
        </div>
    </section>
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>Python Development</li>
                <li>IT Systems Management</li>
                <li>Technical Support</li>
                <li>Web Development</li>
                <!-- Add more skills as needed -->
            </ul>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Get in touch with me via email: <a href="mailto:carloscezar859@gmail.com">carloscezar859@gmail.com</a></p>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 Carlos Cezar Nunes. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>



body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    margin: 0;
    font-size: 1.2em;
}

nav {
    background: #444;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px 0;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

h2 {
    margin-top: 0;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    background: #fff;
    margin-bottom: 10px;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 0 5px #ccc;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

