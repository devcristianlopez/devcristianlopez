<div align="center">
  <img src="./assets/header.svg" width="100%" alt="devcristianlopez — Full Stack Developer"/>
</div>

<div align="center">
  <a href="https://github.com/devcristianlopez">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=900&color=00F0FF&center=true&vCenter=true&width=900&lines=%3E+booting+developer.profile...;%3E+full-stack+%2F%2F+ai+orchestration+%2F%2F+automation;%3E+building+tools+that+think%2C+automate+and+scale;%3E+open+to+collaborate+%3C%2F%3E" alt="Typing SVG"/>
  </a>
</div>

<p align="center">
  <img alt="STATUS" src="https://img.shields.io/badge/STATUS-ONLINE-00F0FF?style=for-the-badge&labelColor=0D0221"/>
  <img alt="LOCATION" src="https://img.shields.io/badge/LOCATION-TODO-FF2A6D?style=for-the-badge&labelColor=0D0221"/>
  <img alt="FOLLOWERS" src="https://img.shields.io/github/followers/devcristianlopez?style=for-the-badge&color=B026FF&labelColor=0D0221&label=FOLLOWERS"/>
  <img alt="STARS" src="https://img.shields.io/github/stars/devcristianlopez?style=for-the-badge&color=00F0FF&labelColor=0D0221&label=STARS"/>
</p>

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

```console
┌──(devcristianlopez㉿github)-[~]
└─$ whoami
> Full Stack Developer · AI Orchestration · Automation

└─$ cat mission.txt
"Construyo sistemas que piensan, automatizan y escalan."
```

<div align="center">
  <img src="./assets/divider.svg" width="100%" alt=""/>
</div>

<h2 align="center">⟨ 01 ⟩ · SYSTEM.PROFILE</h2>

> Mi perfil, pero como código. Copia la idea, cambia los `TODO` y hazla tuya.

```python
from dataclasses import dataclass
from typing import ClassVar


@dataclass(slots=True)
class Developer:
    """Perfil vivo: identidad, stack y proyectos en un solo objeto."""

    # ── identidad ──────────────────────────────────────────────────────────
    username: str = "devcristianlopez"
    name: str = "TODO: Tu Nombre"
    role: str = "Full Stack Developer & AI Orchestration"
    location: str = "TODO: Ciudad, País"
    email: str = "TODO: tu@email.com"

    # ── links ──────────────────────────────────────────────────────────────
    web: str = "TODO: https://tu-web.dev"
    linkedin: str = "TODO: https://linkedin.com/in/tu-usuario"
    x: str = "TODO: https://x.com/tu-usuario"
    youtube: str = "TODO: https://youtube.com/@tu-canal"

    # ── stack ──────────────────────────────────────────────────────────────
    languages: ClassVar[tuple[str, ...]] = ("Python", "TypeScript", "JavaScript", "SQL", "Bash")
    backend: ClassVar[tuple[str, ...]] = ("FastAPI", "Django", "Flask", "Node.js", "WebSockets")
    frontend: ClassVar[tuple[str, ...]] = ("React", "Astro", "Tailwind CSS", "Vite")
    data: ClassVar[tuple[str, ...]] = ("PostgreSQL", "Redis", "SQLite", "MongoDB")
    devops: ClassVar[tuple[str, ...]] = ("Docker", "GitHub Actions", "Nginx", "Linux")
    ai: ClassVar[tuple[str, ...]] = ("OpenCode", "LLM orchestration", "RAG", "MCP", "Agents")

    # ── proyectos ──────────────────────────────────────────────────────────
    projects: ClassVar[dict[str, str]] = {
        "lemoria":               "Memory & Orchestration OS for AI-assisted development",
        "livebridge":            "TikTok LIVE SDK for Python · custom Webcast protocol",
        "manel":                 "Security health monitor for dev environments",
        "guardian-live-monitor": "OpenCV + FastAPI + WebSockets live surveillance",
        "boilerplate-django":    "Django + PostgreSQL + Docker, production ready",
        "coffe-code":            "PWA to brew the perfect coffee ☕",
    }

    # ── estado actual ──────────────────────────────────────────────────────
    learning: ClassVar[tuple[str, ...]] = ("Agent architectures", "Observability", "Rust")
    open_to: str = "colaboraciones · freelance · open source"
    coffee_level: int = 99  # ☕☕☕

    def __str__(self) -> str:
        return f"{self.name} · {self.role} · {self.location}"

    def greet(self) -> str:
        return f"Hey, soy {self.name}. Construyo cosas que funcionan y se ven bien."


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
| **[livebridge](https://github.com/devcristianlopez/livebridge)** | SDK Python que conecta TikTok LIVE y normaliza eventos en tiempo real | `Python` `Webcast` `WS` | ![stars](https://img.shields.io/github/stars/devcristianlopez/livebridge?style=flat-square&color=00F0FF&labelColor=0D0221) |
| **[manel](https://github.com/devcristianlopez/manel)** | Security Health Monitor para entornos de desarrollo 🛡️ | `TypeScript` `CLI` | ![stars](https://img.shields.io/github/stars/devcristianlopez/manel?style=flat-square&color=B026FF&labelColor=0D0221) |
| **[guardian-live-monitor](https://github.com/devcristianlopez/guardian-live-monitor)** | Video, movimiento y alertas en tiempo real sin recargar página | `Python` `OpenCV` `FastAPI` | ![stars](https://img.shields.io/github/stars/devcristianlopez/guardian-live-monitor?style=flat-square&color=FF2A6D&labelColor=0D0221) |
| **[boilerplate-django](https://github.com/devcristianlopez/boilerplate-django)** | Django + PostgreSQL + Docker, auth por email y setup automatizado | `Python` `Django` `Docker` | ![stars](https://img.shields.io/github/stars/devcristianlopez/boilerplate-django?style=flat-square&color=00F0FF&labelColor=0D0221) |
| **[coffe-code](https://github.com/devcristianlopez/coffe-code)** | PWA para preparar café perfecto: V60, Chemex, prensa francesa ☕ | `TypeScript` `PWA` | ![stars](https://img.shields.io/github/stars/devcristianlopez/coffe-code?style=flat-square&color=B026FF&labelColor=0D0221) |

<details>
<summary><b>▸ VER TODOS LOS REPOSITORIOS</b></summary>
<br/>

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
  <a href="TODO"><img src="https://img.shields.io/badge/LinkedIn-TODO-0D0221?style=for-the-badge&logo=linkedin&logoColor=00F0FF"/></a>
  <a href="TODO"><img src="https://img.shields.io/badge/X_/_Twitter-TODO-0D0221?style=for-the-badge&logo=x&logoColor=FFFFFF"/></a>
  <a href="TODO"><img src="https://img.shields.io/badge/Website-TODO-0D0221?style=for-the-badge&logo=googlechrome&logoColor=FF2A6D"/></a>
  <a href="mailto:TODO"><img src="https://img.shields.io/badge/Email-TODO-0D0221?style=for-the-badge&logo=gmail&logoColor=FF2A6D"/></a>
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
