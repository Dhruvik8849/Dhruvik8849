<p align="center">
  <a href="https://github.com/Dhruvik8849">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=6A5ACD&height=200&section=header&text=Dhruvik%20%7C%20CSE%20@%20MNIT&fontSize=36&fontColor=ffffff" alt="header" />
  </a>
</p>

<div align="center">
  <h1>Backend & Systems Developer</h1>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2200&pause=800&color=6A5ACD&center=true&width=700&lines=Crafting+Reliable+Systems+%26+Backend+Architectures;Clean+Code+%7C+Performance+%7C+Scalability;Always+Learning%2C+Always+Building" alt="typing" />
</div>

---

## 👋 About Me
Hi — I'm **Dhruvik** (3rd year, CSE @ MNIT Jaipur). I build reliable backend systems, care deeply about clean architecture and performance, and love low-level systems & crypto experiments.

---

<div align="center">
  <!-- Social badges -->
  <a href="https://github.com/Dhruvik8849"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/dhruvik8849"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/Dhruvik_MYI/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
</div>

---

### 🧠 Current Focus
- Advanced DSA & problem patterns  
- Modern C++ (STL internals, memory models)  
- Backend engineering (auth, caching, DB indexing, Redis)  
- Practical cryptography (implementations & protocols)

### ⚡ Core Interests
Systems programming · Distributed systems · Database design · Clean architecture

---

## 🛠 Tech & Tools
<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,py,js,ts,nodejs,express,mongodb,postgres,redis,linux,docker,git,github,bash,cmake&perline=12&theme=dark" alt="skills"/>
</p>

---

## 🌗 Auto Dark/Light GitHub Stats & Top Languages
<div align="center">
  <!-- Dark / Light versions (auto by GitHub CSS selectors) -->
  <p>
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=Dhruvik8849&show_icons=true&count_private=true&hide_border=true&theme=react#gh-dark-mode-only" alt="gh-stats-dark"/>
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=Dhruvik8849&show_icons=true&count_private=true&hide_border=true&theme=default#gh-light-mode-only" alt="gh-stats-light"/>
  </p>
  <p>
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dhruvik8849&layout=compact&hide_border=true&theme=react&langs_count=6#gh-dark-mode-only" alt="langs-dark"/>
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dhruvik8849&layout=compact&hide_border=true&theme=default&langs_count=6#gh-light-mode-only" alt="langs-light"/>
  </p>
</div>

---

## 🔭 Currently Building
<!-- Simple progress badge (edit percentage manually) -->
<p align="center">
  <img src="https://img.shields.io/badge/Currently_Building-Auth%20System%20API-6A5ACD?style=for-the-badge" alt="building"/>
  <img src="https://img.shields.io/badge/Progress-45%25-yellow?style=for-the-badge" alt="progress"/>
</p>

---

## 💼 Mini Portfolio — Pinned Work
<p align="center">
  <a href="https://github.com/Dhruvik8849/Login-Auth-System"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Dhruvik8849&repo=Login-Auth-System&theme=react&hide_border=true" width="45%" alt="Login-Auth-System"/></a>
  <a href="https://github.com/Dhruvik8849/SnakeGame-Python"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Dhruvik8849&repo=SnakeGame-Python&theme=react&hide_border=true" width="45%" alt="SnakeGame"/></a>
</p>
<p align="center">
  <a href="https://github.com/Dhruvik8849/Crypto-Lab"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Dhruvik8849&repo=Crypto-Lab&theme=react&hide_border=true" width="48%" alt="Crypto-Lab"/></a>
</p>

---

## 🏗️ How to add a 3D GitHub contribution graph (quick)
You can generate a 3D model / skyline or an SVG of your contribution calendar using an Action or a small script. Two popular options:

- `github-profile-3d-contrib` — GitHub Action / repo that generates a 3D-style contribution visualization and commits it to your repo (you can add it as a workflow). :contentReference[oaicite:5]{index=5}  
- `gh-skyline` / GitHub Skyline clones — many community projects (and demos) produce a 3D skyline from contributions; they can be run locally or hosted. :contentReference[oaicite:6]{index=6}

**Example (workflow snippet) — place this in `.github/workflows/3d-contrib.yml`:**

```yaml
name: Generate 3D contribution
on:
  workflow_dispatch:
  schedule:
    - cron: '0 4 * * *' # runs daily at 04:00 UTC, change as you like

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate 3D contrib (example)
        uses: yoshi389111/github-profile-3d-contrib@v0.8.0
        with:
          gh_token: ${{ secrets.GITHUB_TOKEN }}
          username: Dhruvik8849
          output_path: "./contrib-3d"   # example output folder
