<!--
✨ HANDCRAFTED 2026 GITHUB PROFILE LANDING PAGE
🎨 DESIGN LANGUAGE: VERCEL × LINEAR × APPLE
🦾 DEVELOPER: ABHAY SHANKER TIWARI
-->

<div align="center">
  <!-- Glowing Interactive Tech Banner -->
  <svg width="100%" height="320" viewBox="0 0 900 320" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Background Gradient -->
      <linearGradient id="bg-grad" x1="0" y1="0" x2="900" y2="320" gradientUnits="userSpaceOnUse">
        <stop stop-color="#020204"/>
        <stop offset="0.5" stop-color="#0a071b"/>
        <stop offset="1" stop-color="#010103"/>
      </linearGradient>
      
      <!-- Neon Glowing Auras -->
      <radialGradient id="aurora-purple" cx="150" cy="100" r="250" gradientUnits="userSpaceOnUse">
        <stop stop-color="#a855f7" stop-opacity="0.25"/>
        <stop offset="1" stop-color="#a855f7" stop-opacity="0"/>
      </radialGradient>
      <radialGradient id="aurora-blue" cx="750" cy="220" r="300" gradientUnits="userSpaceOnUse">
        <stop stop-color="#3b82f6" stop-opacity="0.2"/>
        <stop offset="1" stop-color="#3b82f6" stop-opacity="0"/>
      </radialGradient>
      
      <!-- Perspective Grid -->
      <linearGradient id="grid-fade" x1="450" y1="0" x2="450" y2="320" gradientUnits="userSpaceOnUse">
        <stop stop-color="#000000" stop-opacity="1"/>
        <stop offset="0.3" stop-color="#000000" stop-opacity="0"/>
        <stop offset="0.8" stop-color="#1e1b4b" stop-opacity="0.15"/>
        <stop offset="1" stop-color="#7c3aed" stop-opacity="0.4"/>
      </linearGradient>

      <!-- Text Gradients -->
      <linearGradient id="text-grad" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse">
        <stop stop-color="#ffffff"/>
        <stop offset="0.5" stop-color="#cbd5e1"/>
        <stop offset="1" stop-color="#94a3b8"/>
      </linearGradient>
      <linearGradient id="sub-grad" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse">
        <stop stop-color="#a855f7"/>
        <stop offset="0.5" stop-color="#3b82f6"/>
        <stop offset="1" stop-color="#06b6d4"/>
      </linearGradient>

      <!-- Border Glow -->
      <linearGradient id="border-glow" x1="0" y1="0" x2="900" y2="320" gradientUnits="userSpaceOnUse">
        <stop stop-color="#7c3aed" stop-opacity="0.6"/>
        <stop offset="0.5" stop-color="#3b82f6" stroke-opacity="0.2"/>
        <stop offset="1" stop-color="#06b6d4" stop-opacity="0.5"/>
      </linearGradient>
    </defs>

    <!-- Background Base -->
    <rect width="900" height="320" rx="16" fill="url(#bg-grad)"/>
    
    <!-- Radial Neon Lights -->
    <circle cx="150" cy="100" r="250" fill="url(#aurora-purple)"/>
    <circle cx="750" cy="220" r="300" fill="url(#aurora-blue)"/>

    <!-- Perspective 3D Grid Pattern -->
    <g>
      <path d="M-100 320 L450 140 L1000 320 M-50 320 L450 140 L950 320 M0 320 L450 140 L900 320 M50 320 L450 140 L850 320 M100 320 L450 140 L800 320 M150 320 L450 140 L750 320 M200 320 L450 140 L700 320 M250 320 L450 140 L650 320 M300 320 L450 140 L600 320 M350 320 L450 140 L550 320 M400 320 L450 140 L500 320" stroke="url(#grid-fade)" stroke-width="1" />
      <path d="M 0,280 L 900,280 M 0,250 L 900,250 M 0,225 L 900,225 M 0,205 L 900,205 M 0,190 L 900,190 M 0,178 L 900,178 M 0,168 L 900,168 M 0,160 L 900,160 M 0,154 L 900,154" stroke="url(#grid-fade)" stroke-width="1" />
    </g>

    <!-- Premium Frame Border -->
    <rect x="1" y="1" width="898" height="318" rx="15" stroke="url(#border-glow)" stroke-width="1.5"/>

    <!-- Animated Glowing Network in Center Background -->
    <g transform="translate(450, 160)" opacity="0.35">
      <circle cx="0" cy="0" r="40" stroke="#7c3aed" stroke-width="1" stroke-dasharray="4 4" fill="none">
        <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite" />
      </circle>
      <circle cx="0" cy="0" r="80" stroke="#3b82f6" stroke-width="0.75" stroke-dasharray="8 8" fill="none">
        <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="25s" repeatCount="indefinite" />
      </circle>
      <!-- Core node -->
      <circle cx="0" cy="0" r="10" fill="url(#sub-grad)">
        <animate attributeName="r" values="8;13;8" dur="4s" repeatCount="indefinite" />
      </circle>
    </g>

    <!-- Typography Layout -->
    <!-- Monospace cyber label -->
    <text x="50" y="70" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="11" fill="#38bdf8" letter-spacing="3" opacity="0.8">
      SYSTEMS ORCHESTRATOR // SECURE IDENTITY // MACHINE INTELLIGENCE
    </text>

    <!-- Main Name Title -->
    <text x="50" y="130" font-family="'Space Grotesk', 'Inter', -apple-system, sans-serif" font-weight="900" font-size="52" fill="url(#text-grad)" letter-spacing="-1">
      ABHAY SHANKER TIWARI
    </text>
    
    <!-- Subtle gradient border line below title -->
    <rect x="50" y="152" width="220" height="2" fill="url(#sub-grad)" />

    <!-- Subtitle -->
    <text x="50" y="195" font-family="'Space Grotesk', 'Inter', -apple-system, sans-serif" font-weight="600" font-size="20" fill="#e2e8f0" letter-spacing="1">
      AI • Machine Learning • Computer Vision
    </text>

    <!-- Availability Capsule Badge -->
    <g transform="translate(50, 235)">
      <!-- Glass background -->
      <rect width="360" height="34" rx="17" fill="#0c0720" fill-opacity="0.6" stroke="#1e1b4b" stroke-width="1"/>
      <!-- Glowing green dot -->
      <circle cx="20" cy="17" r="4.5" fill="#10b981">
        <animate attributeName="opacity" values="1;0.4;1" dur="2s" repeatCount="indefinite" />
      </circle>
      <!-- Text -->
      <text x="35" y="21" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="12" fill="#a78bfa">
        STATUS: ACTIVE <tspan fill="#64748b">// OPEN FOR 2026 AI INTERNSHIPS</tspan>
      </text>
    </g>

    <!-- Futuristic HUD readout details on the right -->
    <g transform="translate(680, 50)" opacity="0.75" font-family="monospace" font-size="9" fill="#94a3b8">
      <text x="0" y="20">LOG: CLASSIFY_CORE [LOADED]</text>
      <text x="0" y="35">SYS: CV_ENGINE_ACTIVE [OK]</text>
      <text x="0" y="50">LOC: LUCKNOW, IN // UTC+5.5</text>
      <text x="0" y="65">ENV: PYTORCH | TENSORFLOW | C++</text>
      
      <!-- Cyber graph graphic -->
      <g transform="translate(0, 85)" stroke="#38bdf8" stroke-width="1.5" fill="none">
        <path d="M 0,40 L 20,30 L 40,35 L 60,10 L 80,25 L 100,5 L 120,12 L 140,2" />
        <line x1="0" y1="40" x2="140" y2="40" stroke="#1e293b" stroke-width="1" />
        <!-- glowing target dot -->
        <circle cx="140" cy="2" r="3" fill="#38bdf8" />
      </g>
    </g>
  </svg>

  <br/><br/>

  <!-- Interactive Typing Animation -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&weight=600&size=28&duration=3000&pause=1000&color=40B4FF&center=true&vCenter=true&width=900&lines=Engineering+AI+That+Solves+Real+Problems;Computer+Vision+%E2%80%A2+Machine+Learning+%E2%80%A2+Python;Building+Products%2C+Not+Just+Projects;Python+%E2%80%A2+TensorFlow+%E2%80%A2+OpenCV;Learning.+Building.+Shipping.;Turning+Ideas+into+Intelligent+Solutions;Always+Learning.+Always+Building.;Open+to+Collaborations+%26+Opportunities" alt="Typing SVG" />
  </a>

  <br/>

  <!-- Raycast-Style Quick Info Bar -->
  <svg width="100%" height="90" viewBox="0 0 900 90" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- Background -->
    <rect width="900" height="90" rx="10" fill="#070709" stroke="#1e293b" stroke-width="1.5" />
    
    <!-- Search Icon -->
    <g transform="translate(24, 32)" stroke="#94a3b8" stroke-width="2" fill="none">
      <circle cx="11" cy="11" r="7" />
      <line x1="16" y1="16" x2="22" y2="22" stroke-linecap="round" />
    </g>
    
    <!-- Search text placeholder -->
    <text x="60" y="49" font-family="'Inter', -apple-system, sans-serif" font-weight="500" font-size="15" fill="#e2e8f0">abhay --focus</text>
    <text x="165" y="49" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="15" fill="#475569">|</text>
    
    <!-- Tags on the right -->
    <g transform="translate(360, 30)">
      <!-- Tag 1: Education -->
      <rect x="0" y="0" width="160" height="30" rx="6" fill="#18181b" stroke="#27272a" stroke-width="1" />
      <text x="12" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="500" font-size="11" fill="#94a3b8">B.Tech CSE</text>
      <text x="85" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#71717a">@SRMCEM</text>
      <rect x="142" y="6" width="12" height="18" rx="3" fill="#27272a" />
      <text x="148" y="18" font-family="'Inter', -apple-system, sans-serif" font-weight="700" font-size="8" fill="#a1a1aa" text-anchor="middle">E</text>

      <!-- Tag 2: Domain -->
      <rect x="175" y="0" width="165" height="30" rx="6" fill="#1e1b4b" stroke="#311042" stroke-width="1" />
      <text x="187" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="500" font-size="11" fill="#c084fc">Computer Vision</text>
      <text x="285" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#a21caf">CV</text>
      <rect x="312" y="6" width="12" height="18" rx="3" fill="#4a044e" />
      <text x="318" y="18" font-family="'Inter', -apple-system, sans-serif" font-weight="700" font-size="8" fill="#f5d0fe" text-anchor="middle">C</text>

      <!-- Tag 3: Location -->
      <rect x="355" y="0" width="165" height="30" rx="6" fill="#022c22" stroke="#064e3b" stroke-width="1" />
      <text x="367" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="500" font-size="11" fill="#34d399">Lucknow, India</text>
      <text x="465" y="19" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#047857">IND</text>
      <rect x="492" y="6" width="12" height="18" rx="3" fill="#065f46" />
      <text x="498" y="18" font-family="'Inter', -apple-system, sans-serif" font-weight="700" font-size="8" fill="#d1fae5" text-anchor="middle">L</text>
    </g>
  </svg>

  <br/><br/>

  <!-- Stats view counts -->
  <img src="https://komarev.com/ghpvc/?username=mrgraciz123&label=⚡+Profile+Views&style=for-the-badge&color=7c3aed&labelColor=1e1b4b" alt="Profile Views" />

  <br/><br/>

  <!-- Social Link Buttons -->
  <p align="center">
    <a href="https://www.linkedin.com/in/abhay-shanker-tiwari-0a8031213/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="https://drive.google.com/file/d/1zsKdcm6g4JSWMf5P8ru5IfxCzRNUnefP/view?usp=sharing" target="_blank">
      <img src="https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=googledrive&logoColor=white&labelColor=27272a" alt="Resume Badge"/>
    </a>
    <a href="https://codeforces.com/profile/abhaylibra15" target="_blank">
      <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces Badge"/>
    </a>
    <a href="https://www.codechef.com/users/mr_graciz" target="_blank">
      <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef Badge"/>
    </a>
    <a href="https://x.com/mr_graciz" target="_blank">
      <img src="https://img.shields.io/badge/X.com-000000?style=for-the-badge&logo=x&logoColor=white" alt="X Badge"/>
    </a>
  </p>
</div>

---

## 💎 Executive Summary

<table width="100%" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td width="58%" valign="top">
      <p>I am <b>Abhay Shanker Tiwari</b>, a dedicated AI/ML engineer focused on building robust Computer Vision architectures and scalable deep neural networks.</p>
      <p>My academic foundation in Computer Science at SRMCEM drives me to engineer real-world systems, specializing in biometric identity platforms, real-time video perception, and optimization for low-latency client environments.</p>
      <ul>
        <li>🧬 <b>Neural Architecture:</b> Training custom models via PyTorch, TensorFlow, and optimizing weight pipelines.</li>
        <li>📷 <b>Computer Vision:</b> Object detection, face mesh tracking, segmentation, and live OpenCV pipelines.</li>
        <li>🌐 <b>API Backends:</b> Connecting ML models to high-frequency endpoints with FastAPI and secure architectures.</li>
      </ul>
    </td>
    <td width="4%"></td>
    <td width="38%" valign="top">
      <div align="right">
<pre lang="yaml" style="background: #070709; border: 1px solid #1e293b; padding: 16px; border-radius: 8px; font-size: 12px; color: #a78bfa; text-align: left; margin: 0; line-height: 1.6;">
<b>developer_profile:</b>
  name: "Abhay Shanker Tiwari"
  location: "Lucknow, India"
  education: "B.Tech CSE @ SRMCEM"
  core_stack:
    - Python [Primary]
    - PyTorch / TensorFlow
    - OpenCV [C++ / Python]
    - FastAPI / SQL
  focus_areas:
    - Artificial Intelligence
    - Computer Vision
    - Model Deployment
</pre>
      </div>
    </td>
  </tr>
</table>

---

## 🛠️ Infrastructure & Tech Stack Console

This console maps out the technology domains I configure to construct end-to-end machine learning infrastructure.

<div align="center">
  <svg width="100%" height="280" viewBox="0 0 900 280" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Border Gradient -->
      <linearGradient id="t-border" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
        <stop stop-color="#1e293b" />
        <stop offset="0.5" stop-color="#3b82f6" stop-opacity="0.3" />
        <stop offset="1" stop-color="#1e293b" />
      </linearGradient>
      
      <!-- Box Gradients -->
      <linearGradient id="box-grad-purple" x1="0" y1="0" x2="260" y2="200" gradientUnits="userSpaceOnUse">
        <stop stop-color="#1e1b4b" stop-opacity="0.7" />
        <stop offset="1" stop-color="#02010a" stop-opacity="0.95" />
      </linearGradient>
      <linearGradient id="box-grad-blue" x1="0" y1="0" x2="260" y2="200" gradientUnits="userSpaceOnUse">
        <stop stop-color="#0c2530" stop-opacity="0.7" />
        <stop offset="1" stop-color="#010408" stop-opacity="0.95" />
      </linearGradient>
      <linearGradient id="box-grad-green" x1="0" y1="0" x2="260" y2="200" gradientUnits="userSpaceOnUse">
        <stop stop-color="#022c22" stop-opacity="0.7" />
        <stop offset="1" stop-color="#000201" stop-opacity="0.95" />
      </linearGradient>
    </defs>

    <!-- Frame Background -->
    <rect width="900" height="280" rx="14" fill="#070709" stroke="url(#t-border)" stroke-width="1.5" />

    <!-- Grid Pattern -->
    <pattern id="t-grid" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="15" cy="15" r="1" fill="#ffffff" fill-opacity="0.04" />
    </pattern>
    <rect width="900" height="280" rx="14" fill="url(#t-grid)" />

    <!-- Connection circuit lines -->
    <path d="M 290,150 L 320,150" stroke="#3b82f6" stroke-opacity="0.2" stroke-width="1.5" fill="none" />
    <path d="M 580,150 L 610,150" stroke="#10b981" stroke-opacity="0.2" stroke-width="1.5" fill="none" />

    <!-- Card 1: Machine Learning Core (Purple) -->
    <g transform="translate(30, 40)">
      <rect width="260" height="200" rx="10" fill="url(#box-grad-purple)" stroke="#581c87" stroke-width="1.25" />
      <circle cx="20" cy="22" r="4" fill="#c084fc" />
      <text x="32" y="26" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="13" fill="#ffffff" letter-spacing="0.5">01 / NEURAL ENGINE</text>
      
      <g transform="translate(20, 50)" font-family="'Inter', -apple-system, sans-serif" font-size="11.5" line-height="2">
        <text x="0" y="15" fill="#cbd5e1" font-weight="600">TensorFlow &amp; Keras <tspan fill="#a78bfa" font-weight="400"> (Models)</tspan></text>
        <text x="0" y="38" fill="#cbd5e1" font-weight="600">PyTorch ecosystem <tspan fill="#a78bfa" font-weight="400"> (Deep Nets)</tspan></text>
        <text x="0" y="61" fill="#cbd5e1" font-weight="600">Scikit-Learn <tspan fill="#a78bfa" font-weight="400"> (ML Reg/Clust)</tspan></text>
        <text x="0" y="84" fill="#cbd5e1" font-weight="600">NumPy &amp; Pandas <tspan fill="#a78bfa" font-weight="400"> (Data Matrix)</tspan></text>
        <text x="0" y="107" fill="#cbd5e1" font-weight="600">Hyperparameters <tspan fill="#a78bfa" font-weight="400"> (Optimizations)</tspan></text>
      </g>
      <rect x="0" y="196" width="260" height="4" rx="2" fill="#a855f7" />
    </g>

    <!-- Card 2: Perception & Interfacing (Blue) -->
    <g transform="translate(320, 40)">
      <rect width="260" height="200" rx="10" fill="url(#box-grad-blue)" stroke="#0e7490" stroke-width="1.25" />
      <circle cx="20" cy="22" r="4" fill="#22d3ee" />
      <text x="32" y="26" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="13" fill="#ffffff" letter-spacing="0.5">02 / PERCEPTION &amp; API</text>
      
      <g transform="translate(20, 50)" font-family="'Inter', -apple-system, sans-serif" font-size="11.5">
        <text x="0" y="15" fill="#cbd5e1" font-weight="600">OpenCV Vision <tspan fill="#67e8f9" font-weight="400"> (C++/Python)</tspan></text>
        <text x="0" y="38" fill="#cbd5e1" font-weight="600">FastAPI framework <tspan fill="#67e8f9" font-weight="400"> (Microservices)</tspan></text>
        <text x="0" y="61" fill="#cbd5e1" font-weight="600">Firebase endpoints <tspan fill="#67e8f9" font-weight="400"> (Realtime Auth)</tspan></text>
        <text x="0" y="84" fill="#cbd5e1" font-weight="600">SQL &amp; Relational DB <tspan fill="#67e8f9" font-weight="400"> (MySQL Storage)</tspan></text>
        <text x="0" y="107" fill="#cbd5e1" font-weight="600">Video Processing <tspan fill="#67e8f9" font-weight="400"> (Live Streaming)</tspan></text>
      </g>
      <rect x="0" y="196" width="260" height="4" rx="2" fill="#06b6d4" />
    </g>

    <!-- Card 3: Execution & DevOps (Green) -->
    <g transform="translate(610, 40)">
      <rect width="260" height="200" rx="10" fill="url(#box-grad-green)" stroke="#065f46" stroke-width="1.25" />
      <circle cx="20" cy="22" r="4" fill="#34d399" />
      <text x="32" y="26" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="13" fill="#ffffff" letter-spacing="0.5">03 / SYSTEM RUNTIME</text>
      
      <g transform="translate(20, 50)" font-family="'Inter', -apple-system, sans-serif" font-size="11.5">
        <text x="0" y="15" fill="#cbd5e1" font-weight="600">Docker Virtualization <tspan fill="#6ee7b7" font-weight="400"> (Container)</tspan></text>
        <text x="0" y="38" fill="#cbd5e1" font-weight="600">Linux environments <tspan fill="#6ee7b7" font-weight="400"> (Bash Deploy)</tspan></text>
        <text x="0" y="61" fill="#cbd5e1" font-weight="600">C++ Programming <tspan fill="#6ee7b7" font-weight="400"> (Native Core)</tspan></text>
        <text x="0" y="84" fill="#cbd5e1" font-weight="600">Git versioning <tspan fill="#6ee7b7" font-weight="400"> (CI/CD workflows)</tspan></text>
        <text x="0" y="107" fill="#cbd5e1" font-weight="600">VS Code workspace <tspan fill="#6ee7b7" font-weight="400"> (Tooling Environment)</tspan></text>
      </g>
      <rect x="0" y="196" width="260" height="4" rx="2" fill="#10b981" />
    </g>
  </svg>
  
  <br/>
  <img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,opencv,fastapi,firebase,docker,git,github,vscode,linux,cpp,mysql" alt="Tech Icons Grid" />
</div>

---

## 🚀 Curation of Featured AI / ML Projects

These production-grade architectures demonstrate my implementation work in computer vision, statistical modeling, and deep classifier networks.

<!-- Glassmorphism Cards Grid Table -->
<table width="100%" border="0" cellpadding="0" cellspacing="10" style="border-collapse: separate; border-spacing: 10px;">
  <tr>
    <!-- Project Card 1: AscendID -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/AscendID" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c1-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#a855f7" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#3b82f6" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c1-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#a855f7" stop-opacity="0.15" />
              <stop offset="1" stop-color="#a855f7" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c1-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c1-glow)" />
          
          <!-- Security Face Mesh Icon Graphic -->
          <g transform="translate(320, 30)" opacity="0.65">
            <rect width="80" height="100" rx="8" fill="#181030" stroke="#a855f7" stroke-width="1" stroke-dasharray="2 2" />
            <circle cx="40" cy="35" r="4" fill="#3b82f6" />
            <circle cx="28" cy="45" r="3" fill="#a855f7" />
            <circle cx="52" cy="45" r="3" fill="#a855f7" />
            <circle cx="40" cy="55" r="3" fill="#a855f7" />
            <circle cx="40" cy="72" r="5" fill="#10b981" />
            <path d="M 40,35 L 28,45 L 40,55 L 52,45 L 40,35 M 40,55 L 40,72 M 28,45 L 40,72 M 52,45 L 40,72" stroke="#a855f7" stroke-width="0.75" fill="none" opacity="0.8" />
            <line x1="5" y1="20" x2="75" y2="20" stroke="#06b6d4" stroke-width="1.5">
              <animate attributeName="y1" values="10;90;10" dur="4s" repeatCount="indefinite"/>
              <animate attributeName="y2" values="10;90;10" dur="4s" repeatCount="indefinite"/>
            </line>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#a855f7" letter-spacing="1.5">IDENTITY ORCHESTRATOR</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">AscendID</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Biometric identity platform leveraging deep neural</tspan>
              <tspan x="0" dy="16">face-representations and custom secure REST APIs.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#1e1b4b" stroke="#3b0764" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#d8b4fe" text-anchor="middle">v1.2.0</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="25" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">PyTorch</text>
              <rect x="56" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="81" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">OpenCV</text>
              <rect x="112" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="137" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">FastAPI</text>
            </g>
          </g>
        </svg>
      </a>
    </td>

    <!-- Project Card 2: Gender Classification -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/gender-classification" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c2-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#06b6d4" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#3b82f6" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c2-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#06b6d4" stop-opacity="0.15" />
              <stop offset="1" stop-color="#06b6d4" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c2-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c2-glow)" />

          <!-- Face scanner viewfinder details -->
          <g transform="translate(325, 35)" opacity="0.65" stroke="#06b6d4" stroke-width="1.25" fill="none">
            <path d="M 10,10 L 2,10 L 2,18 M 70,10 L 78,10 L 78,18 M 10,90 L 2,90 L 2,82 M 70,90 L 78,90 L 78,82" />
            <path d="M 40,25 C 25,25 20,40 20,55 C 20,70 30,80 40,80 C 50,80 60,70 60,55 C 60,40 55,25 40,25 Z" stroke-width="1" />
            <line x1="36" y1="50" x2="44" y2="50" stroke-width="1" />
            <line x1="40" y1="46" x2="40" y2="54" stroke-width="1" />
            <text x="40" y="100" font-family="monospace" font-size="8" fill="#06b6d4" stroke="none" text-anchor="middle">MATCH 98.4%</text>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#06b6d4" letter-spacing="1.5">COMPUTER VISION CORE</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">Gender Classification</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Real-time facial detection and demographics estimation</tspan>
              <tspan x="0" dy="16">engine built utilizing deep learning classifiers and OpenCV.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#0c252a" stroke="#083344" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#22d3ee" text-anchor="middle">ACTIVE</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="25" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">OpenCV</text>
              <rect x="56" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="81" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Python</text>
              <rect x="132" width="60" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="162" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Deep Net</text>
            </g>
          </g>
        </svg>
      </a>
    </td>
  </tr>
  
  <tr>
    <!-- Project Card 3: Cat vs Dog Classifier -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/cat-vs-dog" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c3-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#3b82f6" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#1d4ed8" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c3-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#3b82f6" stop-opacity="0.15" />
              <stop offset="1" stop-color="#3b82f6" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c3-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c3-glow)" />

          <!-- Mock training loss graph -->
          <g transform="translate(315, 40)" opacity="0.65">
            <rect width="90" height="70" rx="6" fill="#0b0f19" stroke="#1d4ed8" stroke-width="0.75" />
            <line x1="5" y1="17" x2="85" y2="17" stroke="#1e293b" stroke-width="0.5" />
            <line x1="5" y1="35" x2="85" y2="35" stroke="#1e293b" stroke-width="0.5" />
            <line x1="5" y1="52" x2="85" y2="52" stroke="#1e293b" stroke-width="0.5" />
            <path d="M 5,60 C 25,45 35,15 50,12 C 65,9 75,5 85,4" stroke="#3b82f6" stroke-width="1.5" fill="none" />
            <path d="M 5,65 C 25,55 35,28 50,22 C 65,18 75,15 85,14" stroke="#fb923c" stroke-width="1.25" fill="none" />
            <circle cx="85" cy="4" r="2" fill="#3b82f6" />
            <circle cx="85" cy="14" r="2" fill="#fb923c" />
            <text x="45" y="82" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">ACC: 96.2%</text>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#3b82f6" letter-spacing="1.5">IMAGE CLASSIFICATION</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">Cat vs Dog Classifier</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Binary image classification system trained utilizing</tspan>
              <tspan x="0" dy="16">Convolutional Neural Networks and TensorFlow models.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#0f172a" stroke="#1d4ed8" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#60a5fa" text-anchor="middle">TRAINED</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="65" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="32.5" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">TensorFlow</text>
              <rect x="71" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="96" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Python</text>
              <rect x="127" width="40" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="147" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">CNNs</text>
            </g>
          </g>
        </svg>
      </a>
    </td>

    <!-- Project Card 4: House Price Prediction -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/house-price-prediction" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c4-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#10b981" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#059669" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c4-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#10b981" stop-opacity="0.15" />
              <stop offset="1" stop-color="#10b981" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c4-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c4-glow)" />

          <!-- Mock Regression Scatter Plot with Line of Best Fit -->
          <g transform="translate(315, 40)" opacity="0.65">
            <rect width="90" height="70" rx="6" fill="#041a12" stroke="#10b981" stroke-width="0.75" />
            <circle cx="15" cy="60" r="2.5" fill="#34d399" />
            <circle cx="25" cy="52" r="2.5" fill="#34d399" />
            <circle cx="30" cy="40" r="2.5" fill="#34d399" />
            <circle cx="45" cy="45" r="2.5" fill="#34d399" />
            <circle cx="55" cy="28" r="2.5" fill="#34d399" />
            <circle cx="65" cy="25" r="2.5" fill="#34d399" />
            <circle cx="75" cy="15" r="2.5" fill="#34d399" />
            <circle cx="80" cy="8" r="2.5" fill="#34d399" />
            <line x1="5" y1="65" x2="85" y2="7" stroke="#059669" stroke-width="1.5" />
            <text x="45" y="82" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">R²: 0.912</text>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#10b981" letter-spacing="1.5">REGRESSION MACHINE LEARNING</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">House Price Prediction</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Actuarial supervised pricing models deploying</tspan>
              <tspan x="0" dy="16">regression analysis algorithms on real estate datasets.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#062e24" stroke="#059669" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#34d399" text-anchor="middle">SOLVED</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="65" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="32.5" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Scikit-Learn</text>
              <rect x="71" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="96" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Pandas</text>
              <rect x="127" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="152" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Seaborn</text>
            </g>
          </g>
        </svg>
      </a>
    </td>
  </tr>

  <tr>
    <!-- Project Card 5: Iris K-Means -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/iris-kmeans" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c5-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#f59e0b" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#d97706" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c5-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#f59e0b" stop-opacity="0.15" />
              <stop offset="1" stop-color="#f59e0b" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c5-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c5-glow)" />

          <!-- Mock K-Means Cluster Diagram -->
          <g transform="translate(315, 40)" opacity="0.65">
            <rect width="90" height="70" rx="6" fill="#201502" stroke="#d97706" stroke-width="0.75" />
            <circle cx="20" cy="20" r="3" fill="#a855f7" />
            <circle cx="28" cy="15" r="3" fill="#a855f7" />
            <circle cx="15" cy="28" r="3" fill="#a855f7" />
            <circle cx="55" cy="50" r="3" fill="#f59e0b" />
            <circle cx="65" cy="45" r="3" fill="#f59e0b" />
            <circle cx="60" cy="58" r="3" fill="#f59e0b" />
            <circle cx="70" cy="22" r="3" fill="#06b6d4" />
            <circle cx="80" cy="18" r="3" fill="#06b6d4" />
            <circle cx="75" cy="30" r="3" fill="#06b6d4" />
            <text x="45" y="82" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">K = 3 CLUSTERS</text>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#f59e0b" letter-spacing="1.5">UNSUPERVISED CLUSTERING</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">Iris K-Means</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Iris flower dataset clustering model utilizing unsupervised</tspan>
              <tspan x="0" dy="16">K-Means algorithms to classify species partitions.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#3c1e02" stroke="#d97706" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#fbbf24" text-anchor="middle">K-MEANS</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="55" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="27.5" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Clustering</text>
              <rect x="61" width="55" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="88.5" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Scikit-Learn</text>
              <rect x="122" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="147" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Matplotlib</text>
            </g>
          </g>
        </svg>
      </a>
    </td>

    <!-- Project Card 6: Insurance Prediction -->
    <td width="50%" valign="top">
      <a href="https://github.com/mrgraciz123/insurance-prediction" target="_blank">
        <svg width="100%" height="190" viewBox="0 0 430 190" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="c6-border" x1="0" y1="0" x2="430" y2="190" gradientUnits="userSpaceOnUse">
              <stop stop-color="#ec4899" stop-opacity="0.4"/>
              <stop offset="1" stop-color="#db2777" stop-opacity="0.1"/>
            </linearGradient>
            <radialGradient id="c6-glow" cx="30" cy="30" r="150" gradientUnits="userSpaceOnUse">
              <stop stop-color="#ec4899" stop-opacity="0.15" />
              <stop offset="1" stop-color="#ec4899" stop-opacity="0" />
            </radialGradient>
          </defs>
          <rect width="430" height="190" rx="14" fill="#070709" stroke="url(#c6-border)" stroke-width="1.5" />
          <rect width="430" height="190" rx="14" fill="url(#c6-glow)" />

          <!-- Mock Bell Curve / Premium Probability graph -->
          <g transform="translate(315, 40)" opacity="0.65">
            <rect width="90" height="70" rx="6" fill="#1f0714" stroke="#ec4899" stroke-width="0.75" />
            <path d="M 5,65 C 25,65 35,10 45,10 C 55,10 65,65 85,65" stroke="#ec4899" stroke-width="1.5" fill="none" />
            <path d="M 35,40 C 40,25 45,10 45,10 C 45,10 50,25 55,40 L 55,65 L 35,65 Z" fill="#ec4899" fill-opacity="0.2" />
            <text x="45" y="82" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">PREMIUM CALC</text>
          </g>

          <g transform="translate(24, 28)">
            <text x="0" y="10" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="600" font-size="10" fill="#ec4899" letter-spacing="1.5">PREDICTIVE DATA MODELLING</text>
            <text x="0" y="32" font-family="'Space Grotesk', -apple-system, sans-serif" font-weight="700" font-size="18" fill="#ffffff">Insurance Prediction</text>
            <path d="M 94,20 L 102,20 M 102,20 L 102,28 M 102,20 L 94,28" stroke="#94a3b8" stroke-width="1.5" stroke-linecap="round" />
            
            <text x="0" y="60" font-family="'Inter', -apple-system, sans-serif" font-weight="400" font-size="12" fill="#94a3b8">
              <tspan x="0" dy="0">Actuarial predictive pricing and assessment models built</tspan>
              <tspan x="0" dy="16">deploying supervised estimators on risk profile data.</tspan>
            </text>
            <g transform="translate(0, 95)">
              <rect width="45" height="18" rx="4" fill="#3b0712" stroke="#db2777" stroke-width="1" />
              <text x="22.5" y="12" font-family="monospace" font-size="9" fill="#f472b6" text-anchor="middle">SOLVED</text>
            </g>
            <g transform="translate(55, 95)">
              <rect x="0" width="55" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="27.5" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Data Model</text>
              <rect x="61" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="86" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Python</text>
              <rect x="117" width="50" height="18" rx="4" fill="#0f172a" stroke="#1e293b" stroke-width="1" />
              <text x="142" y="12" font-family="'Inter', -apple-system, sans-serif" font-weight="600" font-size="9" fill="#94a3b8" text-anchor="middle">Estimator</text>
            </g>
          </g>
        </svg>
      </a>
    </td>
  </tr>
</table>

---

## 📊 Analytics Workspace

A synchronized aggregation of coding activities and repository statistics across my GitHub profile.

<p align="center">
  <!-- Stats Card -->
  <img height="185" src="https://github-readme-stats.vercel.app/api?username=mrgraciz123&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070709&title_color=a855f7&text_color=cbd5e1&icon_color=3b82f6" alt="Abhay's Profile Stats" />
  &nbsp;&nbsp;
  <!-- Languages Card -->
  <img height="185" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrgraciz123&layout=compact&theme=tokyonight&hide_border=true&bg_color=070709&title_color=a855f7&text_color=cbd5e1&langs_count=6" alt="Abhay's Language Statistics" />
</p>

<p align="center">
  <!-- Streak Card -->
  <img src="https://streak-stats.demolab.com?user=mrgraciz123&theme=tokyonight&hide_border=true&background=070709&ring=a855f7&fire=3b82f6&currStreakLabel=a855f7&sideNums=cbd5e1&sideLabels=94a3b8" alt="Abhay's Commit Streak" />
</p>

<p align="center">
  <!-- Activity Graph -->
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=mrgraciz123&theme=tokyo-night&bg_color=070709&color=a855f7&line=3b82f6&point=06b6d4&area=true&hide_border=true" alt="Abhay's Activity Graph" />
</p>

<br/>

<div align="center">
  <!-- Trophy Showcase -->
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=mrgraciz123&theme=tokyonight&no-bg=true&no-frame=true&margin-w=15&margin-h=15" alt="Abhay's Trophies" />
  </a>
</div>

---

## ⚡ Active Horizon & Systems CLI

Interactive console outputs displaying my current research roadmap, targets for 2026, and developmental trivia.

<pre>
<span style="color: #38bdf8;">$ abhay --init</span>
<span style="color: #64748b;">Initializing neural workspace ... [OK]</span>
<span style="color: #64748b;">Loading metrics parameters ... [OK]</span>

<span style="color: #a855f7;">$ abhay --query --stack --active</span>
{
  "focus_learning": [
    "Advanced Deep Learning: Multi-modal models and Transformer blocks",
    "Generative AI & LLMs: Latent diffusion models and fine-tuning configurations",
    "High-Frequency Backends: Deploying FastAPI systems inside Docker containers",
    "Compiling native OpenCV bindings inside optimized C++ algorithms"
  ],
  "milestones_2026": [
    "🎯 Deploy 3 production-ready neural networks to public cloud endpoints",
    "🏆 Win upcoming regional and national engineering hackathons",
    "🤝 Contribute core code to open-source deep learning repositories",
    "💼 Secure a focused industrial machine learning or computer vision internship"
  ]
}

<span style="color: #10b981;">$ abhay --trivia --verbose</span>
&gt; Prototyping complex neural structures from absolute scratch is my primary workflow.
&gt; Strong advocate of visual computing models addressing immediate real-world use-cases.
&gt; peak compiling efficiency occurs inside late-night programming blocks.
&gt; Space Grotesk is configured as my primary interface typeface.
</pre>

---

## 🐍 Interactive Activity Snake

A background workflow checks in daily to generate a dynamic crawler parsing my contributions matrix:

<p align="center">
  <img src="https://raw.githubusercontent.com/mrgraciz123/mrgraciz123/output/github-contribution-grid-snake-dark.svg" alt="Abhay's Contribution Snake Grid" width="100%" />
</p>

> [!TIP]
> ### How to set this up on your profile repository:
> 1. Create a workspace action file: `.github/workflows/snake.yml`
> 2. Implement the **Platane/snk** runner.
> 3. Configure it to output to a branch (`output`) or directly check in your SVG asset.

---

## 📫 Let's Connect!

I am always open to discussing model optimizations, hardware-accelerated computer vision, backend integrations, or potential hackathon collaborations.

- **LinkedIn Platform:** [Abhay Shanker Tiwari](https://www.linkedin.com/in/abhay-shanker-tiwari-0a8031213/)
- **X Profile:** [@mr_graciz](https://x.com/mr_graciz)
- **Direct Mail:** *Reach out via LinkedIn or X direct message for secure inquiries.*

<div align="center">
  <br/>
  <!-- Hidden backup snake asset for caching validation -->
  <img src="https://raw.githubusercontent.com/mrgraciz123/mrgraciz123/output/github-contribution-grid-snake.svg" style="display:none;" />
  <p style="color: #4b5563; font-size: 11px;">
    Handcrafted with ❤️ &amp; SVG Vectors. Inspired by Vercel Design Language.<br/>
    &copy; 2026 Abhay Shanker Tiwari. All Rights Reserved.
  </p>
</div>