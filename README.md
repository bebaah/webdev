<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rida Ahmed - Full-Stack Engineer Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin: 10px 0;
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .about, .skills, .projects {
            margin-bottom: 40px;
        }
        .skills ul {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .skills li {
            background-color: #3498db;
            color: white;
            padding: 10px 20px;
            margin: 10px;
            border-radius: 5px;
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .project {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin: 10px;
            width: 300px;
            text-align: center;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: #3498db;
            text-decoration: none;
        }
        @media (max-width: 768px) {
            .projects {
                flex-direction: column;
                align-items: center;
            }
            .skills ul {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Rida Ahmed</h1>
        <p>Full-Stack Engineer</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Rida Ahmed, a passionate full-stack engineer with expertise in building scalable web applications. I love turning ideas into reality through code, from front-end interfaces to back-end logic. With a keen eye for detail and a commitment to clean, efficient code, I strive to deliver high-quality solutions that meet user needs.</p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>JavaScript (ES6+)</li>
            <li>React.js</li>
            <li>Node.js</li>
            <li>Express.js</li>
            <li>Python</li>
            <li>MongoDB</li>
            <li>SQL (MySQL, PostgreSQL)</li>
            <li>Git & GitHub</li>
            <li>Docker</li>
            <li>RESTful APIs</li>
            <li>Agile Development</li>
        </ul>
    </section>

    <section class="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>E-Commerce Platform</h3>
            <p>A full-stack e-commerce site built with React, Node.js, and MongoDB. Features include user authentication, product listings, and payment integration.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Task Management App</h3>
            <p>A collaborative task manager using MERN stack (MongoDB, Express, React, Node). Includes real-time updates and team collaboration features.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Portfolio Website</h3>
            <p>This very portfolio! A responsive single-page application showcasing my skills and projects, built with HTML, CSS, and JavaScript.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
    </section>

    <footer>
        <p>Contact Me: <a href="mailto:rida.ahmed@example.com">rida.ahmed@example.com</a> | <a href="https://linkedin.com/in/ridaahmed" target="_blank">LinkedIn</a> | <a href="https://github.com/ridaahmed" target="_blank">GitHub</a></p>
        <p>&copy; 2023 Rida Ahmed. All rights reserved.</p>
    </footer>
</body>
</html>
