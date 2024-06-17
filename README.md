<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.1em;
            line-height: 1.8;
        }

        .tetris-container {
            text-align: center;
            margin-bottom: 20px;
        }

        .tetris-game {
            display: inline-block;
            width: 100%;
            max-width: 400px;
        }

        .contact-info {
            font-size: 1.1em;
        }
    </style>
</head>

<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Tetris Enthusiast</p>
    </header>

    <div class="container">
        <section class="section">
            <h2>About Me</h2>
            <p>Add your bio here. Briefly introduce yourself and mention your interests, skills, and experiences.</p>
        </section>

        <section class="section">
            <h2>Portfolio - Tetris Game</h2>
            <div class="tetris-container">
                <canvas class="tetris-game" id="tetrisCanvas" width="300" height="600"></canvas>
                <p>Play a Tetris game I've developed!</p>
                <p><a href="tetris.html" target="_blank">Play Tetris</a></p>
            </div>
        </section>

        <section class="section">
            <h2>Contact Information</h2>
            <ul class="contact-info">
                <li>Email: yourname@example.com</li>
                <li>Phone: +1234567890</li>
                <li>Website: <a href="http://www.yourwebsite.com" target="_blank">www.yourwebsite.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/yourlinkedin" target="_blank">Your LinkedIn Profile</a></li>
                <li>GitHub: <a href="https://github.com/yourgithub" target="_blank">Your GitHub Profile</a></li>
            </ul>
        </section>
    </div>

    <footer style="text-align: center; background-color: #007bff; color: #fff; padding: 10px 0;">
        &copy; 2024 Your Name. All rights reserved.
    </footer>

    <!-- Optional: You can include your Tetris game JavaScript file here if needed -->

</body>

</html>
