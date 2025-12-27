<!-- The header GIF. You can find more on Giphy or Tenor by searching "coding" or "engineering". -->
<!-- <img align="right" alt="Coding GIF" width="400" src="https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif" /> -->

<!-- Cyberpunk Glitch Animation for Name -->
<style>
@keyframes glitch {
  0% { text-shadow: 1px 0 #00f, -1px 0 #f0f; }
  2% { text-shadow: 2px 0 #00f, -2px 0 #f0f; }
  4% { text-shadow: -1px 0 #00f, 1px 0 #f0f; }
  6% { text-shadow: -2px 0 #f0f, 2px 0 #00f; }
  8%, 100% { text-shadow: none; }
}
.glitch-name {
  display: inline-block;
  position: relative;
  animation: glitch 8s infinite;
  animation-delay: 2s;
}
.glitch-name::before,
.glitch-name::after {
  content: attr(data-text);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.glitch-name::before {
  animation: glitch-top 1s infinite;
  clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
  opacity: 0.8;
}
.glitch-name::after {
  animation: glitch-bottom 1.5s infinite;
  clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
  opacity: 0.8;
}
@keyframes glitch-top {
  0%, 100% { transform: translate(0); }
  33% { transform: translate(-1px, 1px); }
  66% { transform: translate(1px, -1px); }
}
@keyframes glitch-bottom {
  0%, 100% { transform: translate(0); }
  33% { transform: translate(1px, -1px); }
  66% { transform: translate(-1px, 1px); }
}
</style>

<!-- Main Introduction -->
<h1 align="left">Hi there 👋, I'm 
  <span class="glitch-name" data-text="Samson" style="color: #60a5fa; font-weight: bold;">Samson</span>
</h1>

<!-- A little bit about you. Use emojis to make it stand out! -->
<p align="left">
  I'm a third-year <strong style="color: #818cf8;">Electrical & Computer Engineering</strong> student exploring the intersection where hardware meets software to solve real-world challenges. Passionate about learning through building.
</p>

- 💭 Always exploring new ideas and skills in **embedded systems & IoT**
- 🤝 Looking to collaborate on **open-source projects related to IoT or educational tech**
- 📫 Contact: **[OKTSAM001@myuct.ac.za](mailto:OKTSAM001@myuct.ac.za)** or connect on **[LinkedIn](https://www.linkedin.com/in/samson-okuthe-641aa8265/)**

<br/>

<!-- Skills Section with Icons -->
<h3 align="left">My Skills & Tools:</h3>
<p align="left">
  <!-- Python -->
  <a href="https://www.python.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" />
  </a>
  <!-- Java -->
  <a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" />
  </a>
  <!-- Arduino -->
  <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/arduino-colored.svg" width="36" height="36" alt="Arduino" />
  </a>
  <!-- Git -->
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" />
  </a>
  <!-- Linux -->
  <a href="https://www.linux.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" />
  </a>
  <!-- C -->
  <a href="https://en.wikipedia.org/wiki/C_(programming_language)" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="36" height="36" alt="C" />
  </a>
  <!-- VHDL/FPGA -->
  <a href="https://en.wikipedia.org/wiki/VHDL" target="_blank" rel="noreferrer">
    <img src="https://img.icons8.com/color/48/000000/chip.png" width="36" height="36" alt="VHDL/FPGA" style="filter: hue-rotate(180deg);" />
  </a>
</p>

<!-- Optional: Subtle cyberpunk divider -->
<div align="center">
  <hr style="border: none; height: 1px; background: linear-gradient(90deg, transparent, #60a5fa, #a78bfa, #f472b6, transparent); margin: 2rem 0;" />
</div>

<!-- Optional minimal stats (if you want to add them back) -->
<!--
<h3 align="left">My GitHub Stats:</h3>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=0geder&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0geder&layout=compact&langs_count=8&theme=dracula"/>
</p>
-->
