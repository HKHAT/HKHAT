<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=180&section=header&text=El%20Mehdi%20Chakir&fontSize=42&fontColor=58a6ff&animation=twinkling&fontAlignY=32&desc=Software%20Engineer%20%7C%20Systems%20Architect%20%7C%2042%20Graduate" width="100%" />

<!-- Typing Effect -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=58a6ff&center=true&vCenter=true&random=false&width=600&lines=Backend+%26+Systems+Engineering;C%2B%2B+%7C+Node.js+%7C+Docker+%7C+Three.js;Low-Level+Memory+Management+%7C+UNIX+Internals;Build+Clean+%7C+Scale+Smart+%7C+Ship+Fast" alt="Typing SVG" />

<!-- 42 Badge -->
<a href="https://github.com/oakoudad/badge42"><img src="https://badge.mediaplus.ma/black/elchakir" alt="42 stats badge" /></a>

</div>

---

### 👨‍💻 About Me
I am a software engineer who operates comfortably at both ends of the tech stack—from designing scalable backend architectures to manipulating raw memory and UNIX processes in C/C++. I build systems that prioritize performance, security, and clean architecture.

### 🛠️ Tech Stack
<p>
  <img src="https://skillicons.dev/icons?i=cpp,c,js,ts,nodejs,express,threejs,docker,nginx,postgres,redis,linux,bash,git&theme=dark" />
</p>

---

## 🚀 Featured Full-Stack Projects

> ### 🎮 [ft_transcendence](https://github.com/HKHAT/ft_transcendence) — 3D Multiplayer Ludo Platform
> Full-stack real-time web application featuring a 3D Ludo game via Three.js, WebSocket multiplayer architecture, heuristic AI agents, and social features (chat, friends, leaderboards).
> <p align="right"><code>Node.js</code> <code>Three.js</code> <code>WebSockets</code> <code>JWT</code></p>

> ### 🌐 [TaskFlow API](https://github.com/HKHAT/taskflow) — Secure REST Infrastructure
> A highly structured REST API featuring JWT authentication, real-time WebSocket integrations, strict data validation, and clean architectural separation.
> <p align="right"><code>Express.js</code> <code>TypeScript</code> <code>Postgres</code></p>

> ### 💻 [Webserv](https://github.com/HKHAT/webserv) — Custom HTTP Server (C++98)
> An Nginx-inspired HTTP server built from scratch. Handles non-blocking I/O, multiplexing (epoll/kqueue), robust request parsing, and CGI execution under strict C++98 constraints.
> <p align="right"><code>C++</code> <code>Sockets</code> <code>UNIX</code></p>

> ### 🐳 [Inception](https://github.com/HKHAT/inception) — Docker Infrastructure
> Automated deployment of a secure multi-container environment (Nginx, WordPress, MariaDB, Redis) featuring custom Dockerfiles, TLS encryption, and isolated volume management.
> <p align="right"><code>Docker</code> <code>Nginx</code> <code>TLS</code></p>

---

## 🖥️ 42 Core Curriculum (Low-Level Systems)

<details>
  <summary><b>⚙️ View Systems & Algorithmic Projects (C / C++)</b></summary>
  <br>
  <i>A deep dive into computer science fundamentals: memory management, UNIX processes, 3D math, and concurrency. No frameworks. Just raw engineering.</i>

  <table>
    <tr>
      <td valign="top" width="50%">
        
**🪈 Push_swap**
<div align="right">
  <a href="https://z-cdn-media.chatglm.cn/files/7e2a40a7-8208-410f-94b4-09e1ad157234.png?auth_key=1877612236-075766cd04ed491a9ba01efd674099f0-0-67a5eade2ff27e019f044ffd5aed2aae">
    <img src="https://z-cdn-media.chatglm.cn/files/7e2a40a7-8208-410f-94b4-09e1ad157234.png?auth_key=1877612236-075766cd04ed491a9ba01efd674099f0-0-67a5eade2ff27e019f044ffd5aed2aae" width="120" />
  </a>
</div>
Implemented the **Turk Algorithm** to sort a stack of 500 integers in < 4,900 operations. Utilizes indexing, cost-variable calculation, and overlapping simultaneous rotations (`rr`/`rrr`) to achieve maximum optimization.

<br><br>

**🪈 Pipex**
<div align="right">
  <a href="https://z-cdn-media.chatglm.cn/files/8ed1046b-3ad6-4d35-906a-42ccc48b5468.png?auth_key=1877613305-d6114281f97a4c34adb2ee89919ab913-0-14f62f97817269e67a67f015c7b166d1">
    <img src="https://z-cdn-media.chatglm.cn/files/8ed1046b-3ad6-4d35-906a-42ccc48b5468.png?auth_key=1877613305-d6114281f97a4c34adb2ee89919ab913-0-14f62f97817269e67a67f015c7b166d1" width="120" />
  </a>
</div>
Recreated the shell pipe operator (`|`) from scratch. Mastered UNIX Inter-Process Communication using `pipe()`, `fork()`, `dup2()`, and File Descriptor manipulation to chain infinite commands safely.

      </td>
      <td valign="top" width="50%">

**🐚 Minishell**
<div align="right">
  <a href="https://z-cdn-media.chatglm.cn/files/0a205c72-b247-4d89-8830-886824f854f4.png?auth_key=1877614457-51749c6be1824fcf9f90d80da060c374-0-b7174ddd8b38d332a6555b30dc59cecf">
    <img src="https://z-cdn-media.chatglm.cn/files/0a205c72-b247-4d89-8830-886824f854f4.png?auth_key=1877614457-51749c6be1824fcf9f90d80da060c374-0-b7174ddd8b38d332a6555b30dc59cecf" width="120" />
  </a>
</div>
A fully functional Bash clone. Built a custom Lexer/Parser state machine, handled complex infinite piping, Here-Docs (`<<`), and built-in execution paths. Engineered an anti-leak system to pass AddressSanitizer (ASAN) flawlessly during `SIGINT` interrupts.

<br><br>

**🖥️ Born2beroot**
<div align="right">
  <img src="https://img.shields.io/badge/Virtualization-LVM_Encrypted-9cf?style=flat-square" />
</div>
System administration project featuring Debian hardening. Implemented LVM encrypted partitioning, strict AppArmor/Sudo policies, UFW firewall configuration, and automated system monitoring via `cron`.

      </td>
    </tr>
    <tr>
      <td valign="top">

**🕹️ Cub3D**
<div align="right">
  <a href="https://z-cdn-media.chatglm.cn/files/ddc409a6-b2b5-435b-9625-bb1e83c8e9cb.png?auth_key=1877615749-de408ad51a5943dfb0379325a6a469b7-0-086de5abd009aa8e3b78b48848090dab">
    <img src="https://z-cdn-media.chatglm.cn/files/ddc409a6-b2b5-435b-9625-bb1e83c8e9cb.png?auth_key=1877615749-de408ad51a5943dfb0379325a6a469b7-0-086de5abd009aa8e3b78b48848090dab" width="120" />
  </a>
</div>
A real-time 3D raycasting engine. Engineered the mathematical foundation using the DDA algorithm, perpendicular distance calculations to prevent fisheye distortion, and XPM texture mapping without OpenGL.

      </td>
      <td valign="top">

**🍝 Philosophers**
<div align="right">
  <a href="https://z-cdn-media.chatglm.cn/files/06d809d3-31a0-4937-aae0-dcf1a65b5673.png?auth_key=1877616963-5ce693b135f8483d82bcf9af00b72268-0-b758a4523505160529c2eb5acd7e5396">
    <img src="https://z-cdn-media.chatglm.cn/files/06d809d3-31a0-4937-aae0-dcf1a65b5673.png?auth_key=1877616963-5ce693b135f8483d82bcf9af00b72268-0-b758a4523505160529c2eb5acd7e5396" width="120" />
  </a>
</div>
Solved the classic concurrency problem using multithreading (`pthread`) and multiprocessing (`fork`). Prevented deadlocks via asymmetric resource allocation and managed microsecond-precise state monitoring with `mmap` shared memory.

      </td>
    </tr>
  </table>
</details>

---

## 🧩 Object-Oriented Architecture (C++ Modules)

<details>
  <summary><b>📚 View C++ Paradigm Shift (CPP 00 ➔ 09)</b></summary>
  <br>
  <img src="https://z-cdn-media.chatglm.cn/files/96dca04c-8ab0-4778-b99f-950876695dda.png?auth_key=1877618134-e8dc3b7211ee4b988d60bfb27ed3b6a4-0-62a4c0c3f1bc31a0d7b6d2d01e107ab4" width="100" align="right" alt="OOP"/>
  
  A rigorous transition from Procedural C to strict C++98/03 paradigms, focusing on robust architecture over syntax.
  * **Orthodoxy & Encapsulation (00-02):** Mastered the Rule of Three, RAII, operator overloading, and `new`/`delete` memory control.
  * **Hierarchies & Abstraction (03-04):** Implemented Subtype Polymorphism via Virtual Tables and designed strict Abstract Interfaces.
  * **Resilience & Safety (05-06):** Replaced error codes with structured Exception Handling and enforced type safety using explicit C++ casts.
  * **Generic Programming (07-09):** Built custom Templated Containers, designed the Iterator pattern, and implemented the highly complex **Ford-Johnson (Merge-Insert)** sorting algorithm to minimize CPU comparisons.
</details>

---

<div align="center">

## 📊 Analytics & Activity

<img src="https://github-readme-stats.vercel.app/api?username=HKHAT&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HKHAT&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="170" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=HKHAT&theme=tokyonight&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff" width="600"/>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
<br>

### 📫 Connect
<a href="http://linkedin.com/in/el-chakir"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:elchakirmehdi@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="mailto:elchakir@student.1337.ma"><img src="https://img.shields.io/badge/1337_Email-000000?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br><br>
<i>"Build systems that scale. Engineer experiences that engage."</i>

</div>
