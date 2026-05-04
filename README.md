<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iman Mukhlisin - Full Stack Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

        .header p {
            font-size: 1.2em;
            opacity: 0.95;
        }

        .content {
            padding: 40px;
        }

        .section {
            margin-bottom: 50px;
        }

        .section-title {
            font-size: 1.8em;
            color: #667eea;
            margin-bottom: 25px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            display: inline-block;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .tech-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            font-weight: bold;
            font-size: 1.1em;
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .tech-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.6);
        }

        .tech-card.react {
            background: linear-gradient(135deg, #61dafb 0%, #0ea5e9 100%);
        }

        .tech-card.next {
            background: linear-gradient(135deg, #000000 0%, #333333 100%);
        }

        .tech-card.express {
            background: linear-gradient(135deg, #90c53f 0%, #6ba82a 100%);
        }

        .tech-card.typescript {
            background: linear-gradient(135deg, #3178c6 0%, #235a97 100%);
        }

        .tech-card.laravel {
            background: linear-gradient(135deg, #ff2d20 0%, #cc2417 100%);
        }

        .tech-card.python {
            background: linear-gradient(135deg, #366994 0%, #ffd43b 50%, #366994 100%);
        }

        .about-text {
            font-size: 1.1em;
            line-height: 1.8;
            color: #333;
            margin-bottom: 20px;
        }

        .skills-list {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .skills-list li {
            background: #f5f5f5;
            padding: 15px;
            border-radius: 10px;
            border-left: 4px solid #667eea;
            font-size: 1.05em;
            color: #333;
        }

        .skills-list li:before {
            content: "✓ ";
            color: #667eea;
            font-weight: bold;
            margin-right: 10px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 30px;
            padding-top: 30px;
            border-top: 2px solid #f0f0f0;
        }

        .social-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-decoration: none;
            font-size: 1.3em;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
        }

        .social-btn:hover {
            transform: scale(1.15);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.5);
        }

        .quote {
            background: linear-gradient(135deg, #667eea15 0%, #764ba215 100%);
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #667eea;
            font-style: italic;
            font-size: 1.2em;
            color: #333;
            text-align: center;
            margin-top: 30px;
        }

        .tech-category {
            margin-bottom: 30px;
        }

        .category-label {
            font-size: 1.1em;
            color: #764ba2;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }

            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            }

            .content {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>👋 Iman Mukhlisin</h1>
            <p>Full Stack Developer | Web Enthusiast | Open Source Lover</p>
        </div>

        <div class="content">
            <!-- Tech Stack Section -->
            <div class="section">
                <h2 class="section-title">🚀 Tech Stack</h2>
                
                <div class="tech-category">
                    <p class="category-label">Frontend Frameworks</p>
                    <div class="tech-grid">
                        <div class="tech-card react">React.js</div>
                        <div class="tech-card next">Next.js</div>
                    </div>
                </div>

                <div class="tech-category">
                    <p class="category-label">Backend & Languages</p>
                    <div class="tech-grid">
                        <div class="tech-card express">Express.js</div>
                        <div class="tech-card typescript">TypeScript</div>
                        <div class="tech-card laravel">Laravel</div>
                        <div class="tech-card python">Python</div>
                    </div>
                </div>

                <div class="tech-category">
                    <p class="category-label">Additional Skills</p>
                    <div class="tech-grid">
                        <div class="tech-card" style="background: linear-gradient(135deg, #f1e05a 0%, #c3d91d 100%);">CSS3</div>
                        <div class="tech-card" style="background: linear-gradient(135deg, #e34c26 0%, #ff6b6b 100%);">HTML5</div>
                        <div class="tech-card" style="background: linear-gradient(135deg, #f7df1e 0%, #f5d547 100%); color: #333;">JavaScript</div>
                        <div class="tech-card" style="background: linear-gradient(135deg, #336791 0%, #2d5aa6 100%);">PostgreSQL</div>
                        <div class="tech-card" style="background: linear-gradient(135deg, #13aa52 0%, #0ca33b 100%);">MongoDB</div>
                        <div class="tech-card" style="background: linear-gradient(135deg, #2496ed 0%, #1e88e5 100%);">Docker</div>
                    </div>
                </div>
            </div>

            <!-- About Section -->
            <div class="section">
                <h2 class="section-title">💼 About Me</h2>
                <p class="about-text">
                    I'm a passionate Full Stack Developer dedicated to creating elegant, scalable solutions. 
                    With expertise in modern web technologies, I transform ideas into powerful applications 
                    that make a difference. Always eager to learn and collaborate on innovative projects.
                </p>
            </div>

            <!-- What I Do -->
            <div class="section">
                <h2 class="section-title">✨ What I Do</h2>
                <ul class="skills-list">
                    <li>Build scalable web applications with modern frameworks</li>
                    <li>Create responsive, user-friendly interfaces</li>
                    <li>Develop robust backend solutions & APIs</li>
                    <li>Optimize performance & security</li>
                    <li>Deploy & maintain production applications</li>
                    <li>Contribute to open source projects</li>
                </ul>
            </div>

            <!-- Connect Section -->
            <div class="section">
                <h2 class="section-title">🔗 Let's Connect</h2>
                <div class="social-links">
                    <a href="https://github.com/imanmukhlisin" class="social-btn" title="GitHub">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v 3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                        </svg>
                    </a>
                    <a href="https://linkedin.com/in/imanmukhlisin" class="social-btn" title="LinkedIn">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.475-2.236-1.986-2.236-1.081 0-1.722.722-2.004 1.418-.103.249-.129.597-.129.946v5.441h-3.554s.05-8.814 0-9.752h3.554v1.381c.43-.664 1.199-1.608 2.928-1.608 2.136 0 3.745 1.393 3.745 4.385v5.594zM5.337 9.433c-1.144 0-1.915-.758-1.915-1.704 0-.951.768-1.703 1.96-1.703 1.188 0 1.913.752 1.932 1.703 0 .946-.744 1.704-1.977 1.704zm1.582 11.019H3.771V9.956h3.148v10.496zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z"/>
                        </svg>
                    </a>
                    <a href="https://twitter.com/imanmukhlisin" class="social-btn" title="Twitter">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417a9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/>
                        </svg>
                    </a>
                    <a href="mailto:your.email@example.com" class="social-btn" title="Email">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                        </svg>
                    </a>
                </div>
            </div>

            <!-- Quote -->
            <div class="quote">
                ✨ "Code is poetry written in logic" ✨
            </div>
        </div>
    </div>
</body>
</html>
