<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Interactive README</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e293b, #0f172a);
            color: white;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(135deg, #4caf50, #81c784);
            clip-path: polygon(0 0, 100% 0, 100% 80%, 0 100%);
        }

        header img {
            max-width: 150px;
            border-radius: 50%;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            transform: translateZ(0);
        }

        header h1 {
            font-size: 2.5rem;
            margin-top: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        header h3 {
            font-size: 1.5rem;
            margin-top: 10px;
            color: #f5f5f5;
        }

        section {
            margin: 20px auto;
            padding: 20px;
            max-width: 900px;
            background: #1f2937;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }

        h3 {
            text-align: center;
            margin-bottom: 20px;
            color: #4caf50;
        }

        .profile-stats {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .profile-stats img {
            border: 2px solid #4caf50;
            border-radius: 50%;
            transition: transform 0.3s;
        }

        .profile-stats img:hover {
            transform: scale(1.2) rotate(360deg);
        }

        .social-links img {
            margin: 0 10px;
            height: 40px;
            transition: transform 0.3s;
        }

        .social-links img:hover {
            transform: scale(1.2) rotate(-20deg);
        }

        .languages-tools img {
            margin: 10px;
            transition: transform 0.3s, filter 0.3s;
        }

        .languages-tools img:hover {
            transform: scale(1.1);
            filter: brightness(1.5);
        }

        .stats {
            display: flex;
            justify-content: space-evenly;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .stats img {
            max-width: 300px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
        }

        .stats img:hover {
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            background: #0f172a;
            color: #4caf50;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://static.wixstatic.com/media/3eee0b_8b6780c6bd8245ecafdbe55d8db7e2df~mv2.gif" alt="MasterHead">
        <h1>Hi 👋, I'm Sajal Mondal</h1>
        <h3>An AI/ML Engineer, Advancing Technology with Passion</h3>
    </header>
    <section>
        <div class="profile-stats">
            <img src="https://komarev.com/ghpvc/?username=iamsajalmondal&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views">
            <a href="https://twitter.com/@sajalmo12942950" target="_blank">
                <img src="https://img.shields.io/twitter/follow/@sajalmo12942950?logo=twitter&style=for-the-badge" alt="Twitter">
            </a>
        </div>
        <ul>
            <li>🔭 I’m currently working on <b>NBA Prediction Dataset</b></li>
            <li>💬 Ask me about <b>Python, Machine Learning, Deep Learning, NLP, LLM, Computer Vision, SQL, Power Bi</b></li>
            <li>📫 Reach me at <b>sajalsmondal2001@gmail.com</b></li>
        </ul>
    </section>
    <section>
        <h3>Connect with me:</h3>
        <p class="social-links">
            <a href="https://twitter.com/@sajalmo12942950" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter">
            </a>
            <a href="https://linkedin.com/in/sajal-mondal-2226a8221" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn">
            </a>
            <a href="https://www.facebook.com/iamsajalmondal" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook">
            </a>
            <a href="https://www.instagram.com/iamsajalmondal/" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram">
            </a>
            <a href="https://www.youtube.com/channel/UCaN_fqhjfd8_SJOlXV4s2kg" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube">
            </a>
        </p>
    </section>
    <section>
        <h3>Languages and Tools:</h3>
        <div class="languages-tools">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40">
            <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV" width="40" height="40">
            <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40">
        </div>
    </section>
    <section>
        <h3>Stats:</h3>
        <div class="stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iamsajalmondal&layout=compact" alt="Top Languages">
            <img src="https://github-readme-stats.vercel.app/api?username=iamsajalmondal&show_icons=true" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=iamsajalmondal" alt="GitHub Streak">
        </div>
    </section>
    <footer>
        <p>Crafted
