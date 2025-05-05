<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoang Viet (Coca2302) - GitHub Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #f5f7fa;
            color: #333;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 800px;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            padding: 30px;
            text-align: center;
        }
        h1 img {
            max-width: 100%;
            height: auto;
        }
        .intro {
            font-size: 1.1em;
            color: #555;
            margin: 20px 0;
        }
        .intro p {
            margin: 8px 0;
            transition: color 0.3s ease;
        }
        .intro p:hover {
            color: #007bff;
        }
        .section-title {
            font-size: 1.5em;
            color: #222;
            margin: 30px 0 15px;
            position: relative;
        }
        .section-title::after {
            content: '';
            width: 50px;
            height: 3px;
            background: #007bff;
            position: absolute;
            bottom: -5px;
            left: 50%;
            transform: translateX(-50%);
        }
        .interests {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        .interest-item {
            background: #e9f1ff;
            padding: 10px 2015px;
            border-radius: 20px;
            font-size: 0.9em;
            color: #333;
            transition: transform 0.3s ease, background 0.3s ease;
        }
        .interest-item:hover {
            transform: scale(1.1);
            background: #007bff;
            color: #fff;
        }
        .project-card {
            background: #f8fafc;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
        }
        .project-card a {
            color: #007bff;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.2em;
        }
        .project-card a:hover {
            color: #0056b3;
        }
        .project-card p {
            color: #555;
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
            color: #333;
        }
        .project-card ul li::before {
            content: '➔';
            position: absolute;
            left: 0;
            color: #007bff;
        }
        .stats img {
            max-width: 100%;
            height: auto;
        }
        .connect {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        .connect a {
            color: #333;
            text-decoration: none;
            font-size: 1em;
            padding: 10px 20px;
            border: 2px solid #007bff;
            border-radius: 20px;
            transition: background 0.3s ease, color 0.3s ease;
        }
        .connect a:hover {
            background: #007bff;
            color: #fff;
        }
        .connect .disabled {
            border-color: #ccc;
            color: #ccc;
            cursor: not-allowed;
        }
        .connect .disabled:hover {
            background: none;
            color: #ccc;
        }
        hr {
            border: 0;
            height: 1px;
            background: #ddd;
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>
            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&center=true&vCenter=true&width=435&lines=Hi+there+%F0%9F%91%8B;I'm+Hoang+Viet+(Coca2302)" alt="Typing SVG" />
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
</body>
</html>
