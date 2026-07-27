<!-- Animated Header -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:006B3F,100:00C853&height=200&section=header&text=Nisal%20Wijethunga&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>

</div>


<div align="center">

# 👋 Hi, I'm Nisal Wijethunga

### 🚀  Software Engineer | Full Stack Developer 

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00C853&center=true&vCenter=true&width=600&lines=React+%7C+Next.js+%7C+Node.js+Developer;React+Native+Mobile+App+Developer;MERN+Stack+Enthusiast;Building+Scalable+Software+Solutions" />

</div>


---

## 👨‍💻 About Me

const nisal = {
    role: "Software Engineer",
    education: "BSc (Hons) Computer Science",
    university: "NSBM Green University",
    
    interests: [
        "Full Stack Development",
        "Mobile Applications",
        "Cloud Technologies",
        "Artificial Intelligence"
    ],

    currentStack: [
        "React",
        "Next.js",
        "Node.js",
        "TypeScript",
        "MongoDB"
    ],

    goal: "Building impactful software solutions 🚀"
};>

🛠 Tech Stack
<div align="center">
Frontend
<img src="https://skillicons.dev/icons?i=react,next,typescript,javascript,html,css,tailwind,bootstrap" />
Backend
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,spring,java" />
Database & Cloud
<img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,firebase,aws,gcp,docker" />
Tools
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,linux" /> </div>

🚀 Featured Projects

📱 UniLEARN - Student Learning Management System
<img align="right" width="250" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif">

React Native LMS application built for university students.

Features

✅ JWT Authentication
✅ Course Management
✅ Assignment Tracking
✅ Exam Schedule
✅ REST API Integration
✅ Responsive Mobile UI

Tech:

React Native • Expo • TypeScript • AsyncStorage

<br clear="right"/>

🛡 Sarani - Pathway To Safety

Crime Reporting & Evidence Management Platform.

Features:

Citizen crime reporting
GPS location tracking
Police administration system
ML-based crime analysis
Evidence chain management

Tech:

MERN Stack • NestJS • MongoDB • Machine Learning

📊 GitHub Analytics
<div align="center"> <img height="180" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true"/> <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true"/> </div>

🔥 Contribution Streak
<div align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true"/> </div>

🐍 Contribution Snake Animation
<div align="center"> <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg"/> </div>

🏆 Achievements & Certifications
<a href="https://www.credly.com/badges/ee1f6acd-3676-4f98-9956-125d38936d80/public_url">
<img src="https://images.credly.com/size/220x220/images/af8c6b4e-fc31-47c4-8dcb-eb7a2065dc5b/I2CS__1_.png" width="120"/>
</a> 
<a href="https://www.credly.com/badges/2b39c232-d7b5-4fd4-a9c9-d5274bb1eea2/public_url">
<img src="https://images.credly.com/size/220x220/images/7b08cc0e-064b-407d-b70e-323509c3e474/blob" width="120"/>
</a> 
<a href="https://www.credly.com/badges/9cf98224-08ba-4b56-ae52-89eeb5def32a/public_url">
<img src="https://images.credly.com/size/220x220/images/f5095707-7683-4886-940c-3e8e4a2085ca/blob" width="120"/>
</a> 
<a href="https://www.credly.com/badges/84006517-3c72-406e-b8e0-3e13a86a3987/public_url">
<img src="https://images.credly.com/size/680x680/images/3b1b42e6-dfc2-492b-90df-8058096cb93d/blob" width="120"/>
</a> 
<a href="https://www.credly.com/badges/b642ea91-149f-49b7-88ad-813ad25eb7f9/public_url">
<img src="https://images.credly.com/size/680x680/images/e51a8579-188d-4363-8ed1-12ad164ef57b/blob" width="120"/>
</a> 

📫 Connect With Me
<div align="center"> <a href="https://linkedin.com/in/https://www.linkedin.com/in/nisal-wijethunge/"> <img src="https://skillicons.dev/icons?i=linkedin"/> </a> <a href="mailto:nisalwijethunge@gmail.com"> <img src="https://skillicons.dev/icons?i=gmail"/> </a> </div>

<div align="center">
⭐ Thanks for visiting my profile!
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:006B3F,100:00C853&height=120&section=footer"/> </div> ```

.github/workflows/snake.yml

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  snake:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
