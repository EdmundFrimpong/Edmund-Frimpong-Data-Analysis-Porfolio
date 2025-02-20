<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edmund Frimpong - Data Analysis Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Proxima+Nova:wght@700&display=swap');

        :root {
            --primary-color: #ff8c00;
            --secondary-color: #ffd700;
            --background-color: black;
            --text-color: white;
            --card-radius: 10px; /* More rounded cards */
            --shadow-color: rgba(0, 0, 0, 0.4); /* Subtle shadow color */
        }

        body {
            background-image: url('https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/878114.jpg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 50px;
            color: var(--text-color);
            margin: 0;
        }
        html {
            scroll-behavior: smooth;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style-type: none;
            padding: 0;
            margin-bottom: 30px;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: var(--secondary-color);
        }
        .container {
            display: flex;
            align-items: center;
            gap: 20px;
            justify-content: center;
            margin-bottom: 40px;
        }
        h1 {
            font-family: 'Proxima Nova', sans-serif;
            font-size: 48px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            color: transparent;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.6);
            text-align: left;
        }
        .headshot {
            width: 225px;
            height: 225px;
            border-radius: 50%;
            object-fit: cover;
        }
        .about-description {
            text-align: left;
            font-size: 18px;
            font-weight: bold;
            color: var(--text-color);
            max-width: 600px;
            margin-left: 20px;
        }
        .project,
        .testimonial,
        .contact {
            margin-bottom: 20px;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: var(--card-radius);
            font-size: 18px;
            font-weight: bold;
            color: var(--text-color);
            transition: transform 0.3s, background 0.3s, color 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 8px var(--shadow-color);
        }
        .project:hover,
        .testimonial:hover,
        .contact:hover {
            background: rgba(0, 0, 0, 0.9);
            color: white;
            transform: scale(1.05);
            box-shadow: 0 8px 16px var(--shadow-color);
        }
        .project {
            font-size: 20px;
            color: yellow;
        }
        .project span {
            color: red;
            animation: pulse 2s infinite;
        }
        .contact {
            width: 100%;
            max-width: 600px;
            padding: 10px 20px;
            display: flex;
            justify-content: space-around;
            margin: 20px auto;
        }
        .contact a {
            color: blue;
            text-decoration: none;
            transition: transform 0.3s, color 0.3s;
        }
        .contact a:hover {
            transform: scale(1.05);
            color: red;
        }
        .skills {
            margin: 20px 0;
            font-size: 24px;
        }
        .skills i {
            margin-right: 10px;
        }
        section {
            margin: 40px 0;
        }
        footer {
            margin-top: 40px;
            padding: 20px;
            background: black;
            color: white;
            text-align: center;
        }
        footer a {
            color: #ffd700;
            text-decoration: none;
            transition: color 0.3s;
        }
        footer a:hover {
            color: #ff8c00;
        }
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                text-align: center;
            }
            .headshot {
                width: 150px;
                height: 150px;
                margin: 0 auto;
            }
            h1 {
                font-size: 36px;
                text-align: center;
            }
            .about-description {
                text-align: center;
            }
            body {
                padding: 20px;
            }
            .project,
            .testimonial,
            .contact {
                padding: 15px;
            }
        }
    </style>
    <meta name="description" content="Data Analysis Portfolio of Edmund Frimpong showcasing projects and skills in SQL, Excel, and Power BI.">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <div>
            <img src="https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/IMG_20250219_205530%20copy.png" alt="Edmund Frimpong" class="headshot">
        </div>
        <div class="about-description">
            Operations & Risk Analyst | Google Data Analytics Certificate | Data Storytelling & Reporting | SQL, Excel & Power BI
        </div>
    </div>
    <section id="skills" class="skills">
        <i class="fas fa-database"></i> SQL
        <i class="fas fa-chart-line"></i> Power BI
        <i class="fas fa-file-excel"></i> Excel
    </section>
    <section id="projects">
        <div class="project">
            <h3>SQL Project</h3>
            <p>Analysis of sales data using SQL.</p>
            <a href="https://github.com/EdmundFrimpong/sql-project" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Capstone Project</h3>
            <p>Comprehensive data analysis project integrating multiple skills.</p>
            <a href="https://github.com/EdmundFrimpong/capstone-project" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Excel Project</h3>
            <p>Financial modeling and analysis using Excel.</p>
            <a href="https://github.com/EdmundFrimpong/excel-project" target="_blank">View Project</a>
        </div>
    </section>
    <section id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonial">
            <p>"Edmund's analytical skills are top-notch. He provided invaluable insights for our project."</p>
            <p><strong>- John Doe, Project Manager</strong></p>
        </div>
    </section>
    <section id="contact" class="contact">
        <a href="mailto:edxfrimpong@gmail.com">edxfrimpong@gmail.com</a>
        <a href="https://www.linkedin.com/in/edmund-frimpong-b650a5141/" target="_blank">Edmund Frimpong</a>
    </section>
    <footer>
        <p>&copy; 2025 Edmund Frimpong. All rights reserved.</p>
        <p><a href="#top">Back to top</a></p>
    </footer>
</body>
</html>
