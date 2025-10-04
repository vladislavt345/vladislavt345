<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Stack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            max-width: 600px;
            width: 100%;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }

        .avatar {
            text-align: center;
            margin-bottom: 30px;
        }

        .avatar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #667eea;
        }

        .section {
            margin-bottom: 30px;
        }

        .section:last-child {
            margin-bottom: 0;
        }

        h2 {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #667eea;
            margin-bottom: 15px;
            font-weight: 600;
        }

        .tech-grid {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .tech-item {
            transition: transform 0.2s;
        }

        .tech-item:hover {
            transform: translateY(-5px);
        }

        .tech-item img {
            width: 40px;
            height: 40px;
            filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.1));
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="avatar">
            <img src="https://media.tenor.com/tQThay3xZ-oAAAAi/cat.gif" alt="Avatar">
        </div>

        <div class="section">
            <h2>Core</h2>
            <div class="tech-grid">
                <a href="https://www.python.org/" class="tech-item" title="Python">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python">
                </a>
                <a href="https://docs.pytest.org/" class="tech-item" title="Pytest">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytest/pytest-original.svg" alt="Pytest">
                </a>
            </div>
        </div>

        <div class="section">
            <h2>CI/CD</h2>
            <div class="tech-grid">
                <a href="https://about.gitlab.com/" class="tech-item" title="GitLab">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitlab/gitlab-original.svg" alt="GitLab">
                </a>
                <a href="https://git-scm.com/" class="tech-item" title="Git">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
                </a>
                <a href="https://www.docker.com/" class="tech-item" title="Docker">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker">
                </a>
            </div>
        </div>

        <div class="section">
            <h2>Testing</h2>
            <div class="tech-grid">
                <a href="https://playwright.dev/" class="tech-item" title="Playwright">
                    <img src="https://playwright.dev/img/playwright-logo.svg" alt="Playwright">
                </a>
                <a href="https://swagger.io/" class="tech-item" title="Swagger">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swagger/swagger-original.svg" alt="Swagger">
                </a>
                <a href="https://www.postman.com/" class="tech-item" title="Postman">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" alt="Postman">
                </a>
            </div>
        </div>

        <div class="section">
            <h2>Tools</h2>
            <div class="tech-grid">
                <a href="https://code.visualstudio.com/" class="tech-item" title="VS Code">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code">
                </a>
                <a href="https://www.figma.com/" class="tech-item" title="Figma">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg" alt="Figma">
                </a>
                <a href="https://www.postgresql.org/" class="tech-item" title="PostgreSQL">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL">
                </a>
            </div>
        </div>

        <div class="section">
            <h2>OS</h2>
            <div class="tech-grid">
                <div class="tech-item" title="Linux">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux">
                </div>
                <div class="tech-item" title="Windows">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows">
                </div>
            </div>
        </div>
    </div>
</body>
</html>
