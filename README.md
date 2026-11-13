# Hi, I'm [Ahmad](https://www.linkedin.com/in/idindev/)

I'm an AI engineer and the founder of [Idin Studio](https://idinstudio.com), a two-person AI integration studio in Bogor, Indonesia (UTC+7). I connect AI agents to products safely, through MCP servers and AI assistants with per-user access, confirmed writes and an audit log, and I build the SaaS around them. I've shipped production software since May 2018, starting the day after I finished vocational school.

Since 2025 I design the system, direct AI coding agents under rules and tests I write, and review every change.

## Open source

- [mcp-stdio-mux](https://github.com/techidin/mcp-stdio-mux) runs one shared process per stdio MCP server across every agent session, app and profile on a machine. Four serena sessions used about 202 MB with it, against 679 to 757 MB without it. It is on PyPI.
- [mcp-guarded-server](https://github.com/techidin/mcp-guarded-server) is a small reference MCP server with sign-in before any tool, tenant scoping in the server, confirmed writes, an audit log and a written threat model.

## Selected work

- Alpamayo GmbH, Switzerland (freelance via Upwork since September 2024, Full Stack Engineer). For PREKIT, their industrial data platform, I built the MCP server and AI assistant from the first version, secured with OAuth 2.1 and OpenID on Keycloak. On Alpamayo Intelligence, their device fleet platform, I led the UI/UX overhaul and closed the 32 findings of its UI/UX audit.
- PT Efisiensi Putra Utama, Indonesia (through Idin Studio, since 2025). The passenger ticketing app frontend for this intercity bus operator came first, then a fleet AI system. A YOLO26 model I fine-tuned on frames I labeled counts passengers from bus CCTV, and trips where the count is higher than tickets sold go to auditors. Counting runs in production.
- [Inviboo](https://inviboo.com), my own event SaaS on Go, Next.js and PostgreSQL. Features include invitations, offline QR check-in, a live console for the event host and payments on the DOKU payment gateway. Live with real users.
- InKanteen (2022 to 2024). I built the QR menu frontend and the point-of-sale backend, and the school catering and operator dashboard apps full stack.
- Redek, Colombia (2021 to 2022). I built the online dispute-resolution platform between people and banks end to end.
- Futuready, Aegon Group (2019 to 2021). Insurance platforms for Indonesia and Thailand, including passport OCR in 2020.

More case studies: [ahmadmuhyidin.my.id/work](https://ahmadmuhyidin.my.id/work)

## Stack

<img src="https://skillicons.dev/icons?i=py,fastapi,django,go,ts,nextjs,react,vue,nuxtjs,tailwind,nodejs,nestjs,postgres,mysql,redis,docker,cloudflare&perline=9" alt="Python, FastAPI, Django, Go, TypeScript, Next.js, React, Vue, Nuxt, Tailwind CSS, Node.js, NestJS, PostgreSQL, MySQL, Redis, Docker, Cloudflare" />

For AI work I use MCP (FastMCP, MCP Go SDK), LLM tool calling, YOLO, OpenCV and Label Studio. Infrastructure also includes Keycloak/SSO, MQTT and Prometheus/Grafana.

## Work with me

Contract, fractional or full-time, up to 40 hours a week, remote. I reply within one working day, often within 4 hours. Tell me what your system does today and what you want AI to do in it.

<div align="center">
  <a href="mailto:ahmad@idinstudio.com" target="_blank"><img src="https://img.shields.io/badge/Email-black?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  <a href="https://ahmadmuhyidin.my.id" target="_blank"><img src="https://img.shields.io/badge/Website-black?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://linkedin.com/in/idindev" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-black?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.upwork.com/freelancers/~01e4b82d69dc728ba3" target="_blank"><img src="https://img.shields.io/badge/Upwork-black?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork" /></a>
  <a href="https://x.com/idindev" target="_blank"><img src="https://img.shields.io/badge/X-black?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/techidin/techidin/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/techidin/techidin/output/github-snake.svg" />
  <img alt="A snake eating Ahmad's GitHub contribution graph" src="https://raw.githubusercontent.com/techidin/techidin/output/github-snake-dark.svg" />
</picture>
