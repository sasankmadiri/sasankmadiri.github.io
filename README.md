<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Madiri Sasank | Digital Marketer & Web Developer</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-primary: #f8fafc;
            --text-secondary: #94a3b8;
            --accent: #38bdf8;
            --accent-hover: #0ea5e9;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: var(--bg-color);
            color: var(--text-primary);
            line-height: 1.6;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        header {
            text-align: center;
            margin-bottom: 50px;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: var(--text-primary);
        }
        header p {
            font-size: 1.2rem;
            color: var(--accent);
            margin-bottom: 20px;
        }
        .bio {
            color: var(--text-secondary);
            max-width: 600px;
            margin: 0 auto 25px auto;
        }
        .btn-group {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .btn {
            background-color: var(--accent);
            color: var(--bg-color);
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
        }
        .btn:hover {
            background-color: var(--accent-hover);
        }
        .btn-outline {
            background-color: transparent;
            color: var(--text-primary);
            border: 2px solid var(--accent);
        }
        .btn-outline:hover {
            background-color: var(--accent);
            color: var(--bg-color);
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            border-bottom: 2px solid var(--card-bg);
            padding-bottom: 8px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .card h3 {
            margin-bottom: 10px;
            color: var(--accent);
        }
        .card p {
            color: var(--text-secondary);
            font-size: 0.95rem;
            margin-bottom: 15px;
        }
        .tags {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
            margin-bottom: 15px;
        }
        .tag {
            background-color: #0f172a;
            color: var(--accent);
            font-size: 0.8rem;
            padding: 4px 8px;
            border-radius: 4px;
        }
        footer {
            text-align: center;
            color: var(--text-secondary);
            margin-top: 60px;
            font-size: 0.9rem;
            border-top: 1px solid var(--card-bg);
            padding-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>Madiri Sasank</h1>
            <p>Digital Marketing Trainee & Web Developer</p>
            <p class="bio">Results-driven professional specializing in data-driven marketing campaigns, social media management, brand development, and responsive web design.</p>
            <div class="btn-group">
                <a href="https://www.linkedin.com/in/madiri-sasank-622a8743b" target="_blank" class="btn">Connect on LinkedIn</a>
                <a href="mailto:sasank.digitalmarketer@gmail.com" class="btn btn-outline">Email Me</a>
            </div>
        </header>

        <!-- Projects Section -->
        <section>
            <h2>Featured Projects</h2>
            <div class="grid">
                <!-- Project 1 -->
                <div class="card">
                    <h3>Shreevastra</h3>
                    <p>A premier saree brand concept featuring targeted social media strategies, customized digital marketing workflows, and structured content campaigns.</p>
                    <div class="tags">
                        <span class="tag">Digital Marketing</span>
                        <span class="tag">Meta Business Suite</span>
                        <span class="tag">Brand Identity</span>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="card">
                    <h3>Scalecraft Studio</h3>
                    <p>A digital marketing portfolio and agency branding initiative showcasing social media ad creatives, content calendars, and campaign layouts.</p>
                    <div class="tags">
                        <span class="tag">Social Media Strategy</span>
                        <span class="tag">Content Planning</span>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="card">
                    <h3>Web Development Portfolio</h3>
                    <p>Custom-coded responsive web projects and zero-cost hosting configurations built using HTML, CSS, and modern deployment pipelines.</p>
                    <div class="tags">
                        <span class="tag">HTML/CSS</span>
                        <span class="tag">GitHub Pages</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section>
            <h2>Core Competencies</h2>
            <div class="card">
                <div class="tags">
                    <span class="tag">Digital Marketing & SEO</span>
                    <span class="tag">Social Media Optimization</span>
                    <span class="tag">Meta Business Suite</span>
                    <span class="tag">Web Development Fundamentals</span>
                    <span class="tag">Microsoft Excel & TallyPrime</span>
                    <span class="tag">Logistics & Billing Operations</span>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer>
            <p>&copy; 2026 Madiri Sasank. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
