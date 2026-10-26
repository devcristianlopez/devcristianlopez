<div align="center">
  <img src="./assets/header.svg" width="100%" alt="devcristianlopez — Backend Developer & Software Architect"/>
</div>

<div align="center">
  <a href="https://github.com/devcristianlopez">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=900&color=00F0FF&center=true&vCenter=true&width=900&lines=%3E%208%2B%20a%C3%B1os%20con%20Python%2C%20Django%20y%20Odoo;%3E%20IA%20aplicada%3A%20agentes%2C%20LLMs%20y%20RAG;%3E%20docencia%20t%C3%A9cnica%3A%20cloud%2C%20datos%20y%20DevOps;%3E%20Valpara%C3%ADso%2C%20Chile%20_" alt="Typing SVG"/>
  </a>
</div>

<p align="center">
  <img alt="STATUS" src="https://img.shields.io/badge/STATUS-ONLINE-00F0FF?style=for-the-badge&labelColor=0D0221"/>
  <img alt="LOCATION" src="https://img.shields.io/badge/LOCATION-Valpara%C3%ADso%2C_Chile-FF2A6D?style=for-the-badge&labelColor=0D0221"/>
  <img alt="EXPERIENCE" src="https://img.shields.io/badge/EXPERIENCE-8%2B_YEARS-B026FF?style=for-the-badge&labelColor=0D0221"/>
  <img alt="FOLLOWERS" src="https://img.shields.io/github/followers/devcristianlopez?style=for-the-badge&color=B026FF&labelColor=0D0221&label=FOLLOWERS"/>
  <img alt="STARS" src="https://img.shields.io/github/stars/devcristianlopez?style=for-the-badge&color=00F0FF&labelColor=0D0221&label=STARS"/>
</p>

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

```console
┌──(devcristianlopez㉿github)-[~]
└─$ whoami
> Backend Developer & Software Architect · AI Orchestration

└─$ cat mission.txt
"Construyo backend, automatizo con IA y enseño lo que aprendo."
```

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 01 ⟩ · SYSTEM.PROFILE</h2>

> Desarrollador Backend y Arquitecto de Software con **8+ años** en Python, Django y Odoo. Diseño soluciones con IA aplicada (agentes, LLMs, RAG) y llevo **4+ años** como instructor técnico en cloud, datos y DevOps.
>
> Mi perfil, pero como código.

```python
from dataclasses import dataclass
from typing import ClassVar


@dataclass(slots=True)
class Developer:
    """Perfil vivo: identidad, stack, trayectoria y proyectos."""

    # ── identidad ──────────────────────────────────────────────────────────
    username: str = "devcristianlopez"
    name: str = "Cristian López"
    role: str = "Backend Developer & Software Architect"
    focus: str = "Python · Django · Odoo · AI Orchestration"
    location: str = "Valparaíso, Chile"
    email: str = "cristianlopezvalpo@gmail.com"

    # ── links ──────────────────────────────────────────────────────────────
    web: str = "https://lemoria.org/"
    linkedin: str = "https://linkedin.com/in/cristianl0pez"
    github: str = "https://github.com/devcristianlopez"

    # ── trayectoria ────────────────────────────────────────────────────────
    years_experience: int = 8
    years_teaching: int = 4

    # ── stack ──────────────────────────────────────────────────────────────
    languages: ClassVar[tuple[str, ...]] = ("Python", "TypeScript", "JavaScript", "SQL", "Bash")
    backend: ClassVar[tuple[str, ...]] = ("Django", "FastAPI", "Flask", "Odoo", "REST APIs")
    frontend: ClassVar[tuple[str, ...]] = ("Vue.js", "React", "Astro", "Tailwind CSS")
    data: ClassVar[tuple[str, ...]] = ("PostgreSQL", "MySQL", "SQL Server", "Redis", "Pandas")
    devops: ClassVar[tuple[str, ...]] = ("Docker", "Nginx", "Linux", "CI/CD", "DigitalOcean")
    ai: ClassVar[tuple[str, ...]] = ("Agents", "LLMs", "RAG", "Prompt Engineering", "MCP")

    # ── proyectos ──────────────────────────────────────────────────────────
    projects: ClassVar[dict[str, str]] = {
        "lemoria":               "AI memory & orchestration OS · 8 agents · persistent memory",
        "core-odoo":             "Self-hosted Odoo 20 software factory · Git envs & observability",
        "livebridge":            "TikTok LIVE SDK for Python · custom Webcast protocol",
        "manel":                 "Security health monitor for dev environments",
        "guardian-live-monitor": "OpenCV + FastAPI + WebSockets live surveillance",
        "boilerplate-django":    "Django + PostgreSQL + Docker, production ready",
        "coffe-code":            "PWA to brew the perfect coffee ☕",
    }

    # ── estado actual ──────────────────────────────────────────────────────
    currently: ClassVar[tuple[str, ...]] = (
        "Building Lemoria",
        "Consulting & AI development at Lanedu",
        "Teaching AI, cloud & data",
    )
    open_to: str = "freelance · consultoría · docencia · open source"
    coffee_level: int = 99  # ☕☕☕

    def __str__(self) -> str:
        return f"{self.name} · {self.role} · {self.location}"

    def greet(self) -> str:
        return f"Hey, soy {self.name}. Construyo backend, automatizo con IA y enseño lo que aprendo."


if __name__ == "__main__":
    me = Developer()
    print(me)
    print(me.greet())
```

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 02 ⟩ · TECH.ARSENAL</h2>

<h3 align="center">LANGUAGES</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-0D0221?style=for-the-badge&logo=python&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/TypeScript-0D0221?style=for-the-badge&logo=typescript&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/JavaScript-0D0221?style=for-the-badge&logo=javascript&logoColor=FFE600"/>
  <img src="https://img.shields.io/badge/SQL-0D0221?style=for-the-badge&logo=postgresql&logoColor=FF2A6D"/>
  <img src="https://img.shields.io/badge/Bash-0D0221?style=for-the-badge&logo=gnubash&logoColor=00F0FF"/>
</p>

<h3 align="center">BACKEND</h3>
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-0D0221?style=for-the-badge&logo=fastapi&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/Django-0D0221?style=for-the-badge&logo=django&logoColor=FF2A6D"/>
  <img src="https://img.shields.io/badge/Flask-0D0221?style=for-the-badge&logo=flask&logoColor=B026FF"/>
  <img src="https://img.shields.io/badge/Node.js-0D0221?style=for-the-badge&logo=nodedotjs&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/WebSockets-0D0221?style=for-the-badge&logo=socketdotio&logoColor=FF2A6D"/>
</p>

<h3 align="center">FRONTEND</h3>
<p align="center">
  <img src="https://img.shields.io/badge/React-0D0221?style=for-the-badge&logo=react&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/Astro-0D0221?style=for-the-badge&logo=astro&logoColor=FF2A6D"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-0D0221?style=for-the-badge&logo=tailwindcss&logoColor=B026FF"/>
  <img src="https://img.shields.io/badge/Vite-0D0221?style=for-the-badge&logo=vite&logoColor=FFE600"/>
</p>

<h3 align="center">DATA · DEVOPS · AI</h3>
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-0D0221?style=for-the-badge&logo=postgresql&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/Redis-0D0221?style=for-the-badge&logo=redis&logoColor=FF2A6D"/>
  <img src="https://img.shields.io/badge/MongoDB-0D0221?style=for-the-badge&logo=mongodb&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/Docker-0D0221?style=for-the-badge&logo=docker&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-0D0221?style=for-the-badge&logo=githubactions&logoColor=B026FF"/>
  <img src="https://img.shields.io/badge/Linux-0D0221?style=for-the-badge&logo=linux&logoColor=FFE600"/>
  <img src="https://img.shields.io/badge/OpenCode-0D0221?style=for-the-badge&logo=terminal&logoColor=00F0FF"/>
  <img src="https://img.shields.io/badge/LLM_Orchestration-0D0221?style=for-the-badge&logo=openai&logoColor=FF2A6D"/>
  <img src="https://img.shields.io/badge/MCP-0D0221?style=for-the-badge&logo=protocols&logoColor=B026FF"/>
</p>

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 03 ⟩ · FEATURED.PROJECTS</h2>

| ▸ PROYECTO | DESCRIPCIÓN | STACK | |
| :--- | :--- | :--- | :---: |
| **[lemoria](https://github.com/devcristianlopez/lemoria)** | Sistema Operativo de Memoria y Orquestación para Desarrollo con IA | `Python` `Agents` `MCP` | ![stars](https://img.shields.io/github/stars/devcristianlopez/lemoria?style=flat-square&color=FF2A6D&labelColor=0D0221) |
| **[core-odoo](https://github.com/devcristianlopez/core-odoo)** | Fábrica de software self-hosted sobre Odoo 20: entornos Git, módulos, frontends y observabilidad | `TypeScript` `Odoo` `Docker` | ![status](https://img.shields.io/badge/STATUS-NEW-FF2A6D?style=flat-square&labelColor=0D0221) |

<details>
<summary><b>▸ VER TODOS LOS REPOSITORIOS</b></summary>
<br/>

- **[livebridge](https://github.com/devcristianlopez/livebridge)** — SDK Python para TikTok LIVE con protocolo Webcast propio · `Python`
- **[manel](https://github.com/devcristianlopez/manel)** — Security Health Monitor para entornos de desarrollo · `TypeScript`
- **[guardian-live-monitor](https://github.com/devcristianlopez/guardian-live-monitor)** — Video, movimiento y alertas en tiempo real · `Python` `OpenCV`
- **[boilerplate-django](https://github.com/devcristianlopez/boilerplate-django)** — Django + PostgreSQL + Docker listo para producción · `Python`
- **[coffe-code](https://github.com/devcristianlopez/coffe-code)** — PWA para preparar el café perfecto ☕ · `TypeScript`
- **[chileonline](https://github.com/devcristianlopez/chileonline)** — Noticias de Chile estilo notas de parche MMORPG · `Astro`
- **[wardogs-chile-bot](https://github.com/devcristianlopez/wardogs-chile-bot)** — Discord bot + plataforma competitiva · `Python`
- **[falcon-control-hub](https://github.com/devcristianlopez/falcon-control-hub)** — Control hub · `Python`
- **[nomicon](https://github.com/devcristianlopez/nomicon)** — Compendios del lenguaje tecnológico
- **[cursoia](https://github.com/devcristianlopez/cursoia)** — Curso de Desarrollo con IA: OpenCode y Agentes · `HTML`
- **[lanedu](https://github.com/devcristianlopez/lanedu)** — Consultoría tecnológica y cumplimiento digital · `HTML`
- **[config](https://github.com/devcristianlopez/config)** — Configuración portable de Omarchy e infraestructura · `QML`
- **[skills-opencode](https://github.com/devcristianlopez/skills-opencode)** — Skills de Python y Django para OpenCode

</details>

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 04 ⟩ · SYSTEM.METRICS</h2>

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=devcristianlopez&theme=2077" alt="Profile details"/>
</div>

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=devcristianlopez&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0221&title_color=00F0FF&icon_color=FF2A6D&text_color=C9D1D9&rank_icon=github" alt="GitHub stats"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devcristianlopez&layout=compact&langs_count=8&hide_border=true&bg_color=0D0221&title_color=00F0FF&text_color=C9D1D9" alt="Top languages"/>
</div>

<div align="center">
  <img width="70%" src="https://streak-stats.demolab.com?user=devcristianlopez&hide_border=true&background=0D0221&ring=FF2A6D&fire=00F0FF&currStreakNum=FFFFFF&currStreakLabel=00F0FF&sideNums=FFFFFF&sideLabels=C9D1D9&dates=8B949E&stroke=B026FF" alt="Streak"/>
</div>

<div align="center">
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=devcristianlopez&theme=2077" alt="Repos per language"/>
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=devcristianlopez&theme=2077" alt="Most commit language"/>
  <img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=devcristianlopez&theme=2077&utcOffset=-3" alt="Productive time"/>
</div>

<div align="center">
  <!-- La serpiente aparece cuando corre .github/workflows/snake.yml y se crea la rama `output` -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devcristianlopez/devcristianlopez/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/devcristianlopez/devcristianlopez/output/github-contribution-grid-snake.svg"/>
    <img width="100%" alt="Snake animation" src="https://raw.githubusercontent.com/devcristianlopez/devcristianlopez/output/github-contribution-grid-snake-dark.svg"/>
  </picture>
</div>

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 05 ⟩ · CONNECT</h2>

<div align="center">
  <a href="https://github.com/devcristianlopez"><img src="https://img.shields.io/badge/GitHub-devcristianlopez-0D0221?style=for-the-badge&logo=github&logoColor=00F0FF"/></a>
  <a href="https://linkedin.com/in/cristianl0pez"><img src="https://img.shields.io/badge/LinkedIn-cristianl0pez-0D0221?style=for-the-badge&logo=linkedin&logoColor=00F0FF"/></a>
  <a href="https://lemoria.org/"><img src="https://img.shields.io/badge/Website-lemoria.org-0D0221?style=for-the-badge&logo=googlechrome&logoColor=FF2A6D"/></a>
  <a href="mailto:cristianlopezvalpo@gmail.com"><img src="https://img.shields.io/badge/Email-cristianlopezvalpo%40gmail.com-0D0221?style=for-the-badge&logo=gmail&logoColor=FF2A6D"/></a>
</div>

<br/>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Quote"/>
</div>

<div align="center">
  <sub><b>「 Primero lo haces funcionar. Después lo haces rápido. Después lo haces bonito. 」</b></sub>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=devcristianlopez&style=for-the-badge&color=FF2A6D&label=PROFILE+VIEWS"/>
</div>
