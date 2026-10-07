# index.html-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naveen Chandra Tewari | Personal Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        }

        body {
            background-color: #ffffff;
            color: #111111;
            line-height: 1.7;
        }

        /* Header / Hero Section */
        header {
            background-color: #f8f9fa;
            border-bottom: 1px solid #e9ecef;
            padding: 70px 20px 50px 20px;
            text-align: center;
        }

        .profile-img {
            width: 170px;
            height: 170px;
            border-radius: 50%;
            object-fit: cover;
            border: 1px solid #cccccc;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2.8rem;
            font-weight: 700;
            color: #000000;
            letter-spacing: -0.5px;
            margin-bottom: 8px;
        }

        header p {
            font-size: 1.25rem;
            color: #555555;
            font-weight: 400;
        }

        /* Navigation Bar */
        nav {
            background-color: #ffffff;
            border-bottom: 1px solid #e9ecef;
            text-align: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #333333;
            text-decoration: none;
            margin: 0 20px;
            font-size: 0.95rem;
            font-weight: 600;
            letter-spacing: 0.5px;
            text-transform: uppercase;
            transition: color 0.2s ease;
        }

        nav a:hover {
            color: #000000;
            text-decoration: underline;
        }

        /* Container Layout */
        .container {
            max-width: 850px;
            margin: 50px auto;
            padding: 0 20px;
        }

        /* Card Sections */
        .section-card {
            background: #ffffff;
            border: 1px solid #e9ecef;
            padding: 35px;
            margin-bottom: 35px;
            border-radius: 6px;
        }

        .section-card h2 {
            font-size: 1.6rem;
            color: #000000;
            border-bottom: 2px solid #111111;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-weight: 700;
        }

        .section-card p {
            color: #333333;
            font-size: 1.05rem;
            margin-bottom: 15px;
        }

        ul.skills-list, ul.exp-list {
            list-style: none;
            padding-left: 0;
        }

        ul.skills-list li, ul.exp-list li {
            position: relative;
            padding-left: 20px;
            margin-bottom: 12px;
            color: #333333;
            font-size: 1.05rem;
        }

        ul.skills-list li::before, ul.exp-list li::before {
            content: "—";
            position: absolute;
            left: 0;
            color: #111111;
            font-weight: bold;
        }

        /* Buttons */
        .btn {
            display: inline-block;
            background-color: #111111;
            color: #ffffff;
            padding: 12px 28px;
            text-decoration: none;
            border-radius: 4px;
            font-size: 0.95rem;
            font-weight: 600;
            margin-top: 15px;
            transition: background-color 0.2s ease;
        }

        .btn:hover {
            background-color: #333333;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            background-color: #f8f9fa;
            border-top: 1px solid #e9ecef;
            color: #666666;
            font-size: 0.9rem;
            margin-top: 60px;
        }
    </style>
</head>
<body>

    <header>
        <!-- Place your profile photo named 'profile.jpg' in the same folder -->
        <img src="profile.jpg" alt="Naveen Chandra Tewari" class="profile-img">
        <h1>Naveen Chandra Tewari</h1>
        <p>12+ Years of Professional Experience</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        
        <!-- About Section -->
        <section id="about" class="section-card">
            <h2>About Me</h2>
            <p>Hello! I am <strong>Naveen Chandra Tewari</strong>. With over <strong>12 years of professional experience</strong>, I specialize in operations management, IT processes, and software solutions execution. This personal portfolio highlights my professional journey, key competencies, and ongoing achievements.</p>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="section-card">
            <h2>Professional Experience</h2>
            <p>Demonstrated history of driving technical and operational execution across various domains:</p>
            <ul class="exp-list">
                <li><strong>12+ Years Industry Experience:</strong> Strong track record in overseeing IT infrastructure, technical coordination, and operational efficiency.</li>
                <li><strong>Process & IT Management:</strong> Proven capabilities in executing software solutions, technical troubleshooting, and cross-functional team communication.</li>
                <li><strong>Project Execution:</strong> Focused on delivering reliable performance, system management, and continuous workflow improvements.</li>
            </ul>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="section-card">
            <h2>Core Competencies</h2>
            <ul class="skills-list">
                <li>IT Management & Operational Operations</li>
                <li>Software Development & Integration</li>
                <li>Process Optimization & Analysis</li>
                <li>Technical Coordination & Leadership</li>
                <li>Problem Solving & Strategy Execution</li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="section-card">
            <h2>Contact Information</h2>
            <p>If you would like to get in touch regarding professional collaborations, consulting, or opportunities, feel free to email me directly:</p>
            <p><strong>Email:</strong> naveenchandra.tewari@gmail.com</p>
            <a href="mailto:naveenchandra.tewari@gmail.com" class="btn">Send Email</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Naveen Chandra Tewari. All Rights Reserved.</p>
    </footer>

</body>
</html>
