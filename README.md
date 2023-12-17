<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rabia Çevik - Computer Engineering Student</title>
  <style>
    @keyframes move {
      0% { transform: translateX(0); }
      50% { transform: translateX(10px); }
      100% { transform: translateX(0); }
    }

    h2 {
      text-align: left;
      font-family: 'Arial', sans-serif;
      background-image: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red);
      -webkit-background-clip: text;
      color: transparent;
      display: inline-block;
      animation: move 2s infinite;
    }

    .center {
      text-align: center;
    }

    .stats {
      height: 150px;
    }

    .languages {
      height: 150px;
    }

    .contributions {
      text-align: center;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <h2>Hi 👋! My name is<span class="colorful-text"> Rabia Çevik</span> and I'm a Senior Computer Engineering Student</h2>

  <div class="center">
    <img class="stats" src="https://github-readme-stats.vercel.app/api?username=rabiacevikk&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" alt="stats graph" />
    <img class="languages" src="https://github-readme-stats.vercel.app/api/top-langs?username=rabiacevikk&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" alt="languages graph" />
  </div>

  <img align="right" height="193" src="https://camo.githubusercontent.com/5ff9182d12e799168a3bb67b88df7388ae08ede3/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3837352f312a7164415731546a434e353768316c6275757a766368672e676966" alt="profile image" />

  <div class="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo" />
    <!-- Add more images for your skills -->
  </div>

  <div class="contributions">
    <h2>🐍 My Contributions 🐍</h2>
    <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/salesp07/salesp07/output/github-contribution-grid-snake.svg" />
  </div>
</body>
</html>
