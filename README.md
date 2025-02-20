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
            grid-template-columns: 1fr 2fr; /* Adjusted for headshot and about description */
            align-items: center;
            gap: 20px;
        }
        h1 {
            font-family: 'Proxima Nova', sans-serif; 
            font-size: 48px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            color: transparent;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.6);
            text-align: left; /* Make the title a straight line */
        }
        .headshot {
            width: 225px; 
            height: 225px; 
            border-radius: 50%; 
            margin: 20px;
            justify-self: start; /* Align headshot to the left */
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .about,
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
        .about {
            justify-self: start; /* Align about description to the right of the headshot */
        }
        .project {
            font-size: 20px;
            color: yellow;
        }
        .project span {
            color: red;
            animation: pulse 2s infinite;
        }
        .about:hover,
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
            }
            .headshot {
