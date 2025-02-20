<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edmund Frimpong - Data Analysis Portfolio</title>
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
            color: red; /* Change "Coming Soon" text color to red */
            animation: pulse 2s infinite; /* Add animation */
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
    <meta name="description" content="Data Analysis Portfolio of Edmund Frimpong showcasing projects and skills in SQL, Excel, and Power BI.">
</head>
<body>
    <div class="container">
        <h1>My Data Analysis Portfolio</h1>
        <div class="about">
            <img src="https://raw.githubusercontent.com/EdmundFrimpong/Edmund-Frimpong-Data-Analysis-Porfolio/main/IMG_20250219_205530%20copy.png" alt="Edmund Frimpong">
            Operations & Risk Analyst | Google Data Analytics Certificate | Data Storytelling & Reporting | SQL, Excel & Power BI
        </div>
        <div class="project">SQL Project - <span style="color: red;">Coming Soon!!!</span></div>
        <div class="project">Capstone Project - <span style="color: red;">Coming Soon!!!</span></div>
        <div class="project">Excel Project - <span style="color: red;">Coming Soon!!!</span></div>
        <div class="contact">
            <p>Contact Me:</p>
            <a href="mailto:edxfrimpong@gmail.com">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" alt="Email icon"> edxfrimpong@gmail.com
            </a>
            <a href="https://www.linkedin.com/in/edmund-frimpong-b650a5141/" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn icon"> Edmund Frimpong
            </a>
        </div>
    </div>
</body>
</html>
