<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coming Soon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            padding: 50px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 50px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 36px;
            color: #333;
        }
        .coming-soon {
            font-size: 30px;
            color: red;
            font-weight: bold;
            margin-top: 20px;
        }
        p {
            font-size: 18px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 id="project-title">Project Title</h1>
        <div class="coming-soon">Coming Soon</div>
        <p>Details to follow...</p>
        <a href="index.html">Back to Portfolio</a>
    </div>
    <script>
        const titles = {
            "sql_project.html": "SQL Project",
            "capstone_project.html": "Capstone Project",
            "excel_project.html": "Excel Project"
        };
        document.getElementById("project-title").innerText = titles[window.location.pathname.split("/").pop()] || "Project";
    </script>
</body>
</html>
