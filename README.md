# Matías García

**Full Stack Engineer at Bettergy, an energy-tech product company.** I build products end to end, from the database to the deploy: Django and PostgreSQL on the back, Next.js and TypeScript on the front, Docker and Kubernetes to run it, and Claude Code in the loop to ship faster without dropping quality.

I lead a team of five technically (architecture, code reviews, standards), and the three juniors I onboarded each shipped to production in their first month.

## Impact

Production numbers from my work at Bettergy:

- **Live in under two months.** Built MIOT Sentra, an IoT monitoring platform for energy installations, from scratch with one other developer: **10+ clients and 100+ connected devices** in its first six months.
- **~3× more tickets per sprint** (about 10 → 30, testing and QA included) after bringing in an AI-assisted workflow with Claude Code.
- **Releases from twice a month to once or twice a week**, and tickets passing QA first time from 5–7 out of 10 to 8–9, after adding linters, formatters and strict test rules.
- **90 s → 1 s** on a core endpoint by rewriting Django ORM code: from up to 6,000 database calls per request down to 7.
- **€1,500 → €800 a month** in infrastructure by automating the cleanup of stale Velero backups on Kubernetes.

## Featured projects

### [ai-personal-coach](https://github.com/matgarfer499/ai-personal-coach)

An evidence-based personal trainer and nutrition coach that runs inside Claude Code, for healthy adults who want a lasting change in body and health. Claude does the conversation; every number (calories, macros, heart-rate zones, loads, weight trend) comes from a tested Python CLI, so the model never does the maths in its head. Every piece of advice traces back to one of 469 graded rules backed by 890 sources, and safety flags from the health screening are enforced in code.

**Stack:** Python 3.12 · uv · pytest · Ruff · Claude Code skills

<img src="https://raw.githubusercontent.com/matgarfer499/ai-personal-coach/main/assets/demo.gif" alt="Terminal demo: coach macros, a squat load increase, then a cardiac symptom stops all training" width="100%">

### [portfolio-web](https://github.com/matgarfer499/portfolio-web) · [live](https://matiasgarcia.dev)

My portfolio, built as a sports poster: the career read like an athlete's record board, for engineers and clients who want the numbers first. Every section is server-rendered and readable without JavaScript, all motion is CSS and stops with `prefers-reduced-motion`, and feature folders never import each other (ESLint enforces it). There are six hidden trophies if you go looking.

**Stack:** Next.js 16 · React 19 · TypeScript · Tailwind CSS 4 · Vitest · Playwright + axe · Vercel

## Stack

- **Product / frontend:** TypeScript, React, Next.js, Tailwind CSS, SvelteKit
- **Backend / data:** Python, Django, Django REST Framework, FastAPI, Celery, Redis, PostgreSQL, TimescaleDB
- **Infra:** Docker, Kubernetes, GitLab CI, Flux, Grafana, Prometheus, Loki, Sentry
- **AI tooling:** Claude Code, every day: skills, hooks and a test-first workflow

## Contact

[LinkedIn](https://www.linkedin.com/in/mgarfer/) · [mjgarciadev14@gmail.com](mailto:mjgarciadev14@gmail.com) · [matiasgarcia.dev](https://matiasgarcia.dev)
