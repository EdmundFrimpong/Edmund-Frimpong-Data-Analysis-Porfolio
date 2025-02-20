<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edmund Frimpong - Data Analysis Portfolio</title>
    <!-- Material Design Lite CSS -->
    <link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Proxima+Nova:wght@700&display=swap');

        body {
            background-image: url('https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/878114.jpg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        h1 {
            font-family: 'Proxima Nova', sans-serif; /* Change font to Proxima Nova */
            font-size: 48px; /* Increase font size */
            background: linear-gradient(90deg, #ff8c00, #ffd700); /* Gradient text color */
            -webkit-background-clip: text;
            color: transparent; /* Set text color to transparent to show gradient */
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.6); /* 3D effect */
            animation: pulse 2s infinite; /* Add animation */
        }
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
            100% {
                transform: scale(1);
            }
        }
        .about {
            margin-bottom: 20px;
            padding: 15px;
            background: #d9edf7;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
        }
        .about img {
            width: 75px; /* Reduce the size by 50% */
            height: 75px; /* Reduce the size by 50% */
            border-radius: 50%; /* Make it a circle */
            display: block;
            margin: 10px auto;
        }
        .project {
            margin: 20px 0;
            padding: 15px;
            background: black; /* Black background for project cards */
            border-radius: 5px;
            font-size: 20px;
            font-weight: bold;
            color: yellow; /* Yellow text */
        }
        .project span {
            color: yellow; /* Change "Coming Soon" text color to yellow */
        }
        .contact {
            margin-top: 20px;
            padding: 15px;
            background: black; /* Black background for contact card */
            border-radius: 5px;
            font-size: 16px;
            color: yellow; /* Yellow text */
        }
        .contact a {
            color: yellow;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 10px 0;
        }
        .contact img {
            width: 24px;
            height: 24px;
            margin-right: 8px;
        }
    </style>
    <!-- Material Design Lite JavaScript -->
    <script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>
    <meta name="description" content="Data Analysis Portfolio of Edmund Frimpong showcasing projects and skills in SQL, Excel, and Power BI.">
</head>
<body>
    <div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
        <header class="mdl-layout__header">
            <div class="mdl-layout__header-row">
                <span class="mdl-layout-title">Edmund Frimpong - Data Analysis Portfolio</span>
                <div class="mdl-layout-spacer"></div>
                <nav class="mdl-navigation mdl-layout--large-screen-only">
                    <a class="mdl-navigation__link" href="#about">About</a>
                    <a class="mdl-navigation__link" href="#projects">Projects</a>
                    <a class="mdl-navigation__link" href="#contact">Contact</a>
                </nav>
            </div>
        </header>
        <main class="mdl-layout__content">
            <div class="page-content">
                <div class="container">
                    <h1>My Data Analysis Portfolio</h1>
                    <div class="about mdl-card mdl-shadow--2dp" id="about">
                        <img src="https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/IMG_20250219_205530%20copy.png" alt="Edmund Frimpong">
                        Operations & Risk Analyst | Google Data Analytics Certificate | Data Storytelling & Reporting | SQL, Excel & Power BI
                    </div>
                    <div class="project mdl-card mdl-shadow--2dp" id="projects">SQL Project - <span style="color: yellow;">Coming Soon</span></div>
                    <div class="project mdl-card mdl-shadow--2dp">Capstone Project - <span style="color: yellow;">Coming Soon</span></div>
                    <div class="project mdl-card mdl-shadow--2dp">Excel Project - <span style="color: yellow;">Coming Soon</span></div>
                    <div class="contact mdl-card mdl-shadow--2dp" id="contact">
                        <p>Contact Me:</p>
                        <a href="mailto:edxfrimpong@gmail.com">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" alt="Email icon"> edxfrimpong@gmail.com
                        </a>
                        <a href="https://www.linkedin.com/in/edmund-frimpong-b650a5141/" target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn icon"> Edmund Frimpong
                        </a>
                    </div>
                </div>
            </div>
        </main>
    </div>
</body>
</html>
