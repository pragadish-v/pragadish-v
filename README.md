from pathlib import Path
import pypandoc

content = r'''# Hi there, I'm Pragadish 👋

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:61DAFB,100:47A248&height=220&section=header&text=Pragadish%20V&fontSize=42&fontColor=ffffff"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&center=true&width=700&lines=Full-Stack+MERN+Developer;Data+Science+Enthusiast;B.Tech+CSE+Student;Always+Learning+Something+New"/>
</p>

## 🚀 About Me

- 🎓 B.Tech CSE @ Easwari Engineering College
- 📍 Chennai, India
- 💻 MERN Stack Developer
- 📊 Learning Data Science & Machine Learning
- 🌱 Practicing DSA daily
- 🤝 Open to internships and collaborations

## 🎯 Current Focus

- Build production-ready MERN applications
- Strengthen DSA
- Learn ML fundamentals
- Contribute to Open Source

## 🛠 Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,java,cpp,js,html,css,react,nodejs,express,mongodb,mysql,git,github,vscode,postman,linux&theme=dark"/>
</p>

## 📊 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=pragadish-v&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pragadish-v&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=pragadish-v&theme=tokyonight&hide_border=true"/>
</p>

## 📈 Activity Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=pragadish-v&theme=tokyo-night&hide_border=true"/>
</p>

## 🐍 Contribution Snake

<p align="center">
<img src="https://raw.githubusercontent.com/pragadish-v/pragadish-v/output/github-contribution-grid-snake-dark.svg"/>
</p>

## 📌 Featured Projects

| Project | Description |
|---------|-------------|
| 🚀 Nexora | MERN Ecommerce Platform |
| 🌏 South India Travel | Travel Website |
| 🛒 MyShop | E-commerce Application |
| 🧮 Calculator | JavaScript Calculator |
| 💼 CodeAlpha Tasks | Internship Projects |

## 🏆 Achievements

- 🥇 FedEx Hackathon (IIT Madras)
- 🤖 AI Wars
- 🎯 Convolve 4.0
- 💻 110+ LeetCode Problems
- 🚀 CodeAlpha Full Stack Internship

## 🤝 Connect

<p align="center">
<a href="https://github.com/pragadish-v"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://linkedin.com/in/pragadish-v"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail"/></a>
</p>

---

<p align="center">
⭐ If you like my work, consider starring my repositories!
</p>
'''
path="/mnt/data/README.md"
Path(path).write_text(content,encoding="utf-8")
print(path)
