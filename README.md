<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  <style>
    /* Початковий стан елементів */
    .animated {
      opacity: 0;
      transform: translateX(100px);
      transition: all 0.8s ease-in-out;
    }

    .animated.show {
      opacity: 1;
      transform: translateX(0);
    }

    /* Додаткові стилі */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }
    img {
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <div class="animated">
    <h1>💫 About Me:</h1>
    <p>I am Misha Lavrenuyk, a designer-programmer with more than 2 years of experience and a content creator on the web. I have experience with programming languages ​​such as JavaScript, as well as markup and styling languages ​​such as HTML and CSS. I spend most of my time coding new and unique projects to improve my skills.</p>
  </div>

  <div class="animated">
    <h2>🌐 Socials:</h2>
    <p>
      <a href="https://www.facebook.com/shere/19iKmFzm/?mibextid=wwXlfr">Facebook</a> | 
      <a href="https://www.pinterest.com/mishalavrenaik">Pinterest</a> | 
      <a href="https://www.reddit.com/u/Colefainxx/s/vkCC5kLPul">Reddit</a> | 
      <a href="https://www.tiktok.com/@dllldgreal">TikTok</a> | 
      <a href="https://codepen.io/MrRep">CodePen</a>
    </p>
  </div>

  <div class="animated">
    <h2>💻 Tech Stack:</h2>
    <p>
      <img src="https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
      <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      <img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white" alt="Canva">
      <img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
      <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    </p>
  </div>

  <div class="animated">
    <img src="https://c4.wallpaperflare.com/wallpaper/976/74/465/multiple-display-mountains-snow-nature-wallpaper-preview.jpg" alt="Banner" style="width: 100%; height: auto;">
  </div>

  <div class="animated">
    <h2>📊 GitHub Stats:</h2>
    <table>
      <tr>
        <td>
          <img src="https://github-readme-stats.vercel.app/api?username=MrRep&theme=nord&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats">
        </td>
        <td>
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrRep&theme=nord&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Most Used Languages">
        </td>
      </tr>
    </table>
  </div>

  <div class="animated">
    <h2>🔝 Top Contributed Repo</h2>
    <p><img src="https://github-contributor-stats.vercel.app/api?username=MrRep&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="Top Contributed Repo"></p>
  </div>

  <div class="animated">
    <p><img src="https://visitcount.itsvg.in/api?id=MrRep&icon=7&color=4" alt="Profile Visits"></p>
  </div>

  <script>
    // Знаходимо всі елементи з класом "animated"
    const elements = document.querySelectorAll('.animated');

    // Додаємо клас "show" до кожного елемента з затримкою
    window.addEventListener('load', () => {
      elements.forEach((element, index) => {
        setTimeout(() => {
          element.classList.add('show');
        }, index * 200); // Затримка між елементами
      });
    });
  </script>

</body>
</html>

