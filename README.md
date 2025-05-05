<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoang Viet (Coca2302) - GitHub Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 1200px;
            display: flex;
            gap: 20px;
        }
        .sidebar {
            width: 300px;
            text-align: center;
        }
        .profile-pic-placeholder {
            width: 260px;
            height: 260px;
            background: #161b22;
            border-radius: 50%;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.9em;
            color: #8b949e;
            border: 1px solid #30363d;
        }
        .username {
            font-size: 1.5em;
            font-weight: 600;
            color: #c9d1d9;
            margin: 15px 0 5px;
        }
        .handle {
            font-size: 1em;
            color: #8b949e;
            margin-bottom: 15px;
        }
        .main-content {
            flex: 1;
            background: #161b22;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.3);
        }
        h1 img {
            max-width: 100%;
            height: auto;
        }
        .intro {
            font-size: 1em;
            color: #c9d1d9;
            margin: 20px 0;
        }
        .intro p {
            margin: 8px 0;
            transition: color 0.3s ease;
        }
        .intro p:hover {
            color: #58a6ff;
        }
        .section-title {
            font-size: 1.4em;
            color: #f0f6fc;
            margin: 30px 0 15px;
            position: relative;
        }
        .section-title::after {
            content: '';
            width: 40px;
            height: 2px;
            background: #58a6ff;
            position: absolute;
            bottom: -5px;
            left: 0;
        }
        .interests {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        .interest-item {
            background: #21262d;
            padding: 8px 15px;
            border-radius: 15px;
            font-size: 0.9em;
            color: #c9d1d9;
            transition: background 0.3s ease, color 0.3s ease;
        }
        .interest-item:hover {
            background: #58a6ff;
            color: #0d1117;
        }
        .project-card {
            background: #0d1117;
            border-radius: 6px;
            padding: 15px;
            margin: 20px 0;
            text-align: left;
            border: 1px solid #30363d;
            transition: border-color 0.3s ease;
        }
        .project-card:hover {
            border-color: #58a6ff;
        }
        .project-card a {
            color: #58a6ff;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.2em;
        }
        .project-card a:hover {
            text-decoration: underline;
        }
        .project-card p {
            color: #c9d1d9;
            margin: 10px 0;
        }
        .project-card ul {
            list-style: none;
            padding: 0;
            margin: 10px 0;
        }
        .project-card ul li {
            margin: 8px 0;
            position: relative;
            padding-left: 20px;
            color: #c9d1d9;
        }
        .project-card ul li::before {
            content: '➔';
            position: absolute;
            left: 0;
            color: #58a6ff;
        }
        .stats img {
            max-width: 100%;
            height: auto;
        }
        .connect {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        .connect a {
            color: #c9d1d9;
            text-decoration: none;
            font-size: 0.9em;
            padding: 8px 15px;
            border: 1px solid #30363d;
            border-radius: 15px;
            transition: border-color 0.3s ease, color 0.3s ease;
        }
        .connect a:hover {
            border-color: #58a6ff;
            color: #58a6ff;
        }
        .connect .disabled {
            border-color: #30363d;
            color: #8b949e;
            cursor: not-allowed;
        }
        .connect .disabled:hover {
            border-color: #30363d;
            color: #8b949e;
        }
        hr {
            border: 0;
            height: 1px;
            background: #30363d;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <div class="profile-pic-placeholder">
                Contribution Graph Placeholder
            </div>
            <div class="username">Hoang Viet</div>
            <div class="handle">Coca2302 • he/him</div>
        </div>
        <div class="main-content">
            <h1>
                <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000¢er=true&vCenter=true&width=435&lines=Hi+there+%F0%9F%91%8B;I'm+Hoang+Viet+(Coca2302)" alt="Typing SVG" />
            </h1>

            <div class="intro">
                <p>🔬 Passionate about Machine Learning, Bioinformatics, and Deep Learning</p>
                <p>🌱 Currently learning Computer Vision, Data Preprocessing, and PyTorch</p>
                <p>🚀 Open to collaborations on AI for biology and protein classification projects</p>
                <p>💡 Love exploring how AI can support science and healthcare</p>
            </div>

            <hr>

            <h2 class="section-title">🧠 My Interests</h2>
            <div class="interests">
                <span class="interest-item">📊 Machine Learning</span>
                <span class="interest-item">📈 Deep Learning</span>
                <span class="interest-item">🧮 Data Science</span>
                <span class="interest-item">⚙️ Python</span>
                <span class="interest-item">🔥 PyTorch</span>
                <span class="interest-item">🛠️ Scikit-learn</span>
                <span class="interest-item">📓 Jupyter Notebooks</span>
                <span class="interest-item">🧪 AI for Real-World Problems</span>
            </div>

            <hr>

            <h2 class="section-title">📌 Highlight Project</h2>
            <div class="project-card">
                <a href="https://github.com/Coca2302/protein_classification">Protein Classification</a>
                <p>A Convolutional Neural Network (CNN) based on LeNet to classify protein sequences.</p>
                <ul>
                    <li>Implemented data preprocessing for amino acid sequences</li>
                    <li>Built CNN based on LeNet architecture</li>
                    <li>Achieved accurate predictions on sequence datasets</li>
                </ul>
            </div>

            <hr>

            <h2 class="section-title">📈 GitHub Stats</h2>
            <div class="stats">
                <img src="https://github-readme-stats.vercel.app/api?username=Coca2302&show_icons=true&theme=tokyonight" alt="GitHub Stats" width="400">
            </div>

            <hr>

            <h2 class="section-title">📫 Connect with Me</h2>
            <div class="connect">
                <a href="mailto:nguyenhoangviet23022004@gmail.com">📧 Email</a>
                <a href="#" class="disabled">🧪 Medium (Coming Soon)</a>
                <a href="#" class="disabled">💬 Telegram (Coming Soon)</a>
            </div>
        </div>
    </div>
</body>
</html>
