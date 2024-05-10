<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .profile {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 40px;
            text-align: center;
        }
        .profile h1 {
            margin-bottom: 20px;
            color: #0366d6;
        }
        .profile p {
            margin-bottom: 20px;
        }
        .stats {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
        }
        .stat {
            flex: 1;
            padding: 20px;
            border-radius: 8px;
            background-color: #0366d6;
            color: #fff;
            margin: 0 10px;
        }
        .stat h2 {
            margin-bottom: 10px;
        }
        .streak-stats {
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <div class="profile">
        <h1>My GitHub Profile</h1>
        <p>Welcome to my GitHub profile!</p>
        
        <div class="stats">
            <div class="stat">
                <h2>GitHub Stats</h2>
                <img src="https://github-readme-stats.vercel.app/api?username=hhelaneyy&show_icons=true&theme=dark" alt="GitHub Stats">
            </div>
            <div class="stat">
                <h2>Streak Stats</h2>
                <a href="https://git.io/streak-stats">
                    <img src="https://streak-stats.demolab.com/?user=hhelaneyy&theme=dark&mode=weekly&currStreakNum=2FD3EB&fire=pink&sideLabels=F00&date_format=[Y.]n.j" alt="Streak Stats">
                </a>
            </div>
        </div>
    </div>
</body>
</html>
