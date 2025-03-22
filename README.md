<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            overflow: hidden;
            text-align: center;
        }

        .snake {
            position: absolute;
            width: 10px;
            height: 10px;
            background-color: lime;
            animation: moveSnake 5s linear infinite;
        }

        @keyframes moveSnake {
            0% {
                top: 50%;
                left: 0%;
            }
            25% {
                top: 60%;
                left: 30%;
            }
            50% {
                top: 50%;
                left: 60%;
            }
            75% {
                top: 40%;
                left: 90%;
            }
            100% {
                top: 50%;
                left: 100%;
            }
        }

        h1, p {
            color: #fff;
            margin: 10px;
        }

        .tech-stack, .socials, .stats {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="snake"></div>

    <h1>💫 About Me:</h1>
    <p>🤝 Let’s Build the Future Together! I’m eager to collaborate on cutting-edge AI-driven drone technologies, next-gen flight control systems, seamless sensor integrations, and full-stack web development that powers innovation.</p>

    <p>🛠️ Bringing Ideas to Reality—As the Project Lead at FK Textile, I manage the entire web development process, leading a software team to create seamless, high-performance digital experiences. Additionally, my work in Yılkı Drone Systems involves developing AI-powered UAV solutions for fire detection and suppression, combining software, hardware, and automation.</p>

    <p>👐 Seeking Visionaries & Game-Changers—whether it’s business growth, high-impact sponsorships, or mastering cloud computing, I’m all about pushing boundaries and making things happen.</p>

    <p>🌱 Always Evolving—Diving deep into advanced machine learning, UAV embedded systems, and modern web technologies to stay ahead of the curve.</p>

    <p>💬 Ask Me About drone tech, AI in aviation, software project management, and web development that scales!</p>

    <p>⚡ Fun Fact: With a background in both aviation and tech, I merge engineering precision with digital innovation, crafting solutions that take industries to new heights.</p>

    <div class="tech-stack">
        <h2>💻 Tech Stack:</h2>
        <p>HTML, CSS, JavaScript, Python, Flask, AWS, Node.js, React, Next.js, and more...</p>
    </div>

    <div class="socials">
        <h2>🌐 Socials:</h2>
        <p>
            [<a href="https://linkedin.com/in/furkanasknn" style="color: #0e76a8;">LinkedIn</a>] 
            [<a href="mailto:furkanasknn@gmail.com" style="color: #d14836;">Email</a>]
        </p>
    </div>

    <div class="stats">
        <h2>📊 GitHub Stats:</h2>
        <!-- Insert your GitHub stats and other dynamic content here -->
    </div>
</body>
</html>
