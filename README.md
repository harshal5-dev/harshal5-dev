<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0369a1,100:0f766e&height=210&section=header&text=Harshal%20Ganbote&fontSize=46&fontColor=ffffff&fontAlignY=35&desc=Full-Stack%20Developer%20%E2%80%A2%20Go%20%E2%80%A2%20React%20%E2%80%A2%20PostgreSQL&descSize=19&descAlignY=56&animation=fadeIn" alt="Harshal Ganbote banner" />

### Designing scalable systems — and shipping them end-to-end, from database to UI

[![Portfolio](https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://harshalganbote.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0369a1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshal-ganbote)
[![Email](https://img.shields.io/badge/Email-0f766e?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshalganbote55@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=harshal5-dev&style=for-the-badge&color=0369a1&label=PROFILE+VIEWS)](https://github.com/harshal5-dev)

</div>

## About Me

I am a full-stack developer who builds production-minded web applications with **Go**, **PostgreSQL**, and **React** — and I treat **system design (HLD/LLD)** as part of the job, not a separate subject. I enjoy modeling real domains, designing clean REST APIs, and connecting them to fast, responsive interfaces.

- Shipped **Farm Deck**, a multi-tenant farm operations SaaS — fields, hydroponic systems, daily logs, reminders, and reports.
- Now designing **Tandav**, a background job processing system, and a third project is already in the works.
- Practicing system design, data structures, and algorithms to keep my fundamentals sharp.
- Open to collaborating on full-stack products, Go services, and developer tools.

## Featured Projects

<!-- To add Project 03 later: copy one of the blocks below, bump the number, and fill in the details. -->

### 01 · Farm Deck — Multi-Tenant Farm Operations SaaS

> The farm command-deck: fields, hydroponic systems, daily logs, reminders, and reports for a portfolio farm SaaS.

[![Repo](https://img.shields.io/badge/Repo-farm--deck-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/harshal5-dev/farm-deck)
[![Live Demo](https://img.shields.io/badge/Live_Demo-0f766e?style=flat-square&logo=firefoxbrowser&logoColor=white)](https://farm-deck-client-izzchc-83a7b4-167-233-74-73.sslip.io)
[![License](https://img.shields.io/badge/License-MIT-0f172a?style=flat-square)](https://github.com/harshal5-dev/farm-deck/blob/main/LICENSE)

**Stack:** Go, PostgreSQL, React, GitHub Actions

Key engineering areas:

- Multi-tenant architecture — one deployment serving many farm tenants with isolated data.
- Monorepo layout with separate `backend`, `frontend`, and `docs` spaces.
- REST API design and PostgreSQL schema modeling for real farm operations.
- CI pipeline with GitHub Actions and a live deployed preview; architecture documented with diagrams.

### 02 · Tandav — Background Job Processing System

> Named for Shiva's cosmic dance: jobs cycle through creation, execution, and completion — millions of times over, never missing a beat.

[![Repo](https://img.shields.io/badge/Repo-tandav-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/harshal5-dev/tandav)
[![Status](https://img.shields.io/badge/Status-in__active__development-f59e0b?style=flat-square)](https://github.com/harshal5-dev/tandav)

Currently being designed and built in the open:

- Reliable job lifecycle — enqueueing, execution, completion, and failure handling.
- Durability and observability questions every job system has to answer.

*Project 03 is underway — more soon.*

## System Design

I practice both sides of system design and back it with real projects:

| Area | What I practice | Where to see it |
|:---|:---|:---|
| High-Level Design | Multi-tenancy, API layering, deployment topology, CI/CD | [farm-deck](https://github.com/harshal5-dev/farm-deck) architecture diagrams |
| Low-Level Design | Schema modeling, RBAC, module boundaries in Go | [farm-deck](https://github.com/harshal5-dev/farm-deck) |
| Background Processing | Job lifecycle, queues, reliability, retries | [tandav](https://github.com/harshal5-dev/tandav) |

## Current Stack

<div align="center">

### Backend

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-0f172a?style=for-the-badge&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-111827?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0f172a?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8)

### Data and Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![sqlc](https://img.shields.io/badge/sqlc-1f2937?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

## More Projects

| Project | What it demonstrates | Stack |
|:---|:---|:---|
| [Go Complete Guide](https://github.com/harshal5-dev/go-complete-Guide) | Hands-on Go fundamentals, concurrency, data structures, and REST API exercises | Go |
| [Learn Go](https://github.com/harshal5-dev/learn-go) | My journey learning Go — fundamentals, syntax, and hands-on practice exercises | Go |

## How I Build

```go
type Developer struct {
	Name       string
	Focus      []string
	Principles []string
}

harshal := Developer{
	Name:  "Harshal Ganbote",
	Focus: []string{
		"Go APIs",
		"React applications",
		"PostgreSQL systems",
		"system design (HLD & LLD)",
	},
	Principles: []string{
		"keep boundaries clear",
		"design for real users",
		"measure before optimizing",
		"learn by shipping",
	},
}
```

## GitHub Activity

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=harshal5-dev&theme=github_dark" alt="Harshal's GitHub stats" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=harshal5-dev&theme=github_dark" alt="Harshal's most used languages" />

<img height="170" src="https://streak-stats.demolab.com/?user=harshal5-dev&theme=github-dark&hide_border=true" alt="Harshal's GitHub streak" />

<img width="95%" src="https://ghchart.rshah.org/0369a1/harshal5-dev" alt="Harshal's contribution graph" />

</div>

## Let's Connect

I am interested in **Go backend development**, **full-stack applications**, **API and system design**, and **open-source collaboration**. The best way to reach me is through [email](mailto:harshalganbote55@gmail.com) or [LinkedIn](https://www.linkedin.com/in/harshal-ganbote).

<div align="center">

**Build clearly. Learn continuously. Ship useful software.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,50:0369a1,100:0f172a&height=110&section=footer" alt="Footer" />

</div>
