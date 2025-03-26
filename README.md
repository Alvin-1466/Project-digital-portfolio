
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>X. Alvin Antony - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #b4eb34;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .profile-container {
            margin-right: 15px;
        }

        .profile-container img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid #d42c2c;
        }

        .header-content {
            text-align: left;
        }

        .header-content h1 {
            margin: 0;
            font-size: 24px;
        }

        .header-content small {
            font-size: 14px;
            color: #444;
        }

        .navbar {
            background-color: #d42c2c;
            text-align: center;
            padding: 10px 0;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }

        .navbar a:hover {
            background-color: #444;
            border-radius: 5px;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .section {
            background: white;
            padding: 20px;
            margin-top: 10px;
            border-radius: 5px;
            box-shadow: 0px 0px 10px 0px #aaa;
        }

        h2 {
            color: #d42c2c;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            padding: 5px 0;
        }

        .resume, .github {
            text-align: center;
            margin-top: 20px;
        }

        .resume a, .github a {
            display: inline-block;
            padding: 10px 20px;
            background: #444;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .resume a:hover, .github a:hover {
            background: #222;
        }

        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>

<body>

    <!-- Header Section with Profile Pic -->
    <div class="header">
        <div class="profile-container">
            <img src="Screenshot_2025-03-26-12-36-42-953_com.whatsapp.jpg" alt="X. Alvin Antony">
        </div>
        <div class="header-content">
            <h1>X. Alvin Antony</h1>
            <small>BCA Graduate</small>
        </div>
    </div>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">

        <!-- About Section -->
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>Motivated BCA graduate with strong programming and problem-solving skills, seeking an entry-level role to
                apply my knowledge in software development and IT solutions.</p>
        </div>

        <!-- Education Section -->
        <div id="education" class="section">
            <h2>Education</h2>
            <p>Prince Shri Venkateswara Arts and Science College</p>
        </div>

        <!-- Skills Section -->
        <div id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>Java</li>
                <li>C++</li>
                <li>Data Structures</li>
                <li>CSS</li>
                <li>HTML</li>
            </ul>
        </div>

        <!-- Projects Section -->
        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li>Guess a Number</li>
                <li>Digital Portfolio</li>
                <li>Pattern</li>
            </ul>
        </div>

        <!-- Resume Section -->
        <div id="resume" class="resume">
            <a href="#" onclick="alert('CV download will be available soon!')">Download CV</a>
        </div>

        <!-- GitHub Link -->
        <div class="github">
            <a href="https://github.com/Alvin-1466" target="_blank">Visit My GitHub</a>
        </div>

    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>© 2025 X. Alvin Antony</p>
    </div>

</body>

</html>
