<!--  ╔══════════════════════════════════════════════════════════════╗
      ║           YOINER TOVAR — GitHub Profile README              ║
      ║   Copia todo el contenido de este archivo en el             ║
      ║   README.md de tu repositorio de perfil de GitHub.           ║
      ║   Diseñado con amor y tecnología por Antigravity            ║
      ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<!-- ░░ CABECERA SVG CYBERPUNK CON CIRCUITOS Y EFECTO DE GLOW ░░ -->
<svg width="100%" viewBox="0 0 860 250" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Filtros de Brillo (Glow) -->
    <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur" />
      <feComponentTransfer in="blur" result="glow1">
        <feFuncA type="linear" slope="0.8"/>
      </feComponentTransfer>
      <feMerge>
        <feMergeNode in="glow1" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="subtleGlow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="2.5" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <!-- Gradientes -->
    <linearGradient id="cyberBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#020617"/>
      <stop offset="40%"  stop-color="#090d1f"/>
      <stop offset="80%"  stop-color="#0f112b"/>
      <stop offset="100%" stop-color="#180e29"/>
    </linearGradient>
    <linearGradient id="neonGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00f2fe"/>
      <stop offset="50%"  stop-color="#9d4edd"/>
      <stop offset="100%" stop-color="#ff007f"/>
    </linearGradient>
    <linearGradient id="blueGlowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00f2fe" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#00f2fe" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#00f2fe" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <!-- Fondo base -->
  <rect width="860" height="250" fill="url(#cyberBg)" rx="18"/>
  <rect x="0" y="0" width="860" height="3" fill="url(#blueGlowGrad)" rx="1"/>
  <rect x="0" y="247" width="860" height="3" fill="url(#blueGlowGrad)" rx="1"/>

  <!-- Líneas de Circuito Integrado SVG (Cyberpunk Pattern) -->
  <path d="M 30 125 L 120 125 L 150 95 L 240 95" stroke="#00f2fe" stroke-width="1.5" fill="none" opacity="0.65" filter="url(#subtleGlow)"/>
  <path d="M 830 125 L 740 125 L 710 155 L 620 155" stroke="#9d4edd" stroke-width="1.5" fill="none" opacity="0.65" filter="url(#subtleGlow)"/>
  <path d="M 200 30 L 230 60 L 320 60" stroke="#ff007f" stroke-width="1" fill="none" opacity="0.4"/>
  <path d="M 660 220 L 630 190 L 540 190" stroke="#00f2fe" stroke-width="1" fill="none" opacity="0.4"/>

  <!-- Nodos de circuito (Círculos) -->
  <circle cx="240" cy="95" r="4.5" fill="#00f2fe" filter="url(#subtleGlow)"/>
  <circle cx="320" cy="60" r="3.5" fill="#ff007f" filter="url(#subtleGlow)"/>
  <circle cx="620" cy="155" r="4.5" fill="#9d4edd" filter="url(#subtleGlow)"/>
  <circle cx="540" cy="190" r="3.5" fill="#00f2fe" filter="url(#subtleGlow)"/>

  <!-- Nubes de luz de fondo (Efectos de brillo tecnológico) -->
  <circle cx="100" cy="125" r="80" fill="#00f2fe" fill-opacity="0.04" filter="url(#neonGlow)"/>
  <circle cx="760" cy="125" r="80" fill="#9d4edd" fill-opacity="0.04" filter="url(#neonGlow)"/>

  <!-- TEXTO PRINCIPAL: Nombre en 3D/Sombra y Brillo -->
  <text x="432" y="92" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="46" font-weight="900"
        fill="#020617" text-anchor="middle" letter-spacing="4" opacity="0.75">YOINER DAVID TOVAR</text>
  <text x="430" y="90" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="46" font-weight="900"
        fill="#ffffff" text-anchor="middle" letter-spacing="4" filter="url(#subtleGlow)">YOINER DAVID TOVAR</text>

  <!-- Línea divisoria central con gradiente de neón -->
  <rect x="180" y="112" width="500" height="2" fill="url(#neonGradient)" filter="url(#subtleGlow)"/>

  <!-- SUBTÍTULO: Roles del desarrollador -->
  <text x="430" y="145" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="15" font-weight="700"
        fill="#00f2fe" text-anchor="middle" letter-spacing="4.5" filter="url(#subtleGlow)">
    SOFTWARE ENGINEER  ·  FRONT-END DEVELOPER  ·  WEB DEVELOPER
  </text>
  <text x="430" y="165" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="11" font-weight="600"
        fill="#9d4edd" text-anchor="middle" letter-spacing="2" opacity="0.9">
    CREATIVIDAD VISUAL  &amp;  ARQUITECTURA DE CÓDIGO
  </text>

  <!-- Badge dinámico de disponibilidad estilo Cyberpunk -->
  <rect x="290" y="190" width="280" height="28" rx="14" fill="#00f2fe" fill-opacity="0.1" filter="url(#subtleGlow)"/>
  <rect x="290" y="190" width="280" height="28" rx="14" fill="none" stroke="url(#neonGradient)" stroke-width="1.5" stroke-opacity="0.8"/>
  <circle cx="310" cy="204" r="5" fill="#39ff14" filter="url(#subtleGlow)"/>
  <text x="440" y="208.5" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="11.5" font-weight="700"
        fill="#e2e8f0" text-anchor="middle" letter-spacing="1">🟢 DISPONIBLE / OPEN TO WORK (REMOTO)</text>
</svg>

</div>

<br/>

<div align="center">

<!-- Typing SVG animado -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=17&duration=2000&pause=1000&color=00F2FE&center=true&vCenter=true&width=750&lines=Software+Engineer+%E2%80%94+Universidad+de+Cartagena;Graduado+con+Honores;Frontend+Specialist+%7C+Angular+%26+React;Dise%C3%B1o+Gr%C3%A1fico+%26+UI%2FUX+%7C+Bellas+Artes;Clean+Code+%2B+Scalable+Architecture)](https://git.io/typing-svg)

</div>

<br/>

<!-- ░░ BIENVENIDA MOCKUP: AVATAR NEÓN + TERMINAL INTERACTIVA ░░ -->
<table align="center" style="border-collapse: collapse; border: none; width: 100%;">
  <tr style="border: none;">
    <!-- Avatar con anillo neón de gradiente -->
    <td align="center" width="28%" style="border: none; padding: 10px;" valign="middle">
      <svg width="180" height="180" viewBox="0 0 180 180" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="avatarGlow" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#00f2fe"/>
            <stop offset="50%" stop-color="#9d4edd"/>
            <stop offset="100%" stop-color="#ff007f"/>
          </linearGradient>
          <filter id="neonShadow" x="-20%" y="-20%" width="140%" height="140%">
            <feGaussianBlur stdDeviation="4.5" result="blur"/>
            <feMerge>
              <feMergeNode in="blur"/>
              <feMergeNode in="SourceGraphic"/>
            </feMerge>
          </filter>
          <clipPath id="circleClip">
            <circle cx="90" cy="90" r="76"/>
          </clipPath>
        </defs>
        <!-- Anillo Neón con Glow -->
        <circle cx="90" cy="90" r="81" stroke="url(#avatarGlow)" stroke-width="4.5" fill="none" filter="url(#neonShadow)"/>
        <!-- Imagen del Avatar de GitHub -->
        <image href="https://github.com/yoinertovar.png" x="14" y="14" width="152" height="152" clip-path="url(#circleClip)"/>
      </svg>
      <br/>
      <br/>
      <a href="https://wa.me/573017260118"><img src="https://img.shields.io/badge/Contactar%20WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
    </td>
    <!-- Terminal SVG Mockup de Bienvenida -->
    <td width="72%" style="border: none; padding: 10px 20px;" valign="middle">
      <svg width="100%" height="195" viewBox="0 0 500 195" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <filter id="terminalGlow">
            <feGaussianBlur stdDeviation="1.5" result="blur"/>
            <feMerge>
              <feMergeNode in="blur"/>
              <feMergeNode in="SourceGraphic"/>
            </feMerge>
          </filter>
        </defs>
        <!-- Consola de comandos -->
        <rect width="500" height="195" rx="10" fill="#030712" stroke="#1e293b" stroke-width="1.8"/>
        <!-- Barra de cabecera -->
        <rect width="500" height="30" rx="10" fill="#0f172a"/>
        <!-- Botones OS -->
        <circle cx="18" cy="15" r="5" fill="#ff5f56"/>
        <circle cx="33" cy="15" r="5" fill="#ffbd2e"/>
        <circle cx="48" cy="15" r="5" fill="#27c93f"/>
        <!-- Nombre de la terminal -->
        <text x="250" y="20" font-family="'Fira Code', monospace, sans-serif" font-size="11" fill="#64748b" text-anchor="middle">yoinertovar@cartagena:~</text>
        
        <!-- Texto terminal -->
        <text x="20" y="55" font-family="'Fira Code', monospace" font-size="12" font-weight="bold" fill="#38bdf8">
          <tspan fill="#00f2fe">yoiner-tovar ~ </tspan>cat perfil.json
        </text>
        <text x="20" y="78" font-family="'Fira Code', monospace" font-size="11" fill="#94a3b8">
          {
        </text>
        <text x="40" y="96" font-family="'Fira Code', monospace" font-size="11" fill="#e2e8f0">
          <tspan fill="#ff007f">"nombre"</tspan>: <tspan fill="#e2e8f0">"Yoiner David Tovar Navarro"</tspan>,
        </text>
        <text x="40" y="113" font-family="'Fira Code', monospace" font-size="11" fill="#e2e8f0">
          <tspan fill="#ff007f">"almaMater"</tspan>: <tspan fill="#4ade80">"Universidad de Cartagena (Graduado con Honores 🎓)"</tspan>,
        </text>
        <text x="40" y="130" font-family="'Fira Code', monospace" font-size="11" fill="#e2e8f0">
          <tspan fill="#ff007f">"educacionGrafica"</tspan>: <tspan fill="#4ade80">"Bellas Artes — Diseñador Gráfico (Honores 🎨)"</tspan>,
        </text>
        <text x="40" y="147" font-family="'Fira Code', monospace" font-size="11" fill="#e2e8f0">
          <tspan fill="#ff007f">"skills"</tspan>: [<tspan fill="#38bdf8">"Angular"</tspan>, <tspan fill="#38bdf8">"React"</tspan>, <tspan fill="#38bdf8">"TypeScript"</tspan>, <tspan fill="#38bdf8">"Tailwind"</tspan>, <tspan fill="#38bdf8">"Figma"</tspan>],
        </text>
        <text x="40" y="164" font-family="'Fira Code', monospace" font-size="11" fill="#e2e8f0">
          <tspan fill="#ff007f">"filosofia"</tspan>: <tspan fill="#eab308">"Código limpio que parece arte. Visuales fluidos."</tspan>
        </text>
        <text x="20" y="182" font-family="'Fira Code', monospace" font-size="11" fill="#94a3b8">
          }
        </text>
      </svg>
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <!-- Redes e información complementaria -->
  <a href="https://portafolioyoinertn.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/%F0%9F%8C%90_Portafolio%20Oficial-00f2fe?style=for-the-badge&labelColor=030712" alt="Portafolio"/></a>&nbsp;
  <a href="https://linkedin.com/in/yoiner-tovar" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="mailto:yoinertnwork@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;
  <a href="https://github.com/yoinertovar"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</div>

<br/>

---

## ⚡ Panel de Control & Áreas de Experiencia

> [!NOTE]
> La fusión de conocimientos entre ingeniería lógica y arte gráfico permite un desarrollo front-end sumamente balanceado, donde la arquitectura técnica del código escala de la misma forma en que cautiva la interfaz visual del usuario.

<div align="center">

```
┌───────────────────────────────────────────────────────────┐
│                                                           │
│  🖥️ Desarrollo Front-End   [████████████████████] 100%     │
│  🎨 UI/UX & Arte Gráfico   [████████████████░░░░]  80%     │
│  🗄️ MySQL / SQL DB         [████████████░░░░░░░░]  60%     │
│  🤖 Integración de APIs    [██████████████░░░░░░]  70%     │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

</div>

---

## 🔷 Stack de Tecnologías Avanzadas

<div align="center">

### 💻 Front-End & Frameworks Core

![JavaScript](https://img.shields.io/badge/JavaScript%20(ES6+)-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)&nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### 🎨 Maquetación & Diseño Web

![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)&nbsp;
![Bootstrap](https://img.shields.io/badge/Bootstrap%205-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)&nbsp;
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### ⚙️ Back-End & Base de Datos

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)&nbsp;
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![SQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)&nbsp;
![Node.js](https://img.shields.io/badge/Node.js%20(b%C3%A1sico)-339933?style=for-the-badge&logo=node.js&logoColor=white)

### 🛠️ Herramientas de Diseño & DevOps

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)&nbsp;
![Adobe Suite](https://img.shields.io/badge/Adobe%20Suite-FF0000?style=for-the-badge&logo=adobe&logoColor=white)&nbsp;
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)&nbsp;
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)&nbsp;
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

</div>

---

## 💼 Línea de Tiempo Profesional (Timeline)

<table style="border: none; border-collapse: collapse; width: 100%;">
  
  <!-- Fila 1: SMA Edu -->
  <tr style="border: none;">
    <td width="16%" align="right" valign="top" style="border: none; padding-right: 15px; padding-top: 5px;">
      <span style="color: #00f2fe; font-family: monospace; font-size: 13px; font-weight: 800;">2024 - ACT.</span>
    </td>
    <td width="6%" align="center" valign="top" style="border: none;">
      <svg width="24" height="150" viewBox="0 0 24 150" xmlns="http://www.w3.org/2000/svg">
        <circle cx="12" cy="12" r="8" fill="#00f2fe" stroke="#030712" stroke-width="2.5" filter="url(#subtleGlow)"/>
        <line x1="12" y1="20" x2="12" y2="150" stroke="#1e293b" stroke-width="2.5"/>
      </svg>
    </td>
    <td width="78%" valign="top" style="border: none; padding-bottom: 25px;">
      <h3 style="color: #ffffff; margin: 0; font-size: 16px;">Desarrollador Front-End Junior – Angular</h3>
      <span style="color: #9d4edd; font-weight: 600; font-size: 13px;">SMA Edu (Proyecto Freelance)</span>
      <p style="color: #94a3b8; font-size: 13.5px; line-height: 1.6; margin-top: 6px;">
        ▸ Diseñé y desarrollé el dashboard principal de la plataforma educativa <strong>SMA Edu</strong> en Angular, entregando interfaces interactivas y <em>mobile-first</em> que elevaron sustancialmente la retención y experiencia de los estudiantes.<br/>
        ▸ Construí una biblioteca modular de componentes reutilizables con estilos CSS globales unificados, reduciendo tiempos de desarrollo y maquetación de nuevas vistas en un <strong>30%</strong>.<br/>
        ▸ Creé soluciones web complementarias en React y Tailwind CSS dedicadas a resolver problemáticas de gestión y auditoría interna de inventarios.
      </p>
    </td>
  </tr>

  <!-- Fila 2: Docente TIC -->
  <tr style="border: none;">
    <td width="16%" align="right" valign="top" style="border: none; padding-right: 15px; padding-top: 5px;">
      <span style="color: #00f2fe; font-family: monospace; font-size: 13px; font-weight: 800;">FEB - JUN 2025</span>
    </td>
    <td width="6%" align="center" valign="top" style="border: none;">
      <svg width="24" height="110" viewBox="0 0 24 110" xmlns="http://www.w3.org/2000/svg">
        <circle cx="12" cy="12" r="6" fill="#9d4edd" stroke="#030712" stroke-width="2.5" opacity="0.9"/>
        <line x1="12" y1="18" x2="12" y2="110" stroke="#1e293b" stroke-width="2.5"/>
      </svg>
    </td>
    <td width="78%" valign="top" style="border: none; padding-bottom: 25px;">
      <h3 style="color: #ffffff; margin: 0; font-size: 16px;">Docente TIC – Educación en Informática</h3>
      <span style="color: #9d4edd; font-weight: 600; font-size: 13px;">Centro Educativo Santo Domingo Savio</span>
      <p style="color: #94a3b8; font-size: 13.5px; line-height: 1.6; margin-top: 6px;">
        ▸ Impartí clases de Tecnología e Informática a estudiantes de primaria (grados 1° a 5°), liderando planes educativos para el fomento de habilidades lógicas y competencias informáticas fundamentales.
      </p>
    </td>
  </tr>

  <!-- Fila 3: P&B Comunicaciones -->
  <tr style="border: none;">
    <td width="16%" align="right" valign="top" style="border: none; padding-right: 15px; padding-top: 5px;">
      <span style="color: #00f2fe; font-family: monospace; font-size: 13px; font-weight: 800;">ENE - DIC 2024</span>
    </td>
    <td width="6%" align="center" valign="top" style="border: none;">
      <svg width="24" height="120" viewBox="0 0 24 120" xmlns="http://www.w3.org/2000/svg">
        <circle cx="12" cy="12" r="6" fill="#9d4edd" stroke="#030712" stroke-width="2.5" opacity="0.9"/>
        <line x1="12" y1="18" x2="12" y2="120" stroke="#1e293b" stroke-width="2.5"/>
      </svg>
    </td>
    <td width="78%" valign="top" style="border: none; padding-bottom: 25px;">
      <h3 style="color: #ffffff; margin: 0; font-size: 16px;">Técnico Instalador de Software – Ofimática</h3>
      <span style="color: #9d4edd; font-weight: 600; font-size: 13px;">P&B Comunicaciones S.A.S</span>
      <p style="color: #94a3b8; font-size: 13.5px; line-height: 1.6; margin-top: 6px;">
        ▸ Gestioné la instalación técnica, parametrización de sistemas operativos y resolución de incidencias en entornos empresariales críticos, logrando mantener la disponibilidad de sistemas.<br/>
        ▸ Reconocido oficialmente por la compañía gracias al óptimo cumplimiento, honestidad y disciplina operativa.
      </p>
    </td>
  </tr>

  <!-- Fila 4: IE Buenavista -->
  <tr style="border: none;">
    <td width="16%" align="right" valign="top" style="border: none; padding-right: 15px; padding-top: 5px;">
      <span style="color: #00f2fe; font-family: monospace; font-size: 13px; font-weight: 800;">FEB - AGO 2024</span>
    </td>
    <td width="6%" align="center" valign="top" style="border: none;">
      <svg width="24" height="90" viewBox="0 0 24 90" xmlns="http://www.w3.org/2000/svg">
        <circle cx="12" cy="12" r="6" fill="#00f2fe" stroke="#030712" stroke-width="2.5" filter="url(#subtleGlow)"/>
      </svg>
    </td>
    <td width="78%" valign="top" style="border: none; padding-bottom: 25px;">
      <h3 style="color: #ffffff; margin: 0; font-size: 16px;">Practicante – Auxiliar de Software y Ofimática</h3>
      <span style="color: #9d4edd; font-weight: 600; font-size: 13px;">Institución Educativa Buenavista</span>
      <p style="color: #94a3b8; font-size: 13.5px; line-height: 1.6; margin-top: 6px;">
        ▸ Asistí técnicamente a docentes y personal administrativo en la optimización de plataformas de notas y software de oficina, siendo evaluado con un desempeño sobresaliente por iniciativa y responsabilidad.
      </p>
    </td>
  </tr>
</table>

---

## 🚀 Proyectos de Nivel Dios (Featured Projects)

<table style="border: none; border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <!-- Tarjeta Proyecto 1 -->
    <td width="50%" valign="top" style="border: none; padding: 10px;">
      <div style="background-color: #050b18; border: 1.5px solid #1e293b; border-radius: 12px; padding: 20px; min-height: 165px; box-shadow: 0px 4px 15px rgba(0, 242, 254, 0.05);">
        <span style="float: right; font-size: 22px;">🎓</span>
        <h3 style="color: #00f2fe; margin-top: 0; font-size: 16px; font-weight: 700; letter-spacing: 0.5px;">Dashboard SMA Edu</h3>
        <p style="color: #94a3b8; font-size: 13px; line-height: 1.5; margin-top: 8px;">
          Plataforma educativa con un panel de control interactivo para analítica escolar. Utiliza una arquitectura modular robusta y estilos globales optimizados.
        </p>
        <div style="margin-top: 15px;">
          <span style="background: #1e1b4b; color: #a5b4fc; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; margin-right: 5px; border: 1px solid #312e81;">Angular</span>
          <span style="background: #030712; color: #94a3b8; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; border: 1px solid #1e293b;">TypeScript</span>
          <span style="background: #06202a; color: #00f2fe; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; border: 1px solid #083344;">CSS3</span>
        </div>
      </div>
    </td>
    <!-- Tarjeta Proyecto 2 -->
    <td width="50%" valign="top" style="border: none; padding: 10px;">
      <div style="background-color: #050b18; border: 1.5px solid #1e293b; border-radius: 12px; padding: 20px; min-height: 165px; box-shadow: 0px 4px 15px rgba(157, 78, 221, 0.05);">
        <span style="float: right; font-size: 22px;">📦</span>
        <h3 style="color: #9d4edd; margin-top: 0; font-size: 16px; font-weight: 700; letter-spacing: 0.5px;">Gestor de Inventarios</h3>
        <p style="color: #94a3b8; font-size: 13px; line-height: 1.5; margin-top: 8px;">
          Aplicación web freelance rápida y fluida para el control, auditoría y auditoría visual de mercancías en tiempo real. Diseño 100% responsivo y filtrado dinámico.
        </p>
        <div style="margin-top: 15px;">
          <span style="background: #2e0854; color: #d8b4fe; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; margin-right: 5px; border: 1px solid #4c0519;">React</span>
          <span style="background: #06202a; color: #22d3ee; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; border: 1px solid #083344;">Tailwind CSS</span>
        </div>
      </div>
    </td>
  </tr>
  <tr style="border: none;">
    <!-- Tarjeta Proyecto 3 -->
    <td width="50%" valign="top" style="border: none; padding: 10px;">
      <div style="background-color: #050b18; border: 1.5px solid #1e293b; border-radius: 12px; padding: 20px; min-height: 165px; box-shadow: 0px 4px 15px rgba(244, 63, 94, 0.05);">
        <span style="float: right; font-size: 22px;">💼</span>
        <h3 style="color: #f43f5e; margin-top: 0; font-size: 16px; font-weight: 700; letter-spacing: 0.5px;">Portafolio Profesional</h3>
        <p style="color: #94a3b8; font-size: 13px; line-height: 1.5; margin-top: 8px;">
          Tu vitrina al mundo. Muestra de proyectos interactivos, habilidades de ingeniería y arte gráfico desplegados en producción con alto rendimiento.
        </p>
        <div style="margin-top: 15px; display: flex; align-items: center; justify-content: space-between;">
          <div>
            <span style="background: #0f172a; color: #cbd5e1; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; margin-right: 5px; border: 1px solid #1e293b;">Vanilla JS</span>
            <span style="background: #030712; color: #38bdf8; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; border: 1px solid #1e293b;">HTML/CSS</span>
          </div>
          <a href="https://portafolioyoinertn.netlify.app/" target="_blank" style="color: #00f2fe; font-size: 12px; text-decoration: none; font-weight: bold; letter-spacing: 0.5px;">DEMO LIVE →</a>
        </div>
      </div>
    </td>
    <!-- Tarjeta Proyecto 4 -->
    <td width="50%" valign="top" style="border: none; padding: 10px;">
      <div style="background-color: #050b18; border: 1.5px solid #1e293b; border-radius: 12px; padding: 20px; min-height: 165px; box-shadow: 0px 4px 15px rgba(234, 179, 8, 0.05);">
        <span style="float: right; font-size: 22px;">🌐</span>
        <h3 style="color: #eab308; margin-top: 0; font-size: 16px; font-weight: 700; letter-spacing: 0.5px;">SolPro247 Landing</h3>
        <p style="color: #94a3b8; font-size: 13px; line-height: 1.5; margin-top: 8px;">
          Maquetación moderna e interactiva orientada a la venta de servicios TI y optimización SEO, integrando efectos fluidos en Vanilla CSS.
        </p>
        <div style="margin-top: 15px; display: flex; align-items: center; justify-content: space-between;">
          <div>
            <span style="background: #06202a; color: #22d3ee; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; margin-right: 5px; border: 1px solid #083344;">Tailwind</span>
            <span style="background: #0f172a; color: #94a3b8; font-size: 11px; padding: 3px 8px; border-radius: 12px; font-weight: bold; border: 1px solid #1e293b;">JS ES6+</span>
          </div>
          <a href="https://solpro247.netlify.app/" target="_blank" style="color: #00f2fe; font-size: 12px; text-decoration: none; font-weight: bold; letter-spacing: 0.5px;">DEMO LIVE →</a>
        </div>
      </div>
    </td>
  </tr>
</table>

---

<!-- ░░ EDUCACIÓN & CERTIFICACIONES EN CUADRÍCULA ░░ -->
<table style="border: none; border-collapse: collapse; width: 100%;">
  <tr style="border: none;">
    <!-- Columna Educación -->
    <td width="50%" valign="top" style="border: none; padding: 15px;">
      <h3 style="color: #00f2fe; border-bottom: 2px solid #00f2fe; padding-bottom: 8px; font-size: 18px; font-weight: 800;">🎓 Educación de Elite</h3>
      <ul style="list-style-type: none; padding-left: 0;">
        <li style="margin-bottom: 18px;">
          <span style="color: #9d4edd; font-weight: bold; font-size: 14.5px;">🥇 Ingeniería de Software</span><br/>
          <span style="color: #f8fafc; font-size: 13px;">Universidad de Cartagena</span> &nbsp;|&nbsp; <span style="color: #64748b; font-size: 12.5px;">Nov 2024</span><br/>
          <span style="background: #064e3b; color: #34d399; font-size: 10.5px; padding: 2px 8px; border-radius: 20px; font-weight: 700; border: 1px solid #059669; display: inline-block; margin-top: 5px;">GRADUADO CON HONORES</span>
        </li>
        <li>
          <span style="color: #9d4edd; font-weight: bold; font-size: 14.5px;">🎨 Técnico en Diseño y Arte Gráfico</span><br/>
          <span style="color: #f8fafc; font-size: 13px;">Escuela de Bellas Artes y Humanidades</span><br/>
          <span style="background: #064e3b; color: #34d399; font-size: 10.5px; padding: 2px 8px; border-radius: 20px; font-weight: 700; border: 1px solid #059669; display: inline-block; margin-top: 5px;">GRADUADO CON HONORES</span>
        </li>
      </ul>
    </td>
    <!-- Columna Certificaciones -->
    <td width="50%" valign="top" style="border: none; padding: 15px;">
      <h3 style="color: #9d4edd; border-bottom: 2px solid #9d4edd; padding-bottom: 8px; font-size: 18px; font-weight: 800;">📜 Certificaciones Oficiales</h3>
      <ul style="list-style-type: none; padding-left: 0;">
        <li style="margin-bottom: 18px;">
          <span style="color: #00f2fe; font-weight: bold; font-size: 14.5px;">🗄️ Construcción de Bases de Datos con MySQL</span><br/>
          <span style="color: #f8fafc; font-size: 13px;">SENA — Formación Profesional de 48 hrs</span><br/>
          <span style="color: #64748b; font-size: 12px;">Noviembre 2023</span>
        </li>
        <li>
          <span style="color: #00f2fe; font-weight: bold; font-size: 14.5px;">🌐 Desarrollo Web con PHP</span><br/>
          <span style="color: #f8fafc; font-size: 13px;">SENA — Formación Profesional de 40 hrs</span><br/>
          <span style="color: #64748b; font-size: 12px;">Noviembre 2021</span>
        </li>
      </ul>
    </td>
  </tr>
</table>

---

## 🌐 Idiomas

<div align="center">

![Español](https://img.shields.io/badge/Espa%C3%B1ol-Nativo%20(L2)-00f2fe?style=for-the-badge&labelColor=030712)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Inglés](https://img.shields.io/badge/Ingl%C3%A9s-B%C3%A1sico%20%2F%20Lectura%20T%C3%A9cnica-9d4edd?style=for-the-badge&labelColor=030712)

</div>

---

## 📊 Estadísticas del Servidor (GitHub Stats)

<div align="center">

<!-- GitHub Stats & Top Languages -->
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=yoinertovar&show_icons=true&include_all_commits=true&count_private=true&border_radius=14&bg_color=030712&title_color=9d4edd&icon_color=00f2fe&text_color=e2e8f0&border_color=1e293b" alt="GitHub Stats"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yoinertovar&layout=compact&border_radius=14&bg_color=030712&title_color=9d4edd&text_color=e2e8f0&border_color=1e293b" alt="Top Languages"/>

</div>

<div align="center">

<!-- GitHub Streak Stats -->
[![Racha de Contribuciones](https://github-readme-streak-stats.herokuapp.com?user=yoinertovar&border_radius=14&background=030712&ring=00f2fe&fire=9d4edd&currStreakLabel=e2e8f0&sideLabels=e2e8f0&dates=00f2fe&stroke=1e293b&border=1e293b)](https://git.io/streak-stats)

</div>

<div align="center">

<!-- Activity Graph -->
[![Gráfico de Actividad](https://github-readme-activity-graph.vercel.app/graph?username=yoinertovar&bg_color=030712&color=00f2fe&line=9d4edd&point=ff007f&area=true&hide_border=false&border_color=1e293b&radius=10)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🤝 Hablemos de Ingeniería & Arte Digital

<div align="center">

¿Tienes en mente un proyecto desafiante, una vacante para un puesto remoto o buscas una consultoría Front-End de alto nivel?  
**Conéctame y materialicemos ideas con código limpio y diseños inolvidables.**

<br/>

[![Portafolio](https://img.shields.io/badge/%F0%9F%8C%90_Visitar%20Mi%20Portafolio-00f2fe?style=for-the-badge&labelColor=030712)](https://portafolioyoinertn.netlify.app/)&nbsp;&nbsp;&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/%F0%9F%92%BC_Conectar%20en%20LinkedIn-0A66C2?style=for-the-badge)](https://linkedin.com/in/yoiner-tovar)&nbsp;&nbsp;&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/%F0%9F%93%A7_Enviar%20Correo%20Directo-EA4335?style=for-the-badge)](mailto:yoinertnwork@gmail.com)

</div>

---

<div align="center">

<!-- ░░ PIE DE PÁGINA SVG CYBERPUNK ░░ -->
<svg width="100%" viewBox="0 0 860 75" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#020617"/>
      <stop offset="50%"  stop-color="#0f112b"/>
      <stop offset="100%" stop-color="#020617"/>
    </linearGradient>
    <linearGradient id="footerBorderGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00f2fe" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#9d4edd" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#ff007f" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="860" height="75" fill="url(#footerBg)" rx="14"/>
  <rect x="0" y="0" width="860" height="2.2" fill="url(#footerBorderGrad)" rx="1"/>
  <text x="430" y="32" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="13.5" font-style="italic"
        fill="#00f2fe" text-anchor="middle" fill-opacity="0.95" filter="url(#subtleGlow)">
    "El código es como el arte: si no transmite algo, no está terminado."
  </text>
  <text x="430" y="55" font-family="'Segoe UI', system-ui, -apple-system, sans-serif" font-size="11" font-weight="700"
        fill="#94a3b8" text-anchor="middle" letter-spacing="1.5">— Yoiner David Tovar Navarro  ·  Colombia</text>
</svg>

<br/>

![Visitantes](https://visitor-badge.laobi.icu/badge?page_id=yoinertovar.yoinertovar&color=9d4edd&style=flat-square)&nbsp;&nbsp;&nbsp;&nbsp;
![Hecho en Colombia](https://img.shields.io/badge/Maquetado%20con%20%E2%9D%A4%EF%B8%8F%20en-Colombia-ff007f?style=flat-square)

</div>
