# stopitshivam.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Modern Reset and Variables */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }

        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-color: #c9d1d9;
            --accent-color: #58a6ff;
            --white: #ffffff;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding-bottom: 60px;
        }

        /* Container wrapper */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 30px 0;
        }

        nav .logo {
            font-weight: 700;
            font-size: 1.2rem;
            color: var(--white);
            text-decoration: none;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }

        nav ul a {
            color: var(--text-color);
            text-decoration: none;
            transition: color 0.2s ease;
        }

        nav ul a:hover {
            color: var(--accent-color);
        }

        /* Hero Section */
        .hero {
            padding: 60px 0 80px 0;
        }

        .hero h1 {
            font-size: 2.8rem;
            color: var(--white);
            margin-bottom: 15px;
        }

        .hero h1 span {
            color: var(--accent-color);
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: var(--bg-color);
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            transition: opacity 0.2s;
        }

        .btn:hover {
            opacity: 0.9;
        }

        /* Grid Sections */
        section {
            padding: 40px 0;
        }

        section h2 {
            font-size: 1.8rem;
            color: var(--white);
            margin-bottom: 25px;
            border-bottom: 1px solid #21262d;
            padding-bottom: 10px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        /* Custom Cards */
        .card {
            background-color: var(--card-bg);
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 25px;
            transition: transform 0.2s, border-color 0.2s;
        }

        .card:hover {
            transform: translateY(-4px);
            border-color: var(--accent-color);
        }

        .card h3 {
            color: var(--white);
            margin-bottom: 10px;
        }

        .card p {
            font-size: 0.95rem;
            margin-bottom: 15px;
        }

        .card .tags {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
        }

        .card .tag {
            background: #21262d;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.75rem;
            color: var(--accent-color);
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 60px;
            font-size: 0.9rem;
            color: #8b949e;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Navigation Bar -->
        <nav>
            <a href="#" class="logo">MyPortfolio.</a>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

        <!-- Hero Welcome Section -->
        <header class="hero" id="about">
            <h1>Hi, I'm <span>Your Name</span></h1>
            <p>I am a developer building clean, lightweight, and modern software experiences. Welcome to my personal slice of the internet.</p>
            <a href="#contact" class="btn">Get In Touch</a>
        </header>

        <!-- Projects Showcase Section -->
        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="grid">
                
                <!-- Project 1 -->
                <div class="card">
                    <h3>Project One</h3>
                    <p>A web application that solves a real-world problem. Built with clean code practices.</p>
                    <div class="tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">JavaScript</span>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="card">
                    <h3>Project Two</h3>
                    <p>An automation tool or interactive script built to make everyday tasks much faster.</p>
                    <div class="tags">
                        <span class="tag">Python</span>
                        <span class="tag">API</span>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="card">
                    <h3>Project Three</h3>
                    <p>A beautifully designed, mobile-responsive layout showcasing front-end capabilities.</p>
                    <div class="tags">
                        <span class="tag">UI/UX</span>
                        <span class="tag">Design</span>
                    </div>
                </div>

            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Me</h2>
            <p>I am currently open to collaboration, freelance gigs, or networking opportunities. Feel free to shoot me an email!</p>
            <p style="margin-top: 15px;">
                <strong>Email:</strong> <a href="mailto:your.email@example.com" style="color: var(--accent-color); text-decoration: none;">your.email@example.com</a>
            </p>
        </section>

        <!-- Footer Footer -->
        <footer>
            <p>&copy; 2026 Your Name. Powered by GitHub Pages.</p>
        </footer>
    </div>

</body>
</html>

