<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mock</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
            border-bottom: 1px solid #ddd;
            margin-bottom: 40px;
        }
        
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #0066cc;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }
        
        nav ul li a:hover {
            color: #0066cc;
        }
        
        .hero {
            text-align: center;
            padding: 60px 0;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #222;
        }
        
        .hero p {
            font-size: 20px;
            color: #666;
            max-width: 700px;
            margin: 0 auto 30px;
            line-height: 1.6;
        }
        
        .cta-button {
            display: inline-block;
            background-color: #0066cc;
            color: white;
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        
        .cta-button:hover {
            background-color: #0052a3;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin: 60px 0;
        }
        
        .feature {
            background-color: white;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }
        
        .feature h3 {
            font-size: 22px;
            margin-top: 0;
            margin-bottom: 15px;
            color: #222;
        }
        
        .feature p {
            color: #666;
            line-height: 1.6;
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            border-top: 1px solid #ddd;
            margin-top: 60px;
            color: #666;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">Mock</div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Pricing</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </header>
        
        <section class="hero">
            <h1>Build amazing things with Mock</h1>
            <p>Mock is a powerful platform that helps developers and designers create, collaborate, and ship better products faster than ever before.</p>
            <a href="#" class="cta-button">Get Started</a>
        </section>
        
        <section class="features">
            <div class="feature">
                <h3>Easy to Use</h3>
                <p>Our intuitive interface makes it simple for anyone to start creating mockups and prototypes in minutes, no training required.</p>
            </div>
            <div class="feature">
                <h3>Collaborative</h3>
                <p>Work seamlessly with your team in real-time, with built-in commenting and version control to keep everyone on the same page.</p>
            </div>
            <div class="feature">
                <h3>Powerful Integrations</h3>
                <p>Connect with your favorite tools like Slack, GitHub, and Figma to streamline your workflow and boost productivity.</p>
            </div>
        </section>
        
        <footer>
            <p>&copy; 2023 Mock. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
