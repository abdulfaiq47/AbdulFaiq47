# 👋 Hi, I'm Abdul Faiq
### 🧱 HTML & CSS Code

html
<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Coder Illustration (HTML/CSS recreation)</title>
  <style>
    :root {
      --bg: #f7fbff;
      --card: #ffffff;
      --muted: #b7c7d6;
      --accent-1: #3b82f6;
      --accent-2: #10b981;
      --accent-3: #f43f5e;
      --dark: #0f172a;
    }

    * {
      box-sizing: border-box
    }

    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      background: var(--bg);
      color: var(--dark);
    }

    .stage {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 48px
    }

    .card {
      width: 980px;
      max-width: 95%;
      background: linear-gradient(180deg, #fff 0%, #f9fdff 100%);
      border-radius: 20px;
      padding: 42px;
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: 28px;
      align-items: center;
      box-shadow: 0 10px 30px rgba(15, 23, 42, 0.08)
    }

    .left {
      display: flex;
      flex-direction: column;
      gap: 20px
    }

    .code-window {
      background: #232f4c;
      color: #fff;
      border-radius: 12px;
      padding: 18px;
      box-shadow: 0 6px 18px rgba(2, 6, 23, 0.2);
      width: 30%;
      max-width: 560px;
      position: fixed;
      top: 118px;
    }

    .code-row {
      height: 12px;
      border-radius: 8px;
      margin: 8px 0
    }

    .c1 {
      width: 50%;
      background: #f59e0b;
    }

    .c2 {
      width: 40%;
      background: #60a5fa
    }

    .c3 {
      width: 30%;
      background: #fb7185
    }

    .avatar-wrap {
      display: flex;
      gap: 24px;
      align-items: center
    }

    .right {
      display: flex;
      flex-direction: column;
      gap: 18px;
      align-items: flex-end
    }

    .tag {
      padding: 12px 18px;
      border-radius: 12px;
      font-weight: 700;
      color: #fff;
      box-shadow: 0 6px 18px rgba(2, 6, 23, 0.06)
    }

    .tag.js {
      background: var(--accent-2);
      position: fixed;
      top: 3px;
      right: 300px;
      width: 64px;
      font-size: x-large;
      height: 56px;
    }

    .tag.html {
      background: var(--accent-1);
      position: fixed;
      top: 79px;
      right: 135px;
      width: 103px;
      font-size: x-large;
      height: 55px;
    }

    .tag.css {
      background: var(--accent-3);
      position: fixed;
      top: 169px;
      right: 124px;
      width: 78px;
      font-size: x-large;
      height: 59px;
    }

    .panel {
      background-color: #0f172a;
      color: white;
      position: fixed;
      top: 252px;
      right: 55px;
      width: 145px;
      border-radius: 10px;
      height: 98px;
      padding: 12px;
    }

    .panel-line {
      height: 8px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 6px;
      margin: 8px 0
    }

    .text-block video {
      height: 330px;
      position: fixed;
      top: 77px;
      left: 166px;
    }
  </style>
</head>

<body>
  <div class="stage">
    <div class="card">
      <div class="left">
        <div class="code-window">
          <div class="code-row c1"></div>
          <div class="code-row c2"></div>
          <div class="code-row c3"></div>
        </div>

        <div class="avatar-wrap">
          <div class="text-block">
            <video autoplay loop muted playsinline width="400">
              <source src="anim.mp4" type="video/mp4">
            </video>
          </div>
          <img src="lap.png" alt="">
        </div>
      </div>

      <div class="right">
        <div class="tag js">JS</div>
        <div class="tag html">HTML</div>
        <div class="tag css">CSS</div>

        <div class="panel">
          <div class="panel-line"></div>
          <div class="panel-line" style="width:85%"></div>
          <div class="panel-line" style="width:60%"></div>
          <div class="panel-line" style="width:92%"></div>
        </div>
      </div>
    </div>
  </div>
</body>

</html>



### 🚀 About Me
- 🌱 Currently learning and exploring advanced backend and cloud deployment.
- 💡 I love turning ideas into interactive, high-performance web solutions.
- ⚡ Always eager to learn and contribute to open-source projects.
- 💬 Ask me about **React, Node.js, MongoDB, Express, and Next.js**.

---

### 🧰 Tech Stack
> *(You can add your badges or tools here later)*  
> Example:
> ![React](https://img.shields.io/badge/-React-61DBFB?style=flat&logo=react&logoColor=white)
> ![Node.js](https://img.shields.io/badge/-Node.js-3C873A?style=flat&logo=node.js&logoColor=white)
> ![MongoDB](https://img.shields.io/badge/-MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
> ![Express](https://img.shields.io/badge/-Express-black?style=flat&logo=express&logoColor=white)

---

<h3 align="left">Languages and Tools:</h3>
<p align="left">
  <!-- HTML -->
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
  </a>
  
  <!-- CSS -->
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  </a>
  
  <!-- JavaScript -->
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  </a>
  
  <!-- ReactJS -->
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  </a>
  
  <!-- NodeJS -->
  <a href="https://nodejs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  </a>
  
  <!-- ExpressJS -->
  <a href="https://expressjs.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/>
  </a>
  
  <!-- MongoDB -->
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
  </a>
  
  <!-- NextJS -->
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/>
  </a>
  
  <!-- Postman -->
  <a href="https://postman.com" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
  </a>
  
  <!-- Python -->
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  </a>
  
  <!-- Pandas -->
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
  </a>
  
  <!-- Seaborn -->
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer">
    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/>
  </a>
  
  <!-- NumPy -->
  <a href="https://numpy.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original-wordmark.svg" alt="numpy" width="40" height="40"/>
  </a>
  
  <!-- Django -->
  <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/>
  </a>
</p>


---
### 📫 Connect With Me
- 📧 Email: Abdulfaiq47@gmail.com


---

### 🧠 Fun Fact
> “The best way to predict the future is to build it.”

---

⭐️ From [Abdul Faiq](https://github.com/AbdulFaiq47)
