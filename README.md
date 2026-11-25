<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:7c3aed&height=220&section=header&text=Manakasina%20Judica%C3%ABl&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Full-stack%20developer%20%C2%B7%20Antsirabe%2C%20Madagascar&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="banner"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=640&lines=Spring+Boot+%2B+Angular%2C+end+to+end;Lead+dev+of+team+VVS;Built+a+workflow+engine+for+a+national+tax+office;Trains+neural+nets+to+play+chess+like+you+do" alt="typing"/></a>

<p>
  <a href="https://www.linkedin.com/in/manakasina-judica%C3%ABl-jean-francois-3927aa30b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:judicaeljeanfrancois@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=ManaJudy&style=for-the-badge&color=1e3a8a&label=PROFILE+VIEWS" alt="views"/>
</p>

</div>

---

### `$ whoami`

```yaml
name:      Manakasina Judicaël JEAN FRANCOIS
role:      Full-stack developer · Lead dev @ VVS (Virtual Vision Synergy)
school:    IT University, Antananarivo — final year of Bachelor's (L3)
based_in:  Antsirabe, Madagascar
core:      [Java, Spring Boot, Angular, PostgreSQL, Docker]
now:       [Valimbavaka ERP, ODC Champions 2026, learning AWS]
speaks:    [Malagasy, French, English]
```

I build business software that real people use every day: workflow engines, ERPs, internal tools. I like the parts most people skip, like migrations, test coverage, CI pipelines and the edge cases nobody asked about.

<br/>

## Highlights

<table>
<tr>
<td width="50%" valign="top">

### DGE Flow
<sub>Internship · Direction des Grandes Entreprises (Ministry of Economy & Finance) · Aug–Nov 2026</sub>

Mail and case management for Madagascar's large-taxpayer office. Built **solo**, from the requirements to the production setup.

- **Configurable workflow engine**: routing, validation levels, timers and alerts. Admins redesign circuits in a graphical designer without touching code
- Deadlines in business days, with alerts at 80% and 100%, a Kanban board that follows the circuit, and KPI dashboards
- **On-premise AI** (Ollama + Spring AI): pre-fills a case from a scanned letter, and a RAG assistant answers questions over 21 procedure sheets plus live data
- **1,786 tests**, 85% back-end and 81% front-end line coverage
- 46-table schema versioned with Liquibase, real-time notifications over WebSocket

<sub>`Spring Boot 4` `Java 21` `Angular 22` `PostgreSQL` `Redis` `Ollama` `Docker` `Caddy`</sub>
<br/><sub>Private, government project</sub>

</td>
<td width="50%" valign="top">

### ChessClone
<sub>Personal project · ML</sub>

Give it a Chess.com username and it trains a neural network that plays **like that person**, not like Stockfish. Then you play against the clone.

- SE-ResNet policy network inspired by **Maia Chess**, pre-trained on Lichess games and fine-tuned per player
- On Hikaru's games, the clone predicts **51.7%** of his exact moves (top-1) and **80.4%** in the top-3
- Whole pipeline (download, dataset, training) fits a **30-minute budget enforced by the code**
- Dataset lives directly in VRAM, with bf16 and `channels_last` (+24% throughput). Every tuning choice was benchmarked, including the ones that didn't make it
- Personal opening book, test-time augmentation, live progress over SSE

<sub>`PyTorch` `CUDA` `FastAPI` `React` `TypeScript` `Docker`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Valimbavaka ERP
<sub>Team VVS · I'm lead dev · 2026, in progress</sub>

ERP for a cosmetics company: purchasing, sales, stock, production and delivery.

- **Offline-first** frontend: an outbox queue in IndexedDB replays requests in FIFO order with an `Idempotency-Key`, and the server enforces idempotency
- Security layer with JWT and refresh tokens, rate limiting, account lockout, permission annotations and an append-only audit journal (cancel and reverse, never delete)
- Architecture enforced by ArchUnit, integration tests on Testcontainers
- **9 GitHub Actions workflows**: CI, convention checks, Qodana, image builds, deploys to QA, staging and prod
- I set up the team conventions, review every PR and maintain the CI

<sub>`Spring Boot 4` `Java 21` `Angular 22` `PostgreSQL` `Liquibase` `GitHub Actions`</sub>

</td>
<td width="50%" valign="top">

### Marshal Editor
<sub>Personal project · zero dependencies</sub>

A browser-based editor for **Ruby Marshal 4.8** files: RPG Maker XP/VX/Ace data, Pokémon Essentials and PSDK saves, anything produced by `Marshal.dump`.

- Hand-written parser and writer that **round-trip byte for byte**, preserving shared object references, symbol tables, Ruby 1.8 floats and bignums
- Edits zlib-compressed game scripts in place and decodes RGSS `Table`, `Color`, `Tone` and `Rect`
- Virtualized tree, regex search, unlimited undo and a hex diff of every change
- **45 round-trip tests** run at Docker build time, so a failing test means no image. Fixtures were checked against Ruby 2.7 and 3.3

<sub>`Vanilla JS` `HTML/CSS` `nginx` `Docker`</sub>

</td>
</tr>
</table>

<br/>

## Also

| | |
|---|---|
| **1st place, IT University hackathon (2026)** | My team won the redesign of the university's website against the whole cohort. Now being deployed. |
| **Enterprise ERP** (2025–2026) | Academic project covering purchasing, sales, stock, CRM, HR, recruitment and time tracking, with a KPI dashboard. Spring Boot, Angular and PostgreSQL. |
| **ODC Champions 2026** | Competing in Orange Digital Center × CodinGame with my team. |

<br/>

## Stack

<div align="center">

**Daily drivers**
<br/><br/>
<img src="https://skillicons.dev/icons?i=java,spring,angular,ts,postgres,redis,docker,git,linux&theme=dark" alt="core stack"/>

<br/><br/>

**Also shipped with**
<br/><br/>
<img src="https://skillicons.dev/icons?i=react,vue,cs,dotnet,mysql,js,html,css,githubactions&theme=dark" alt="other stack"/>

<br/><br/>

**Learning**
<br/><br/>
<img src="https://skillicons.dev/icons?i=aws&theme=dark" alt="learning"/>

</div>

<br/>

## Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ManaJudy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ManaJudy&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages"/>

<img src="https://streak-stats.demolab.com?user=ManaJudy&theme=tokyonight&hide_border=true" alt="streak"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ManaJudy&theme=tokyo-night&hide_border=true&area=true" alt="activity graph"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ManaJudy/ManaJudy/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ManaJudy/ManaJudy/output/github-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/ManaJudy/ManaJudy/output/github-snake.svg"/>
</picture>

</div>

<br/>

<div align="center">

<sub>Off-screen: playing chess, which explains ChessClone.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:1e3a8a,100:0f172a&height=120&section=footer" width="100%" alt="footer"/>

</div>