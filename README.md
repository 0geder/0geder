<!-- ============================= -->
<!-- GitHub Profile README -->
<!-- Owner: Samson Okuthe -->
<!-- ============================= -->

<!-- Optional header GIF -->
<!--
<img align="right" alt="Coding GIF" width="380"
src="https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif" />
-->

<style>
@keyframes glitch {
  0% { text-shadow: 2px 0 #00f, -2px 0 #f0f; }
  2% { text-shadow: 3px 0 #00f, -3px 0 #f0f; }
  4% { text-shadow: -2px 0 #00f, 2px 0 #f0f; }
  6% { text-shadow: -3px 0 #f0f, 3px 0 #00f; }
  8%, 100% { text-shadow: none; }
}

.glitch-name {
  display: inline-block;
  position: relative;
  animation: glitch 4s infinite;
  animation-delay: 1.5s;
  font-weight: 800;
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
  clip-path: polygon(0 0, 100% 0, 100% 35%, 0 35%);
  opacity: 0.8;
}

.glitch-name::after {
  clip-path: polygon(0 65%, 100% 65%, 100% 100%, 0 100%);
  opacity: 0.8;
}
</style>

<h1 align="left">
  Hi there 👋, I'm
  <span class="glitch-name" data-text="Samson" style="color:#60a5fa;">
    Samson
  </span>
</h1>

<p align="left">
  I’m a third-year <strong>Electrical & Computer Engineering</strong> student
  exploring where hardware meets software to solve real-world challenges.
</p>

<ul>
  <li>💭 Exploring <strong>Embedded Systems, IoT, and FPGA design</strong></li>
  <li>🤝 Open to collaboration on educational tech & open-source projects</li>
  <li>📫 Reach me at <strong><a href="mailto:OKTSAM001@myuct.ac.za">OKTSAM001@myuct.ac.za</a></strong></li>
  <li>🔗 Connect on <strong><a href="https://www.linkedin.com/in/samson-okuthe-641aa8265/">LinkedIn</a></strong></li>
</ul>

<h3 align="left">Skills & Tools</h3>
<p align="left">
  ... (icons list here)
</p>

<h3 align="left">GitHub Stats</h3>
<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=0geder&show_icons=true&theme=dracula"
  />
</p>
