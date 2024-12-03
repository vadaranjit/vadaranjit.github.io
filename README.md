<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ranajit's Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #edf2f7;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #6a11cb, #2575fc);
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        nav {
            margin: 15px 0;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 10px;
            font-size: 1.1em;
            font-weight: bold;
        }

        main {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        section {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        section:hover {
            transform: scale(1.03);
        }

        h2 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        footer {
            background: #6a11cb;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
            box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ranajit's Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I am Ranajit, a passionate developer and QA Automation Engineer. I specialize in creating efficient automation frameworks and delivering quality software solutions. With expertise in Java, Selenium, and Docker, I bring innovation and excellence to every project.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Automation Framework Design</strong>: Created robust frameworks for testing enterprise applications.</li>
                <li><strong>Web Testing Solutions</strong>: Delivered seamless web testing solutions using Selenium.</li>
                <li><strong>Dockerized Environments</strong>: Built scalable and containerized test environments.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Feel free to get in touch via email: <a href="mailto:vadaranjit@example.com">vadaranjit@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Ranajit. All rights reserved.</p>
    </footer>
</body>
</html>
