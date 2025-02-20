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
        }

        body {
            background-image: url('https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/878114.jpg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            color: var(--text-color);
        }
        html {
            scroll-behavior: smooth;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style-type: none;
            padding: 0;
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
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 20px;
            align-items: center;
        }
        h1 {
            font-family: 'Proxima Nova', sans-serif; 
            font-size: 48px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            color: transparent;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.6);
            text-align: left; /* Align title to the left */
        }
        .headshot {
            width: 225px; 
            height: 225px; 
            border-radius: 50%;
            margin: 0 auto 0 0; /* Align the image to the left */
        }
        .about-description {
            text-align: left;
            font-size: 18px;
            font-weight: bold;
            color: var(--text-color);
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .project,
        .testimonial {
            margin-bottom: 20px;
            padding: 15px;
            background: var(--background-color);
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
            color: var(--text-color);
            transition: transform 0.3s, background 0.3s, color 0.3s;
        }
        .project {
            font-size: 20px;
            color: yellow;
        }
        .project span {
            color: red;
            animation: pulse 2s infinite;
        }
        .project:hover,
        .testimonial:hover,
        .contact:hover {
            background: black;
            color: white;
            transform: scale(1.05);
            transition: transform 0.3s, background 0.3s, color 0.3s;
        }
        .contact {
            width: 100%;
            max-width: 600px;
            padding: 10px 20px;
            background: var(--background-color);
            border-radius: 5px;
            font-size: 16px;
            color: var(--text-color);
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
            clear: both; /* Ensure the footer stays below the contact card */
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
                grid-template-columns: 1fr;
                text-align: center;
            }
            .headshot {
                width: 150px;
                height: 150px;
                margin: 0 auto; /* Center the image */
            }
            h1 {
                font-size: 36px;
                text-align: center; /* Center the title on small screens */
            }
            .about-description {
                text-align: center; /* Center the about description on small screens */
            }
            body {
                padding: 20px;
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
    <h1 id="top">Data Analysis Portfolio</h1>
    <section id="skills" class="skills">
        <i class="fas fa-database"></i> SQL
        <i class="fas fa-chart-line"></i> Power BI
        <i class="fas fa-file-excel"></i> Excel
    </section>
    <section id="projects">
        <div class="project">
