<!-- 🌟 TOP BANNER -->
<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f1020"/>
      <stop offset="50%" stop-color="#1b2550"/>
      <stop offset="100%" stop-color="#111827"/>
    </linearGradient>

    <!-- Moving light / shine -->
    <linearGradient id="shineGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="rgba(255,255,255,0)" />
      <stop offset="40%" stop-color="rgba(255,255,255,0.3)" />
      <stop offset="60%" stop-color="rgba(255,255,255,0.6)" />
      <stop offset="100%" stop-color="rgba(255,255,255,0)" />
      <animate attributeName="x1" values="-100%;100%" dur="6s" repeatCount="indefinite" />
      <animate attributeName="x2" values="0%;200%" dur="6s" repeatCount="indefinite" />
    </linearGradient>

    <!-- Main text gradient -->
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#60a5fa"/>
      <stop offset="50%" stop-color="#a855f7"/>
      <stop offset="100%" stop-color="#f97316"/>
    </linearGradient>

    <!-- Soft glow shadow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- 3D extrude effect -->
    <filter id="extrude">
      <feOffset dx="4" dy="4" in="SourceAlpha" result="off1"/>
      <feOffset dx="8" dy="8" in="SourceAlpha" result="off2"/>
      <feMerge>
        <feMergeNode in="off1"/>
        <feMergeNode in="off2"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="300" fill="url(#bgGradient)" />

  <!-- Animated shine bar -->
  <rect x="-200" y="0" width="400" height="300" fill="url(#shineGradient)" opacity="0.4">
    <animate attributeName="x" from="-400" to="1200" dur="6s" repeatCount="indefinite" />
  </rect>

  <!-- Floating container group -->
  <g filter="url(#glow)">
    <!-- Slight float animation -->
    <animateTransform attributeName="transform"
                      type="translate"
                      values="0 -4; 0 4; 0 -4"
                      dur="5s"
                      repeatCount="indefinite" />

    <!-- 3D Name -->
    <g filter="url(#extrude)">
      <!-- Back/extruded layer -->
      <text x="50%" y="48%" text-anchor="middle"
            font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
            font-size="64"
            fill="#020617" opacity="0.7">
        Sathya Kapaganthu
      </text>

      <!-- Front gradient layer -->
      <text x="50%" y="45%" text-anchor="middle"
            font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
            font-weight="800"
            font-size="64"
            fill="url(#textGradient)">
        Sathya Kapaganthu
      </text>
    </g>

    <!-- Subtitle (role) -->
    <text x="50%" y="62%" text-anchor="middle"
          font-family="system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
          font-size="26"
          fill="#cbd5f5"
          letter-spacing="3">
      TECHNICAL PROJECT MANAGER
      <animate attributeName="letter-spacing"
               values="2;6;2"
               dur="4s"
               repeatCount="indefinite" />
    </text>

    <!-- Small accent line under role -->
    <rect x="35%" y="66%" width="30%" height="2" rx="1"
          fill="url(#textGradient)">
      <animate attributeName="width"
               values="20%;32%;20%"
               dur="4s"
               repeatCount="indefinite" />
    </rect>
  </g>
</svg>


<h1 align="center">👋 Hi, I'm <span style="color:#ff7b54;">Sathya Kapaganthu</span></h1>
<h3 align="center">Technical Project Manager | IT Project & Program Delivery</h3>

<p align="center">
  <a href="https://github.com/<YOUR_GITHUB_USERNAME>">
    <img src="https://komarev.com/ghpvc/?username=<YOUR_GITHUB_USERNAME>&label=Profile%20Views&style=flat&color=blue" alt="Profile views" />
  </a>
  <a href="https://github.com/<YOUR_GITHUB_USERNAME>?tab=followers">
    <img src="https://img.shields.io/github/followers/<YOUR_GITHUB_USERNAME>?label=Followers&style=flat" alt="GitHub Followers" />
  </a>
  <a href="https://github.com/<YOUR_GITHUB_USERNAME>?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-Portfolio-blueviolet?style=flat&logo=github" alt="Projects" />
  </a>
  <img src="https://img.shields.io/badge/Role-Technical%20Project%20Manager-ff7b54?style=flat" alt="Role" />
</p>

---

## 🧑‍💼 About Me

I’m a **Technical Project Manager / IT Project Manager** with **9+ years** of experience delivering **fintech and healthcare IT** projects across cloud, APIs, and enterprise platforms.

- 🚀 Lead cross-functional teams (engineering, QA, product, business)
- 📈 Drive end-to-end delivery, timelines, and stakeholder communication
- ☁️ Comfortable working with **AWS / Azure**, APIs, and data tools
- 📊 Use **data-driven decision making** with SQL, Excel, Power BI & Tableau
- 🎯 Certified **PMP** with strong Agile (Scrum, Kanban, SAFe) background

---

## 🧰 Tech & Tools

### 📋 Project & Delivery

- Jira • Confluence • Asana • Trello • Monday.com • MS Project • Slack

### 🧠 Methodologies

- Agile (Scrum, Kanban, SAFe) • SDLC • Risk & Dependency Management • Release Planning

### 🧑‍💻 Technical & Data

- Cloud: **AWS, Azure**  
- Data: **SQL, Excel, Power BI, Tableau**  
- Web basics: **HTML, CSS, JavaScript**  
- Integration: **APIs, Web Services, ETL**

---

## 💼 Experience Snapshot

### 🔹 Technical Project Manager – Mastercard
- Managing cloud-based, secure payment platforms
- Coordinating multi-team delivery across engineering, QA, infra & business
- Improving system reliability, scalability, and compliance

### 🔹 Project Manager – Centene (Healthcare)
- Led healthcare modernization initiatives
- Streamlined delivery processes and defect triage
- Improved cross-team communication and reporting

### 🔹 Associate PM / BA – Charter, NY State Dept of Taxation, MaxisIT
- Managed feature delivery, sprints, releases, and change requests
- Prepared BRDs, FRDs, user stories, acceptance criteria
- Worked closely with dev, QA, and operations

---

## 🎓 Education & Certification

- 🎓 **Master’s in Finance**, University of Bridgeport  
- 🎓 **Bachelor’s in Accounts**, Osmania University  
- 🏅 **PMP – Project Management Professional**

---

## 🌐 Portfolio Website

My interactive portfolio website showcases:

- 🎨 Modern, minimal UI with **3D WebGL / Three.js** background  
- 🧊 Animated **icosahedron** & particle field  
- 💬 Built-in **chatbot assistant** answering FAQs about my skills, roles & education  
- 📱 Responsive layout for desktop & mobile  

🔗 **Live Demo:** _Add your portfolio URL here_  
💻 **Source Code:** This repository’s `index.html`

---

## 🖼️ Live Demo Screenshots

> Place your screenshots in an `assets/` folder and update the paths below.

<p align="center">
  <a href="https://sathyakapaganthu.vercel.app/" target="_blank">
    <img src="./assets/dashboard.png" alt="Portfolio Homepage" width="45%" />
  </a>
</p>


---

## 📊 GitHub Analytics

> Replace `<YOUR_GITHUB_USERNAME>` with your actual GitHub username.

<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api?username=<YOUR_GITHUB_USERNAME>&show_icons=true&theme=radical" 
    alt="GitHub Stats" 
    height="160"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=<YOUR_GITHUB_USERNAME>&layout=compact&theme=radical" 
    alt="Top Languages" 
    height="160"
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-streak-stats.herokuapp.com/?user=<YOUR_GITHUB_USERNAME>&theme=radical" 
    alt="GitHub Streak" 
    height="160"
  />
</p>

---

## 📫 Contact

- 📍 Saint Louis, MO  
- 📧 **deepthi.ks93@gmail.com**  
- 🔗 **LinkedIn:** [Sathya Kapaganthu](https://www.linkedin.com/in/sathya-kapaganthu-bbb236a0/)  

---

## ⭐ Support

If you like this portfolio or my work:

- ⭐ Star this repo  
- 🔁 Share with your network  
- 🤝 Connect with me on LinkedIn  

> _“I bridge the gap between complex engineering and business value through structured delivery, clear communication, and accountable leadership.”_
