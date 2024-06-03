# JavaScript Digital Clock with Neon Glow by Barrd

This is a simple digital clock with a neon glow effect created using HTML, CSS, and JavaScript.

## Usage

To use this code, simply copy the HTML, CSS, and JavaScript into your project. Below is the combined code for ease of use.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JavaScript digital clock with neon glow by barrd</title>
  <style>
    :root {
      --color__black: #141518;
      --color__red: #b00020;
      --color__white: #f5f5f5;
      --br: 0.5rem;
      --bs: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    }

    html {
      background-color: var(--color__white);
      background-image: url("data:image/svg+xml,%3Csvg width='6' height='6' viewBox='0 0 6 6' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='var(--color__black)' fill-opacity='0.1' fill-rule='evenodd'%3E%3Cpath d='M5 0h1L0 6V5zM6 5v1H5z'/%3E%3C/g%3E%3C/svg%3E");
      font-family: Arial, Helvetica, sans-serif;
      font-size: 1.5rem;
      color: #444;
      line-height: 1.5;
    }

    a {
      color: #444;
      text-decoration-color: #000;
      text-decoration-thickness: 1px;
      text-underline-offset: 0.25rem;
      transition: 0.4s ease-in-out;
    }

    a:hover,
    a:focus {
      color: unset;
      text-decoration-color: transparent;
    }

    h1 {
      background-color: var(--color__white);
      text-align: center;
      line-height: 1.25;
      max-width: 750px;
      padding: 1rem;
      margin: 40px auto;
      border-radius: var(--br);
    }

    @font-face {
      font-family: "barrd-led";
      src: url("barrd-led.woff2") format("woff2");
      font-weight: normal;
      font-style: normal;
      font-display: swap;
    }

    #digital-clock .inner {
      background-color: var(--color__black);
      display: flex;
      align-items: center;
      justify-content: center;
      max-width: 50%;
      min-height: 9rem;
      margin: 0 auto;
      border-radius: var(--br);
      box-shadow: var(--bs);
    }
    @media (max-width: 768px) {
      #digital-clock .inner {
        max-width: 75%;
        min-height: 6rem;
      }
    }
    @media (max-width: 480px) {
      #digital-clock .inner {
        max-width: 90%;
        min-height: 4rem;
      }
    }

    #digital-clock .container {
      display: inline-block;
    }

    #digital-clock #clock {
      font-family: "barrd-led", Arial, Helvetica, sans-serif;
      font-size: clamp(1rem, 4vw, 2.5rem);
      line-height: 1;
      letter-spacing: 0.25em;
      color: #fff;
      text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #f09,
        0 0 82px #f09, 0 0 92px #f09, 0 0 102px #f09, 0 0 151px #f09;
    }

    #info {
      background-color: var(--color__white);
      text-align: center;
      max-width: 500px;
      padding: 1rem;
      margin: 40px auto;
      border-radius: var(--br);
    }

    noscript .text {
      background-color: var(--color__white);
      color: var(--color__red);
      text-align: center;
      max-width: 500px;
      padding: 1rem;
      margin: 40px auto;
      border-radius: var(--br);
    }
  </style>
</head>
<body>
  <noscript>
    <!--- Engage Cloaking
  </noscript>
  <section id="digital-clock">
    <div class="inner">
      <div class="container">
        <div id="clock"></div>
      </div>
    </div>
  </section>
  <noscript>
    Disengage Cloaking -->
  </noscript>
  <script>
    setInterval(function () {
      const time = getCurrentTime();
      document.getElementById("clock").innerText = time;
    }, 1000);

    function getCurrentTime() {
      const dateObj = new Date();
      const time = {
        hours: dateObj.getHours(),
        minutes: dateObj.getMinutes(),
        seconds: dateObj.getSeconds(),
      };

      // Prepend 0 to hours for double digits
      if (time.hours < 10) {
        time.hours = "0" + time.hours;
      }
      // Prepend 0 to Minutes for double digits
      if (time.minutes < 10) {
        time.minutes = "0" + time.minutes;
      }
      // Prepend 0 to Seconds for double digits
      if (time.seconds < 10) {
        time.seconds = "0" + time.seconds;
      }

      // Format clock time "HH:MM:SS"
      return time.hours + ":" + time.minutes + ":" + time.seconds;
    }
  </script>
</body>
</html>
















<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
<div align="center"><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=1000&size=50&duration=4986&pause=1000&color=00F781&background=0D111700&center=true&vCenter=true&width=1000&height=100&lines=🎲+WELCOME+TO+MY+GITHUB+PAGE+🎲" alt="Typing SVG" /></a><div>
<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
  
![](https://komarev.com/ghpvc/?username=biswajit-github-2022&color=dc143c)
  
<h1 align="center">Hi there 👋🏼 Biswajit Here !</h1>

  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
  
<h1> 👨🏼‍💻About Me :</h1>

◽ Im a Web Developer/Data Science Student💻

◽ Currently Learning  -Machine Learning , Time Series , Statistics , Big Data Technologies(Spark,Hadoop) <img src="" alt="" width="15px">

◽ Projects:<br>
<a href="https://github.com/biswajit-github-2022/RKMVERI_2ND/tree/main/class/ML/SS_assignments_1" target="blank_">Classifying HandWirtten Digit MNIST dataset using KNN </a><br>
<a href="https://github.com/biswajit-github-2022/RKMVERI_2ND/tree/main/class/ML/SS_assignments_2" target="blank_">Classifying satellite images in River and Non River class using NaiveBayes</a><br>
<a href="https://github.com/biswajit-github-2022/RKMVERI_2ND/tree/main/class/ML/SS_assignments_3" target="blank_">Using Preceptron Algorithm to Fit a line Between two linearly seperable data</a><br>
<a href="https://github.com/biswajit-github-2022/RKMVERI_2ND/tree/main/class/ML/SS_assignments_4" target="blank_">Using K-Means Clustering algo to create classes for Satellite images </a><br>
<a href="https://github.com/biswajit-github-2022/RKMVERI/tree/master/1st_sem_PAPERS_materials/STAT/EDA/EDA" target="blank_">Exploratory Data Analytics Using R on a Body Performance Dataset</a><br>

<a href="https://linkedin.com/in/biswajit-rana" target="blank_"><img align="center"
            src="https://upload.wikimedia.org/wikipedia/commons/8/81/LinkedIn_icon.svg"
            alt="biswajit-rana" height="30" width="40" /></a>
<a href="https://instagram.com/biswajit_0_0_" target="blank_"><img align="center"
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/600px-Instagram_logo_2022.svg.png"
            alt="biswajit_0_0_" height="30" width="32" /></a>
<a href="https://www.facebook.com/biswajitrana13/" target="blank_"><img align="center"
            src="https://cdn.usbrandcolors.com/images/logos/facebook-logo.svg"
            alt="biswajit_0_0_" height="33" width="40" /></a>
<a href="https://twitter.com/B_R_0_0" target="blank_"><img align="center"
            src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/x-social-media-logo-icon.png"
            alt="B_R_0_0" height="40" width="40" /></a>
<a href="https://leetcode.com/u/biswajit276/" target="blank_"><img align="center"
            src="https://assets.leetcode.com/static_assets/public/images/LeetCode_logo_rvs.png"
            alt="biswajit276" height="40" width="40" /></a>
<a href="https://discordapp.com/users/757970753605075124" target="blank_"><img align="center"
            src="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0a69f118df70ad7828d4_icon_clyde_blurple_RGB.svg"
            alt="biswajitrana" height="40" width="40" /></a>

 <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">

# 🎯Learned Skills :
  <div>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt=""> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" alt=""> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white" alt=""> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt=""> <img src="https://img.shields.io/badge/R-276DC3.svg?style=for-the-badge&logo=R&logoColor=white" alt="">
    
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt=""> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt=""> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt=""> <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Pug-FFF?style=for-the-badge&logo=pug&logoColor=A86454" alt="">
    
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt=""> <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt=""> <img src="https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white" alt=""> <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt=""> <img src="https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white" alt="">
 
  <img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white" alt=""> <img src="https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="">

  <img src="https://img.shields.io/badge/MongoDB-47A248.svg?style=for-the-badge&logo=MongoDB&logoColor=white" alt=""> <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Oracle-F80000.svg?style=for-the-badge&logo=Oracle&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927.svg?style=for-the-badge&logo=Microsoft-SQL-Server&logoColor=white" alt=""> <img src="https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=PostgreSQL&logoColor=white" alt="">

  <img src="https://img.shields.io/badge/Blender-F5792A.svg?style=for-the-badge&logo=Blender&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Postman-FF6C37.svg?style=for-the-badge&logo=Postman&logoColor=white" alt=""> <img src="https://img.shields.io/badge/VSCodium-2F80ED.svg?style=for-the-badge&logo=VSCodium&logoColor=white" alt=""> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=for-the-badge&logo=IntelliJ-IDEA&logoColor=white" alt="">

  <img src="https://img.shields.io/badge/Kali%20Linux-557C94.svg?style=for-the-badge&logo=Kali-Linux&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Ubuntu-E95420.svg?style=for-the-badge&logo=Ubuntu&logoColor=white" alt=""> <img src="https://img.shields.io/badge/Windows%2011-0078D4.svg?style=for-the-badge&logo=Windows-11&logoColor=white" alt="">
<div/>
    
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
<!-- # ⏳📈 My Stats : -->
 
# ⏳<img src="https://camo.githubusercontent.com/93b08cf9dfcbf01a8306ebc9b8acd61b0f4fbd9d2fb7cece3d6dbd6a56060c19/68747470733a2f2f692e696d6775722e636f6d2f5943773437446d2e676966" alt="">⏳
  
 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=biswajit-github-2022&layout=compact&theme=jolly)](https://github.com/anuraghazra/github-readme-stats)
  
 [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=biswajit-github-2022&theme=monokai&background=000000)](https://git.io/streak-stats)
  
  
  ![Biswajit's GitHub stats](https://github-readme-stats.vercel.app/api?username=biswajit-github-2022&theme=aura&show_icons=true)
    
   <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
    
 # 🏆GitHub Trophies :
    
<img src="https://github-profile-trophy.vercel.app/?username=biswajit-github-2022&theme=tokyonight&no-frame=true&row=1&&margin-w=30&no-bg=true">

<div align="center">
  
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">

  
  </div>
    
