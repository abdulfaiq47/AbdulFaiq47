# 👋 Hi, I'm Abdul Faiq
### 🧱 HTML & CSS Code---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Embedded + Backup</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
    }

    /* iframe full screen */
    iframe {
      width: 100vw;
      height: 100vh;
      border: none;
    }

    /* fallback box */
    #fallback {
      position: absolute;
      top: 0;
      left: 0;
      width: 40vw;          /* adjust width */
      height: 25vh;         /* your 25vh height */
      background: #f7fbff;
      border: 2px solid #0f172a;
      display: none;
      overflow: hidden;
    }

    /* smaller version of your design */
    #fallback iframe {
      width: 100%;
      height: 100%;
      border: none;
      transform: scale(0.45);
      transform-origin: top left;
    }
  </style>
</head>
<body>
  <!-- Main iframe -->
  <iframe id="main" src="https://abdulfaiq47.github.io/AbdulFaiq47/" onerror="showFallback()"></iframe>

  <!-- Fallback content -->
  <div id="fallback">
    <!-- your coder illustration -->
    <iframe srcdoc='
    <!doctype html>
    <html lang="en">
    <head>
    <meta charset="utf-8">
    <style>
      body{margin:0;background:#f7fbff;}
      .code-window{background:#232f4c;color:#fff;border-radius:12px;padding:18px;width:100%;height:100%;}
      .c1{width:50%;height:12px;background:#f59e0b;margin:8px 0;border-radius:8px;}
      .c2{width:40%;height:12px;background:#60a5fa;margin:8px 0;border-radius:8px;}
      .c3{width:30%;height:12px;background:#fb7185;margin:8px 0;border-radius:8px;}
    </style>
    </head>
    <body>
      <div class="code-window">
        <div class="c1"></div>
        <div class="c2"></div>
        <div class="c3"></div>
      </div>
    </body>
    </html>'>
    </iframe>
  </div>

  <script>
    // If main iframe fails, show fallback box
    function showFallback() {
      document.getElementById('fallback').style.display = 'block';
    }

    // Also show fallback if iframe doesn’t load within a few seconds
    setTimeout(() => {
      const iframe = document.getElementById('main');
      if (!iframe.contentWindow || iframe.contentWindow.location.href === 'about:blank') {
        showFallback();
      }
    }, 5000);
  </script>
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
