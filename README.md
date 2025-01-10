<h1 align="center">Hi 👋, I'm Vishwanath</h1>
<p align="center"><h3 align="center" style="color: blue;">A passionate developer and lifelong learner</h3>

<p align="center">
  <img src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="200" alt="Coding GIF" />
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&pause=1000&color=32A2F2&center=true&width=435&lines=Welcome+to+my+GitHub!;I+love+to+code+and;sleep+a+lot!+" alt="Typing SVG" />
</p>


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Vishwanath&label=Profile%20views&color=0e75b6&style=flat" alt="Vishwanath" />
  <img src="https://img.shields.io/github/followers/Vishwanath?label=Followers&style=social" alt="GitHub followers" />
</p>


---


🌟 **About Me**

- 🌱 I’m currently learning **Java and React.js**
- 📫 Reach me at **vishwahesamani@gmail.com**
- ⚡ Fun fact: I love coding and sleep!


---


💻 **Languages and Tools**

<table>
<tr>
<td>
<p align="center">
  <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo--v1.png" alt="Java" />
  <img src="https://img.icons8.com/color/48/000000/react-native.png" alt="React" />
  <img src="https://img.icons8.com/color/48/000000/javascript--v1.png" alt="JavaScript" />
  <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" alt="HTML5" />
  <img src="https://img.icons8.com/color/48/000000/css3.png" alt="CSS3" />
</p>
</tr>
</td>
</table>


---


📈 **GitHub Stats**

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Vishwanath&show_icons=true&theme=radical" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Vishwanath&theme=radical"
alt="GitHub Streak" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vishwanath&layout=compact&theme=radical" alt="Top Languages" />
</p>


---


🌐 **Connect with Me**

<table>
<tr>
<td>
<p align="center">
  <a href="mailto:vishwahesamani@gmail.com">
    <img align="center" src="https://img.icons8.com/color/48/000000/gmail-new.png" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/vishwanath-h-300b63251/">
    <img align="center" src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn" />
  </a>
<a
href="https://www.facebook.com/profile.php?id=100079006017428&mibextid=ZbWKwL">
<img align="center"
src="https://images.app.goo.gl/aoHenLy8hWFPMn3M9.png"
alt="Facebook"/>
</a>
</p>
</tr>
</td>
</table>


---


✨ **Special Thanks for Visiting!** ✨

# Welcome to My GitHub Profile!

<p align="center">
  <svg width="400" height="200" xmlns="http://www.w3.org/2000/svg">
    <rect x="50" y="50" width="300" height="100" fill="lightblue">
      <animate attributeName="x" from="50" to="150" dur="2s" repeatCount="indefinite" />
      <animate attributeName="fill" from="lightblue" to="lightgreen" dur="2s" repeatCount="indefinite" />
    </rect>
    <text x="70" y="120" font-size="20" fill="black">Hello, I'm Vishwanath!</text<p align="center">
  <img src="name: Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Runs daily at midnight UTC
  workflow_dispatch: # Allows manual triggering of the workflow

jobs:
  generate_snake:
    runs-on: ubuntu-latest

    steps:
      # Step 1: Checkout the repository
      - name: Checkout Repository
        uses: actions/checkout@v3

      # Step 2: Generate the Snake Animation
      - name: Generate Snake Animation
        uses: Platane/snk@v2
        with:
          github_user_name: Vishwanath # Replace this with your GitHub username
          outputs: dist/snake.svg

      # Step 3: Push the Snake Animation to the Repository
      - name: Push Snake Animation to Repository
        run: |
          mkdir -p assets
          mv dist/snake.svg assets/snake.svg
          git config --local user.email "github-actions[bot]@users.noreply.github.com"
          git config --local user.name "GitHub Actions"
          git add assets/snake.svg
          git commit -m "Update Snake Animation"
<svg width="100%" height="100" viewBox="0 0 1200 100" xmlns="http://www.w3.org/2000/svg">
  <path fill="#0099ff" d="M0 49L28 47.7C56 46.3 112 43.7 168 49.3C224 55 280 69 336 66.3C392 63.7 448 44.3 504 38.3C560 32.3 616 39.7 672 50.7C728 61.7 784 76.3 840 81.3C896 86.3 952 81.7 1008 78.7C1064 75.7 1120 74.3 1156 73.7L1200 73L1200 101L1156 101C1120 101 1064 101 1008 101C952 101 896 101 840 101C784 101 728 101 672 101C616 101 560 101 504 101C448 101 392 101 336 101C280 101 224 101 168 101C112 101 56 101 28 101L0 101Z" />
  <animate repeatCount="indefinite" attributeName="d" dur="5s" 
    values="
      M0 49L28 47.7C56 46.3 112 43.7 168 49.3C224 55 280 69 336 66.3C392 63.7 448 44.3 504 38.3C560 32.3 616 39.7 672 50.7C728 61.7 784 76.3 840 81.3C896 86.3 952 81.7 1008 78.7C1064 75.7 1120 74.3 1156 73.7L1200 73L1200 101L1156 101C1120 101 1064 101 1008 101C952 101 896 101 840 101C784 101 728 101 672 101C616 101 560 101 504 101C448 101 392 101 336 101C280 101 224 101 168 101C112 101 56 101 28 101L0 101Z;
      
      M0 35L28 38.7C56 42.3 112 49.7 168 55.3C224 61 280 65 336 63.3C392 61.7 448 54.3 504 52.3C560 50.3 616 53.7 672 62.7C728 71.7 784 86.3 840 87.3C896 88.3 952 75.7 1008 70.7C1064 65.7 1120 68.3 1156 69.7L1200 71L1200 101L1156 101C1120 101 1064 101 1008 101C952 101 896 101 840 101C784 101 728 101 672 101C616 101 560 101 504 101C448 101 392 101 336 101C280 101 224 101 168 101C112 101 56 101 28 101L0 101Z;
      
      M0 49L28 47.7C56 46.3 112 43.7 168 49.3C224 55 280 69 336 66.3C392 63.7 448 44.3 504 38.3C560 32.3 616 39.7 672 50.7C728 61.7 784 76.3 840 81.3C896 86.3 952 81.7 1008 78.7C1064 75.7 1120 74.3 1156 73.7L1200 73L1200 101L1156 101C1120 101 1064 101 1008 101C952 101 896 101 840 101C784 101 728 101 672 101C616 101 560 101 504 101C448 101 392 101 336 101C280 101 224 101 168 101C112 101 56 101 28 101L0 101Z;" 
  />
</svg>

          git push" />
</p>
