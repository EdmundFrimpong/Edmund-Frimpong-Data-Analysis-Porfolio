<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

        :root {
            --primary-color: #ff8c00;
            --secondary-color: #ffd700;
            --background-color: black;
            --text-color: white;
            --card-radius: 10px;
            --shadow-color: rgba(0, 0, 0, 0.4);
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-image: url('https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/878114.jpg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
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
            font-family: 'Montserrat', sans-serif;
            font-size: 48px;
            color: white;
            text-align: center;
            background: none;
            text-shadow: none;
            margin-bottom: 40px;
        }
        .headshot {
            width: 225px;
            height: 225px;
            border-radius: 50%;
            object-fit: cover;
        }
        .about-description {
            text-align: center; /* Center the text */
            font-size: 32px; /* Increased font size */
            font-weight: bold;
            color: var(--text-color);
            max-width: 600px;
            margin-left: 20px;
            margin-top: 20px;
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
            position: relative;
        }
        .project:hover,
        .testimonial:hover,
        .contact:hover {
            background: rgba(0, 0, 0, 0.9);
            color: white;
            transform: scale(1.05);
            box-shadow: 0 8px 16px var(--shadow-color);
        }

        /* The new "COMING SOON" ribbon circle */
        .coming-soon {
            position: absolute;
            top: 0;
            left: 0;
            width: 80px;
            height: 80px;
            background-color: rgba(255, 0, 0, 0.7); /* Translucent red circle */
            color: white;
            font-size: 14px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            z-index: 1;
            animation: rotateRibbon 4s linear infinite; /* Animation for rotating the circle */
        }

        /* Animation to rotate the ribbon */
        @keyframes rotateRibbon {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        .contact-card {
            margin: 20px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7); /* Dark background */
            border-radius: var(--card-radius);
            text-align: center;
            width: 100%;
            max-width: 600px;
            box-shadow: 0 4px 8px var(--shadow-color);
        }

        .contact-card h3 {
            font-size: 24px;
            font-weight: bold;
            color: var(--text-color);
            margin-bottom: 20px;
        }

        .contact-details {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .contact-link {
            color: var(--primary-color);
            text-decoration: none;
            font-size: 18px;
            margin: 10px 0;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 10px; /* Space between icon and text */
        }

        .contact-link i {
            font-size: 20px; /* Icon size */
        }

        .contact-link:hover {
            color: var(--secondary-color); /* Change color on hover */
            transform: scale(1.05); /* Slight zoom effect on hover */
            transition: transform 0.3s, color 0.3s;
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
    <h1>Tools</h1>
    <section id="skills" class="skills">
        <i class="fas fa-database"></i> SQL
        <i class="fas fa-chart-line"></i> Power BI
        <i class="fas fa-file-excel"></i> Excel
    </section>
    <section id="projects">
        <div class="project">
            <h3>SQL Project</h3>
            <p>Analysis of sales data using SQL.</p>
            <a href="https://edmundfrimpong.github.io/SQL-Project/" target="_blank">View Project</a>
            <div class="coming-soon">COMING SOON!!!</div>
        </div>
        <div class="project">
            <h3>Capstone Project</h3>
            <p>Comprehensive data analysis project integrating multiple skills.</p>
            <a href="https://edmundfrimpong.github.io/Captsone-Project/" target="_blank">View Project</a>
            <div class="coming-soon">COMING SOON!!!</div>
        </div>
        <div class="project">
            <h3>Excel Project</h3>
            <p>Financial modeling and analysis using Excel.</p>
            <a href="https://edmundfrimpong.github.io/Excel-Project/" target="_blank">View Project</a>
            <div class="coming-soon">COMING SOON!!!</div>
        </div>
    </section>
    <section id="contact" class="contact-card">
        <h3>Contact Me</h3>
        <div class="contact-details">
            <a href="mailto:edxfrimpong@gmail.com" class="contact-link">
                <i class="fas fa-envelope"></i> Email: edxfrimpong@gmail.com
            </a>
            <a href="https://www.linkedin.com/in/edmund-frimpong-b650a5141/" target="_blank" class="contact-link">
                <i class="fab fa-linkedin"></i> LinkedIn: Edmund Frimpong
            </a>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Edmund Frimpong. All rights reserved.</p>
        <p><a href="#top">Back to top</a></p>
    </footer>
</body>
</html>
