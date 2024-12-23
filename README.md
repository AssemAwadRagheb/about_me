<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Network</title>
    <link href="https://fonts.googleapis.com/css?family=Tajawal&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            background: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            background: #4caf50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .header h1 {
            margin: 0;
            font-size: 36px;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px;
        }
        .box {
            width: 48%;
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .box h2 {
            margin-top: 0;
            color: #4caf50;
        }
        .box p {
            color: #666;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
        }
        .centered {
            text-align: center;
        }
        .image-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 10px;
        }
        .image-container img {
            width: 20%;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>My Network</h1>
    </div>
    <div class="container">
        <div class="content">
            <!-- Section 1 -->
            <div class="box">
                <div class="image-container">
                    <img src="https://i.pinimg.com/originals/3f/7e/4e/3f7e4eff7c96e9fe4b8b4b1ff3f7bdb5.gif" width="20%">
                </div>
                <h2>My Work</h2>
                <p>This section displays information about the work you're currently involved in.</p>
                <p class="centered">
                    <a href="https://git.io/typing-svg">
                        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=D2A306&center=true&vCenter=true&random=false&width=600&lines=Full-Stack+.NET+Developer;Penetration+Testing+Specialist;Always+Learning+New+Things;Building+Secure+Applications" alt="Typing SVG" />
                    </a>
                </p>
            </div>
            <!-- Section 2 -->
            <div class="box">
                <div class="image-container">
                    <img src="https://media.giphy.com/media/dMLmQfCO7lCA2gX3tw/giphy.gif?cid=ecf05e47ak6mwfu812269zzr8ydv529109qzpb8rszwnja9e&rid=giphy.gif&ct=s" width="20%">
                </div>
                <h2>My Projects</h2>
                <p>Here you can add details about the projects you're working on, including links and information.</p>
            </div>
            <!-- Section 3 -->
            <div class="box">
                <div class="image-container">
                    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="20%">
                </div>
                <h2>Reports</h2>
                <p>This section can be used to showcase reports on your work, projects, or any ongoing activities.</p>
            </div>
            <!-- Section 4 -->
            <div class="box">
                <div class="image-container">
                    <img src="https://i.ibb.co/6J0r7rW/Daco-5610880.png" width="20%">
                </div>
                <h2>Contact</h2>
                <p>Here you can add ways to contact you or interact with your team. Include social media links or email systems.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 My Network. All rights reserved.</p>
    </footer>
</body>
</html>
