<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .header {
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            color: white;
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        h2 {
            color: #ff6b81;
            border-bottom: 2px solid #ff6b81;
            padding-bottom: 5px;
            margin-top: 25px;
        }
        .logo {
            font-size: 1.8em;
            font-weight: bold;
        }
        .mango {
            color: #fff;
        }
        .ide {
            color: #333;
        }
        code {
            background-color: #f0f0f0;
            padding: 2px 5px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
        }
        pre {
            background-color: #f0f0f0;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .feature-list {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        .feature {
            margin-bottom: 15px;
            padding-left: 20px;
            border-left: 3px solid #ff9a9e;
        }
        .feature-title {
            font-weight: bold;
            color: #ff6b81;
        }
        .badge {
            display: inline-block;
            padding: 3px 8px;
            border-radius: 15px;
            font-size: 0.8em;
            font-weight: bold;
            margin-right: 8px;
        }
        .version {
            background-color: #4CAF50;
            color: white;
        }
        .license {
            background-color: #2196F3;
            color: white;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #777;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">
            <span class="mango">Mango</span> <>&nbsp;<span class="ide">Ide</span>
        </div>
        <p>Coding made sweet and simple</p>
        <div>
            <span class="badge version">v1.0.0</span>
            <span class="badge license">MIT License</span>
        </div>
    </div>

    <h2>📌 Project Description</h2>
    <p>Mango <> Ide is a lightweight, mobile-friendly coding environment designed to make programming accessible and enjoyable. With its clean interface and intuitive design, it's perfect for quick coding sessions on the go.</p>

    <h2>✨ Features</h2>
    <div class="feature-list">
        <div class="feature">
            <div class="feature-title">Mobile-First Design</div>
            <p>Fully responsive interface that works beautifully on all device sizes.</p>
        </div>
        <div class="feature">
            <div class="feature-title">Sweet Splash Screen</div>
            <p>Engaging animated splash screen with smooth transitions.</p>
        </div>
        <div class="feature">
            <div class="feature-title">Lightweight</div>
            <p>No heavy frameworks - pure HTML, CSS, and JavaScript.</p>
        </div>
        <div class="feature">
            <div class="feature-title">Customizable</div>
            <p>Easy to modify colors, animations, and content to match your brand.</p>
        </div>
    </div>

    <h2>🚀 Getting Started</h2>
    <h3>Installation</h3>
    <p>Simply include the HTML file in your project:</p>
    <pre><code>&lt;link rel="stylesheet" href="splash.css"&gt;
&lt;script src="splash.js"&gt;&lt;/script&gt;</code></pre>

    <h3>Usage</h3>
    <p>Add the splash screen HTML to your document:</p>
    <pre><code>&lt;div class="splash-screen"&gt;
    &lt;div class="logo-container"&gt;
        &lt;div class="mango"&gt;Mango&lt;/div&gt;
        &lt;div class="separator"&gt;&lt;&gt;&lt;/div&gt;
        &lt;div class="ide"&gt;Ide&lt;/div&gt;
    &lt;/div&gt;
    &lt;div class="tagline"&gt;Coding made sweet&lt;/div&gt;
    &lt;div class="loading-bar"&gt;
        &lt;div class="progress"&gt;&lt;/div&gt;
    &lt;/div&gt;
&lt;/div&gt;</code></pre>

    <h2>🛠 Customization</h2>
    <p>You can easily customize the splash screen by modifying these CSS variables:</p>
    <pre><code>:root {
    --primary-color: #ff9a9e;
    --secondary-color: #fad0c4;
    --text-color: #333;
    --highlight-color: #ff6b81;
}</code></pre>

    <h2>📜 License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE.md">LICENSE.md</a> file for details.</p>

    <div class="footer">
        <p>© 2023 Mango Ide Team | Made with ❤️ for developers</p>
    </div>
</body>
</html>
