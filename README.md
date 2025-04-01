<div align="center">
  <svg viewBox="0 0 720 120" style="max-width: 720px; width: 100%; height: auto;">
    <style>
      @keyframes drop {
        0% { opacity: 0; transform: translateY(-30px); }
        100% { opacity: 1; transform: translateY(0); }
      }
      .cyber-text {
        font: 600 42px 'Courier New', monospace;
        fill: #0ff;
        text-shadow: 0 0 10px #0ff;
        animation: drop 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
        opacity: 0;
      }
      .cyber-text:hover {
        filter: url(#glitch);
      }
    </style>
    <filter id="glitch">
      <feTurbulence type="fractalNoise" baseFrequency="0.01" numOctaves="1" result="warp"/>
      <feDisplacementMap xChannelSelector="R" yChannelSelector="G" scale="10" in="SourceGraphic" in2="warp"/>
    </filter>
    
    <!-- Name with staggered animation -->
    <text x="50" y="50" class="cyber-text" style="animation-delay: 0.1s">H</text>
    <text x="75" y="50" class="cyber-text" style="animation-delay: 0.2s">A</text>
    <text x="100" y="50" class="cyber-text" style="animation-delay: 0.3s">R</text>
    <text x="125" y="50" class="cyber-text" style="animation-delay: 0.4s">S</text>
    <text x="150" y="50" class="cyber-text" style="animation-delay: 0.5s">H</text>
    <text x="175" y="50" class="cyber-text" style="animation-delay: 0.6s">A</text>
    <text x="225" y="50" class="cyber-text" style="animation-delay: 0.7s">L</text>
    <text x="250" y="50" class="cyber-text" style="animation-delay: 0.8s">A</text>
    <text x="275" y="50" class="cyber-text" style="animation-delay: 0.9s">K</text>
    <text x="300" y="50" class="cyber-text" style="animation-delay: 1.0s">S</text>
    <text x="325" y="50" class="cyber-text" style="animation-delay: 1.1s">H</text>
    <text x="350" y="50" class="cyber-text" style="animation-delay: 1.2s">A</text>
    <text x="375" y="50" class="cyber-text" style="animation-delay: 1.3s">N</text>
    <text x="450" y="50" class="cyber-text" style="animation-delay: 1.4s">(</text>
    <text x="475" y="50" class="cyber-text" style="animation-delay: 1.5s">L</text>
    <text x="500" y="50" class="cyber-text" style="animation-delay: 1.6s">A</text>
    <text x="525" y="50" class="cyber-text" style="animation-delay: 1.7s">-</text>
    <text x="550" y="50" class="cyber-text" style="animation-delay: 1.8s">X</text>
    <text x="575" y="50" class="cyber-text" style="animation-delay: 1.9s">-</text>
    <text x="600" y="50" class="cyber-text" style="animation-delay: 2.0s">A</text>
    <text x="625" y="50" class="cyber-text" style="animation-delay: 2.1s">N</text>
    <text x="650" y="50" class="cyber-text" style="animation-delay: 2.2s">)</text>
  </svg>

  <!-- Tech Stack Grid -->
  <div align="center" style="margin-top: 30px;">
    <div style="display: grid; grid-template-columns: repeat(5, 1fr); gap: 15px; max-width: 600px;">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" style="animation: scaleIn 0.5s ease-out 2.5s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" style="animation: scaleIn 0.5s ease-out 2.7s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" style="animation: scaleIn 0.5s ease-out 2.9s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" style="animation: scaleIn 0.5s ease-out 3.1s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" style="animation: scaleIn 0.5s ease-out 3.3s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" style="animation: scaleIn 0.5s ease-out 3.5s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" style="animation: scaleIn 0.5s ease-out 3.7s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" style="animation: scaleIn 0.5s ease-out 3.9s forwards; opacity: 0;">
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" style="animation: scaleIn 0.5s ease-out 4.1s forwards; opacity: 0;">
    </div>
  </div>
</div>

<style>
  @keyframes scaleIn {
    from { transform: scale(0); opacity: 0; }
    to { transform: scale(1); opacity: 1; }
  }
</style>

![Visitor Count](https://visitor-badge.glitch.me/badge?page_id=La-x-aN.La-x-aN)
