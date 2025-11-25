## Hi there 👋
## About Me

💻 Passionate about full-stack development

🎓 Computer Science student

🔥 Love creating web applications using Laravel, React, Java

🌱 Currently learning: Spring Boot, Vue Js

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio - Trix</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #0d0d0d;
            color: #e6e6e6;
            overflow-x: hidden;
        }

        /* Smooth fade + slide animation */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        header {
            background: #121212;
            color: #00eaff;
            padding: 25px;
            text-align: center;
            font-size: 26px;
            font-weight: 600;
            letter-spacing: 1px;
            animation: fadeInUp 1s ease-in-out;
        }

        nav {
            background: #181818;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 18px;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0, 255, 255, 0.1);
        }

        nav a {
            color: #e6e6e6;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #00eaff;
            transform: translateY(-3px);
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 80vh;
            background: linear-gradient(135deg, #00131a, #000);
            color: white;
            flex-direction: column;
            text-align: center;
            animation: fadeInUp 1s ease;
        }

        .hero h1 { font-size: 55px; letter-spacing: 1px; }

        .hero p { font-size: 22px; margin-top: 12px; opacity: 0.8; }

        .btn {
            margin-top: 25px;
            padding: 12px 30px;
            background: #00eaff;
            color: #000;
            cursor: pointer;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #00b8cc;
            transform: scale(1.05);
        }

        .section {
            padding: 60px;
            max-width: 1200px;
            margin: auto;
            animation: fadeInUp 1s ease;
        }

        .section h2 {
            font-size: 38px;
            margin-bottom: 25px;
            color: #00eaff;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .skills-list {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .skill-box {
            background: #121212;
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            font-size: 20px;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.15);
            transition: 0.3s;
        }

        .skill-box:hover {
            transform: translateY(-8px);
            box-shadow: 0 0 25px rgba(0, 255, 255, 0.4);
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .project-box {
            background: #121212;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.12);
            transition: 0.3s;
        }

        .project-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 30px rgba(0, 255, 255, 0.5);
        }

        footer {
            background: #000;
            color: #00eaff;
            text-align: center;
            padding: 25px;
            margin-top: 50px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <header>
        Portfolio Website - Trix
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>Hello, I'm Trix</h1>
        <p>Software Engineer | Web Developer | Tech Enthusiast</p>
        <a class="btn" href="#contact">Contact Me</a>
    </div>

    <div class="section" id="about">
        <h2>About Me</h2>
        <p>
            I'm a passionate software engineer with experience in building web applications using
            HTML, CSS, JavaScript, React, Firebase, Java, Spring, and more. I love solving
            real‑world problems through clean and efficient code.
        </p>
    </div>

    <div class="section" id="skills">
        <h2>Skills</h2>
        <div class="skills-list">
            <div class="skill-box">HTML</div>
            <div class="skill-box">CSS</div>
            <div class="skill-box">JavaScript</div>
            <div class="skill-box">Java</div>
            <div class="skill-box">React</div>
            <div class="skill-box">Firebase</div>
        </div>
    </div>

    <div class="section" id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-box">
                <h3>Online Auction System</h3>
                <p>J2EE auction platform where users can bid within a time limit.</p>
            </div>
            <div class="project-box">
                <h3>Social-Hive</h3>
                <p>A social media clone built with React + Firebase.</p>
            </div>
            <div class="project-box">
                <h3>Tic Tac Toe AI</h3>
                <p>Python game including player vs AI using Minimax algorithm.</p>
            </div>
        </div>
    </div>

    <div class="section" id="contact">
        <h2>Contact</h2>
        <p>Email: yourname@gmail.com</p>
        <p>LinkedIn: linkedin.com/in/yourprofile</p>
    </div>

    <footer>
        © 2025 Trix | All Rights Reserved
    </footer>

</body>
</html>

