<div align="center">
  
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&random=false&width=500&lines=Hey+there!+I'm+Abhay+%F0%9F%91%8B;Full+Stack+Developer;Fitness+Tech+Enthusiast;Open+Source+Contributor" alt="Typing SVG" />
  
  <img src="https://komarev.com/ghpvc/?username=Abhay1Sharma&style=for-the-badge&color=blue" alt="Profile Views" />
  
</div>

## 🚀 About Me

```mermaid
graph LR
    A[Abhay Sharma] --> B{Passionate About}
    B --> C[Full Stack Dev]
    B --> D[Fitness Tech]
    B --> E[Open Source]
    B --> F[DSA & Algorithms]
    
    C --> G[React/Node.js]
    D --> H[FindBuddy App]
    E --> I[Contributions]
    F --> J[Problem Solving]
<table align="center"> <tr> <td align="center"> <img src="https://img.shields.io/badge/Current_Project-FindBuddy-2E9EF7?style=for-the-badge&logo=github&logoColor=white" /> <br /> <span>Social platform for fitness enthusiasts</span> </td> <td align="center"> <img src="https://img.shields.io/badge/Learning-MERN_Stack-61DAFB?style=for-the-badge&logo=react&logoColor=white" /> <br /> <span>Mastering full-stack development</span> </td> </tr> <tr> <td align="center"> <img src="https://img.shields.io/badge/Seeking-Collaboration-00C853?style=for-the-badge&logo=opensourceinitiative&logoColor=white" /> <br /> <span>Open source projects</span> </td> <td align="center"> <img src="https://img.shields.io/badge/Available_For-Technical_Discussions-FF6B6B?style=for-the-badge&logo=stackoverflow&logoColor=white" /> <br /> <span>Full-stack, Java, Fitness-tech</span> </td> </tr> </table>
🔥 Tech Stack
<div align="center">
Frontend
<img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap" />
Backend
<img src="https://skillicons.dev/icons?i=nodejs,express,java,python" />
Database & Tools
<img src="https://skillicons.dev/icons?i=mongodb,mysql,git,github,vite" /></div>
📊 GitHub Analytics
<div align="center"> <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Abhay1Sharma&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=2E9EF7&icon_color=2E9EF7" /> <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhay1Sharma&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=2E9EF7" /> </div><div align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abhay1Sharma&theme=radical&hide_border=true&background=0D1117&ring=2E9EF7&fire=2E9EF7&currStreakLabel=2E9EF7" /> </div>
🏆 GitHub Trophies
<div align="center"> <img src="https://github-profile-trophy.vercel.app/?username=Abhay1Sharma&theme=radical&no-frame=true&row=1&column=6&margin-w=15" /> </div>
📈 Activity Graph
https://github-readme-activity-graph.vercel.app/graph?username=Abhay1Sharma&bg_color=0D1117&color=2E9EF7&line=2E9EF7&point=FFFFFF&area=true&hide_border=true

🎯 Current Focus
const abhay = {
  learning: ["System Design", "Advanced React Patterns", "Microservices"],
  building: "FindBuddy - Social Fitness Platform",
  goals: ["Contribute to OSS", "Write Technical Blogs", "Mentor Junior Devs"],
  funFact: "🏋️‍♂️ I code better after a good workout!"
};

🤝 Connect With Me
<div align="center">
https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white
https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white

</div>
💡 Featured Project
<div align="center"> <a href="https://github.com/Abhay1Sharma/FindBuddy"> <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=Abhay1Sharma&repo=FindBuddy&theme=radical&hide_border=true&bg_color=0D1117" /> </a> </div>
<div align="center"> <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />
💻 Code. 💪 Fitness. 🚀 Build.
"Making the world healthier, one line of code at a time"

</div><!-- Snake animation -->
https://github.com/Abhay1Sharma/Abhay1Sharma/blob/output/github-contribution-grid-snake.svg


## 🎨 Enhanced Features Added:

1. **Typing Animation**: Dynamic text animation using `readme-typing-svg`
2. **Mermaid Diagram**: Visual representation of your skills and interests
3. **Interactive Badges**: Modern-looking badges with icons
4. **Skill Icons**: Professional tech stack icons using `skillicons.dev`
5. **Enhanced Stats**: Better formatted GitHub stats with custom colors
6. **Activity Graph**: Visual contribution timeline
7. **Trophy Showcase**: GitHub achievement trophies
8. **Featured Project**: Pinned repository with custom styling
9. **Inspirational Quotes**: Random developer quotes
10. **Snake Animation**: Fun contribution graph animation

## 📝 Setup Instructions:

1. **Create Repository**: Create a repository named `Abhay1Sharma` (exactly your GitHub username)
2. **Copy Content**: Copy the above code to your `README.md` file
3. **Enable Snake Animation**: 
   - Create a GitHub Action workflow to generate snake animation
   - Add this to `.github/workflows/snake.yml`:

```yaml
name: Generate snake animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        with:
          github_user_name: Abhay1Sharma
          svg_out_path: dist/github-contribution-grid-snake.svg
          
      - uses: actions/upload-artifact@v2
        with:
          name: snake-animation
          path: dist
          
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./dist
