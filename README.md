<div align="center">

<svg width="800" height="160" viewBox="0 0 800 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#111827"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="800" height="160" rx="12" fill="url(#bgGrad)"/>
  <rect width="800" height="160" rx="12" fill="none" stroke="#1e293b" stroke-width="1.5"/>

  <!-- Scan line effect -->
  <rect width="800" height="1" y="40" fill="#00d9ff" opacity="0.04"/>
  <rect width="800" height="1" y="80" fill="#00d9ff" opacity="0.04"/>
  <rect width="800" height="1" y="120" fill="#00d9ff" opacity="0.04"/>

  <!-- Kali Linux Dragon (simplified geometric) -->
  <g transform="translate(48, 30)" filter="url(#softglow)">
    <!-- Dragon body -->
    <path d="M50,10 L62,0 L74,8 L80,22 L72,38 L60,42 L48,36 L40,22 Z" fill="none" stroke="#00d9ff" stroke-width="1.5" opacity="0.9"/>
    <!-- Dragon wing left -->
    <path d="M44,20 L20,10 L28,30 L44,28 Z" fill="none" stroke="#00d9ff" stroke-width="1" opacity="0.6"/>
    <!-- Dragon wing right -->
    <path d="M76,20 L100,10 L92,30 L76,28 Z" fill="none" stroke="#00d9ff" stroke-width="1" opacity="0.6"/>
    <!-- Dragon head details -->
    <path d="M56,4 L62,0 L68,4 L66,12 L58,12 Z" fill="#00d9ff" opacity="0.2"/>
    <circle cx="58" cy="8" r="2" fill="#00d9ff" opacity="0.8"/>
    <circle cx="66" cy="8" r="2" fill="#00d9ff" opacity="0.8"/>
    <!-- Dragon tail -->
    <path d="M48,36 L30,50 L40,52 L52,42" fill="none" stroke="#00d9ff" stroke-width="1" opacity="0.5"/>
    <!-- Inner glow core -->
    <ellipse cx="60" cy="24" rx="10" ry="8" fill="#00d9ff" opacity="0.06"/>
  </g>

  <!-- Terminal prompt decoration -->
  <text x="190" y="55" font-family="'Courier New', monospace" font-size="13" fill="#00d9ff" opacity="0.5">┌──(</text>
  <text x="232" y="55" font-family="'Courier New', monospace" font-size="13" fill="#22c55e" opacity="0.8">root</text>
  <text x="262" y="55" font-family="'Courier New', monospace" font-size="13" fill="#00d9ff" opacity="0.5">㉿kali)</text>
  <text x="190" y="75" font-family="'Courier New', monospace" font-size="13" fill="#00d9ff" opacity="0.5">└─</text>
  <text x="214" y="75" font-family="'Courier New', monospace" font-size="13" fill="#22c55e" opacity="0.8">$</text>
  <text x="228" y="75" font-family="'Courier New', monospace" font-size="11" fill="#ffffff" opacity="0.35">whoami</text>

  <!-- Main name -->
  <text x="190" y="118" font-family="'Courier New', monospace" font-size="36" font-weight="900" fill="#ffffff" filter="url(#glow)" letter-spacing="2">Vinícius Diniz</text>

  <!-- Subtitle line -->
  <text x="192" y="140" font-family="'Courier New', monospace" font-size="13" fill="#00d9ff" opacity="0.75" letter-spacing="1">Full Stack Developer  ·  Security Mindset  ·  Automation</text>

  <!-- Corner brackets -->
  <text x="12" y="22" font-family="monospace" font-size="16" fill="#00d9ff" opacity="0.3">╔</text>
  <text x="776" y="22" font-family="monospace" font-size="16" fill="#00d9ff" opacity="0.3">╗</text>
  <text x="12" y="155" font-family="monospace" font-size="16" fill="#00d9ff" opacity="0.3">╚</text>
  <text x="776" y="155" font-family="monospace" font-size="16" fill="#00d9ff" opacity="0.3">╝</text>
</svg>

</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=viniciusd7&color=00d9ff&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

<div align="center">
  💻 Desenvolvedor Full Stack &nbsp;|&nbsp; 🎓 Engenharia de Software – 7º período &nbsp;|&nbsp; 🔐 Cibersegurança &nbsp;|&nbsp; ⚙️ Automação & Integrações
</div>

---

## 🚀 Sobre mim

Desenvolvedor Full Stack com forte foco em **backend robusto**, **arquitetura bem definida** e **automações inteligentes**.

```typescript
const viniciusDiniz = {
  role:       "Full Stack Developer",
  degree:     "Engenharia de Software – 7º período",
  background: ["Cibersegurança", "Automação de Processos", "Integrações"],
  focus:      ["Escalabilidade", "Performance", "Segurança"],
  currently:  "Construindo soluções que realmente resolvem problemas 🚀",
};
```

---

## 🧠 Stack Principal

### 💜 Linguagens
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🔧 Frameworks & Bibliotecas
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

### 🗄️ Banco de Dados & Infra
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### ⚙️ Ferramentas & Automação
![n8n](https://img.shields.io/badge/n8n-FF6D00?style=for-the-badge&logo=n8n&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=viniciusd7&show_icons=true&theme=transparent&bg_color=0d0d0d&title_color=00d9ff&text_color=ffffff&icon_color=00d9ff&border_color=ffffff&hide_border=false&include_all_commits=true&count_private=true" />
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=viniciusd7&layout=compact&theme=transparent&bg_color=0d0d0d&title_color=00d9ff&text_color=ffffff&border_color=ffffff&hide_border=false&langs_count=8" />

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=viniciusd7&theme=transparent&background=0d0d0d&stroke=ffffff&ring=00d9ff&fire=00d9ff&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=00d9ff&sideLabels=00d9ff&dates=aaaaaa&border=ffffff" />
</div>

---

## 📈 Gráfico de Contribuições

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=viniciusd7&bg_color=000000&color=ffffff&line=ffffff&point=00d9ff&area=false&hide_border=false&border_color=ffffff&title_color=00d9ff" />
</div>

---

## 🌐 Contato

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinícius-diniz-4b3a71324/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:viniciusdm967@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/viniciusd7)

</div>

---

<div align="center">
  <i>"Automatizar o que é repetitivo. Escalar o que gera valor. Construir o que resolve."</i>
</div>
