<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bharath raj</title></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #8BC34A;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #d32f2f;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background: #b71c1c;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
        }
        h2 {
            color: #d32f2f;
        }
        ul {
            list-style-type: none;
        }
        .btn {
            display: inline-block;
            background: black;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            margin-top: 10px;
        }
        .btn:hover {
            background: grey;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    Bharath raj<br>
    <small>computer science student</small>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a <strong>cyber security</strong> expert and technology enthusiast passionate about helping organizations protect their data and create secure online environments. With over 7 years of experience in the field, I stay updated with the latest trends in cyber security.</p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Madras University</strong> - Electrical & Electronics Engineering</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>CyberSecurity</li>
            <li>Internet of Things</li>
            <li>Cloud Computing</li>
            <li>Python</li>
            <li>IBM Cloud</li>
            <li>Machine Learning & AI</li>
            <li>Java, C++, JavaScript</li>
            <li>Blockchain</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><a href="#">AI-Based Alternator Control System</a></li>
            <li><a href="#">Cloud Security - IBM</a></li>
            <li><a href="#">IBM Chatbot</a></li>
        </ul>
    </section>

    <section id="resume">
        <h2>Resume</h2>
        <a href="your_resume.pdf" download class="btn">Download CV</a>
    </section>
</div>

<footer>
    &copy; 2025 Bharath raj
</footer>

</body>
</html>
