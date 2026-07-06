<!-- ============================================================ -->
<!-- CUSTOM ANIMATED SVG BANNER (PURE SVG, NO EXTERNAL API)       -->
<!-- ============================================================ -->
<div align="center">
  <svg width="100%" height="300" viewBox="0 0 900 300" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <animate attributeName="x1" values="0%;100%;0%" dur="8s" repeatCount="indefinite" />
        <animate attributeName="y1" values="0%;100%;0%" dur="8s" repeatCount="indefinite" />
        <stop offset="0%" stop-color="#0d0221"/>
        <stop offset="50%" stop-color="#150734"/>
        <stop offset="100%" stop-color="#0d0221"/>
      </linearGradient>
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feComposite in="SourceGraphic" in2="blur" operator="over"/>
      </filter>
    </defs>

    <!-- Dynamic Background -->
    <rect width="900" height="300" fill="url(#bgGrad)" />

    <!-- Floating Particles -->
    <circle cx="100" cy="50" r="2" fill="#61DAFB" opacity="0.6">
      <animateTransform attributeName="transform" type="translate" values="0,0;80,60;0,120;0,0" dur="14s" repeatCount="indefinite" />
    </circle>
    <circle cx="800" cy="200" r="3" fill="#7928CA" opacity="0.5">
      <animateTransform attributeName="transform" type="translate" values="0,0;-100,-50;0,-100;0,0" dur="10s" repeatCount="indefinite" />
    </circle>
    <circle cx="450" cy="150" r="1.5" fill="#FF0080" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" values="0,0;50,-30;0,-60;0,0" dur="12s" repeatCount="indefinite" />
    </circle>
    <circle cx="250" cy="250" r="2" fill="#00DFD8" opacity="0.4">
      <animateTransform attributeName="transform" type="translate" values="0,0;-40,20;0,40;0,0" dur="9s" repeatCount="indefinite" />
    </circle>

    <!-- Animated Grid Lines -->
    <path d="M 0 150 L 900 150" stroke="#61DAFB" stroke-width="0.5" opacity="0.15">
      <animateTransform attributeName="transform" type="translate" values="0,0;0,300;0,0" dur="20s" repeatCount="indefinite" />
    </path>
    <path d="M 450 0 L 450 300" stroke="#7928CA" stroke-width="0.5" opacity="0.15">
      <animateTransform attributeName="transform" type="translate" values="0,0;900,0;0,0" dur="20s" repeatCount="indefinite" />
    </path>

    <!-- Pulsing Central Glow -->
    <circle cx="450" cy="120" r="60" fill="none" stroke="#61DAFB" stroke-width="1" opacity="0.4" filter="url(#glow)">
      <animate attributeName="r" values="60;80;60" dur="3s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3s" repeatCount="indefinite" />
    </circle>

    <!-- Name with Glow Pulse -->
    <text x="450" y="120" font-family="'Fira Code', monospace" font-size="48" font-weight="bold" fill="white" text-anchor="middle" filter="url(#glow)">
      Jubayer 🚀
      <animate attributeName="opacity" values="1;0.7;1" dur="2s" repeatCount="indefinite" />
    </text>

    <!-- Typing Subtitle (fade in + blinking cursor) -->
    <text x="450" y="160" font-family="'Fira Code', monospace" font-size="18" fill="#61DAFB" text-anchor="middle" opacity="0.9">
      Machine Learning • Computer Vision • Full-Stack AI
      <animate attributeName="opacity" values="0;0.9;0.9" dur="3s" begin="0s" fill="freeze" />
    </text>

    <!-- Blinking Cursor -->
    <rect x="447" y="165" width="10" height="3" fill="#FF0080">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
    </rect>

    <!-- Decorative Animated Bar -->
    <rect x="250" y="200" width="400" height="2" fill="url(#bgGrad)" opacity="0.5">
      <animate attributeName="width" values="400;800;400" dur="5s" repeatCount="indefinite" />
    </rect>
  </svg>
</div>

<!-- Profile Views -->
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=jubayer032003&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />
</p>

<!-- Dynamic Typing Animation -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=23&pause=1000&color=61DAFB&center=true&vCenter=true&width=700&lines=👋+Hello,+World!+I'm+Jubayer;🧠+AI+%26+Deep+Learning+Engineer;👁️+Computer+Vision+%26+Medical+Image+Processing;⚡+Building+Full-Stack+FastAPI+%2B+React+AI+Apps;📊+Explainable+AI+(SHAP)+System+Architect" alt="Typing SVG" />
  </a>
</p>

<!-- Live Badges -->
<p align="center">
  <a href="https://github.com/jubayer032003">
    <img src="https://img.shields.io/github/followers/jubayer032003?label=Followers&style=for-the-badge&color=7928CA&logo=github&logoColor=white" alt="GitHub Followers">
  </a>
  &nbsp;
  <a href="https://github.com/jubayer032003?tab=repositories">
    <img src="https://img.shields.io/github/stars/jubayer032003?label=Total%20Stars&style=for-the-badge&color=FF0080&logo=github&logoColor=white" alt="GitHub Stars">
  </a>
  &nbsp;
  <a href="https://github.com/jubayer032003?tab=repositories">
    <img src="https://img.shields.io/badge/Status-Active-00DFD8?style=for-the-badge&logo=git&logoColor=white" alt="Active Status">
  </a>
</p>

<br />

<!-- Trophies -->
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=jubayer032003&theme=tokyonight&column=7&margin-w=10&margin-h=10&no-bg=true" width="100%" alt="Trophies" />
</div>

<br />

---

## 🧠 About Me & Specialization

<table border="0">
  <tr>
    <td width="60%" valign="top">
      <h3>👨‍💻 Who I Am</h3>
      <p>
        I am a <b>Computer Vision & Machine Learning Developer</b> passionate about turning complex algorithms into production-ready, interactive web applications.
      </p>
      <p>
        My core expertise spans <b>Deep Learning (CNNs, MobileNet, Transfer Learning)</b>, <b>Medical AI Diagnostics</b>, and <b>Explainable AI (SHAP)</b>. I bridge backend data pipelines with modern frontend interfaces to build transparent, decision-ready AI applications.
      </p>
      <ul>
        <li>🔬 <b>Primary Focus</b>: Computer Vision, Medical Risk Prediction & XAI</li>
        <li>💻 <b>Stack</b>: Python, TensorFlow, PyTorch, OpenCV, Scikit-Learn, FastAPI, React 19</li>
        <li>🎯 <b>Current Goal</b>: Architecting scalable, interpretable AI systems for healthcare & CV</li>
      </ul>
    </td>
    <td width="40%" align="center" valign="top">
      <h3>📈 Language Distribution</h3>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jubayer032003&layout=donut&theme=tokyonight&hide_border=true&title_color=61DAFB&icon_color=7928CA" width="100%" alt="Language Donut" />
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack & Ecosystem

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Artificial Intelligence & DL** | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" /> <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /> |
| **Computer Vision & IP** | <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/Pillow-000000?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Haar--Cascade-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/LBPH-222222?style=for-the-badge" /> |
| **Data Science & XAI** | <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/SHAP-Explainable_AI-7928CA?style=for-the-badge" /> |
| **Full-Stack & APIs** | <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> |
| **Dev Tools** | <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" /> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" /> <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" /> |

</div>

---

## 🌟 Featured Repositories (Live Preview)

<div align="center">

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <h3>🫀 Heart Failure Prediction AI</h3>
      <a href="https://github.com/jubayer032003/Heart-Failure-Prediction-AI">
        <img src="https://opengraph.githubassets.com/1/jubayer032003/Heart-Failure-Prediction-AI" width="100%" alt="Repo preview" />
      </a>
      <p>Full‑stack AI medical dashboard with FastAPI, React 19 & SHAP XAI.</p>
      <p>
        <img src="https://img.shields.io/github/stars/jubayer032003/Heart-Failure-Prediction-AI?style=flat-square&color=009688" />
        <img src="https://img.shields.io/github/forks/jubayer032003/Heart-Failure-Prediction-AI?style=flat-square&color=009688" />
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>🐶🐱 Cat & Dog Transfer Learning</h3>
      <a href="https://github.com/jubayer032003/Cat-and-Dog-classification-using-Transfer-Learning">
        <img src="https://opengraph.githubassets.com/1/jubayer032003/Cat-and-Dog-classification-using-Transfer-Learning" width="100%" alt="Repo preview" />
      </a>
      <p>Binary classifier using MobileNet (96%+ accuracy) with transfer learning.</p>
      <p>
        <img src="https://img.shields.io/github/stars/jubayer032003/Cat-and-Dog-classification-using-Transfer-Learning?style=flat-square&color=FF6F00" />
        <img src="https://img.shields.io/github/forks/jubayer032003/Cat-and-Dog-classification-using-Transfer-Learning?style=flat-square&color=FF6F00" />
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>🚀 OpenCV Master Notes</h3>
      <a href="https://github.com/jubayer032003/OpenCV_Note_By_Jubayer">
        <img src="https://opengraph.githubassets.com/1/jubayer032003/OpenCV_Note_By_Jubayer" width="100%" alt="Repo preview" />
      </a>
      <p>Complete CV guide: transformations, filtering, Haar Cascades & LBPH.</p>
      <p>
        <img src="https://img.shields.io/github/stars/jubayer032003/OpenCV_Note_By_Jubayer?style=flat-square&color=5C3EE8" />
        <img src="https://img.shields.io/github/forks/jubayer032003/OpenCV_Note_By_Jubayer?style=flat-square&color=5C3EE8" />
      </p>
    </td>
  </tr>
</table>

</div>

---

## 📊 Live Real‑Time GitHub Analytics

<div align="center">

<p>
  <img width="400" src="https://github-readme-stats.vercel.app/api?username=jubayer032003&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=61DAFB&icon_color=7928CA&border_radius=10" alt="GitHub Stats" />
  <img width="400" src="https://github-readme-streak-stats.herokuapp.com/?user=jubayer032003&theme=tokyonight&hide_border=true&background=1a1b26&ring=61DAFB&fire=FF0080&border_radius=10" alt="GitHub Streak" />
</p>

<!-- Advanced Profile Summary -->
<p>
  <img width="820" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jubayer032003&theme=tokyonight" alt="Profile Details" />
</p>

<!-- Animated Contribution Activity Graph -->
<p>
  <img width="860" src="https://github-readme-activity-graph.vercel.app/graph?username=jubayer032003&theme=tokyo-night&hide_border=true&area=true" alt="Activity Graph" />
</p>

<!-- ============================================================ -->
<!-- ANIMATED CONTRIBUTION SNAKE (requires one-time GitHub Action) -->
<!-- ============================================================ -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jubayer032003/jubayer032003/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jubayer032003/jubayer032003/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/jubayer032003/jubayer032003/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

## 💬 Developer Inspiration

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="100%" alt="Dev Quote" />
</div>

<br />

---

## 📫 Connect & Collaborate

<p align="center">
  <a href="https://github.com/jubayer032003">
    <img src="https://img.shields.io/badge/GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:jubayer032003@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<!-- Footer Waving Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,25,45,65,90&height=120&section=footer" width="100%" />
</p>
