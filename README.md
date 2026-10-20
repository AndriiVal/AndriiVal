# Hi, I'm Andrii 👋

**Ruby on Rails Backend Engineer · API Reliability & LLM Integrations**

I'm a backend engineer with **5+ years of professional experience** building and maintaining Ruby on Rails applications. I work with PostgreSQL-backed services, REST APIs, third-party integrations, and existing systems that need to stay reliable and maintainable.

My current focus is **reliable AI integrations**: predictable retries and timeouts, strict response validation, privacy-conscious observability, and testable provider boundaries.

## Featured project — Rails AI Reliability Lab

### [Rails AI Reliability Lab](https://github.com/AndriiVal/rails-ai-reliability-lab)

A **reproducible, local-only Rails engineering lab** demonstrating how to handle unreliable LLM APIs safely. It uses synthetic support tickets and a deterministic Fake Provider by default; the browser dashboard never makes a paid LLM request.

<a href="https://github.com/AndriiVal/rails-ai-reliability-lab">
  <img src="https://raw.githubusercontent.com/AndriiVal/rails-ai-reliability-lab/master/docs/images/dashboard-desktop.png" alt="Rails AI Reliability Lab — simulated reliability dashboard" width="680">
</a>

- **Resilience:** bounded retries, `Retry-After`, typed failures, an 8-second per-attempt budget and a 25-second overall cooperative deadline.
- **Provider design:** eight repeatable failure scenarios; optional, explicitly enabled Anthropic Ruby SDK adapter with SDK retries disabled and independent JSON-schema validation.
- **Privacy and observability:** metadata-only PostgreSQL runs, allowlisted Rails structured events, Basic Auth, CSRF protection, and escaped browser output.
- **Verification:** 396 passing RSpec examples in the final October 2026 portfolio audit, with RuboCop and Brakeman checks passing in GitHub Actions.

**Explore:** [Architecture](https://github.com/AndriiVal/rails-ai-reliability-lab/blob/master/docs/ARCHITECTURE.md) · [Simulated engineering audit](https://github.com/AndriiVal/rails-ai-reliability-lab/blob/master/docs/AUDIT_REPORT.md) · [3–5 minute walkthrough](https://github.com/AndriiVal/rails-ai-reliability-lab/blob/master/docs/DEMO_GUIDE.md) · [CI](https://github.com/AndriiVal/rails-ai-reliability-lab/actions)

*This is a synthetic engineering demonstration, not a production deployment or a real-world model-accuracy benchmark. Live Anthropic behavior has not been verified.*

## Other selected projects

- **[Fitness Tracker](https://github.com/AndriiVal/fitness_tracker)** — Rails workout tracking with Devise authentication, exercises, training sets, and charts.
- **[File Sorter](https://github.com/AndriiVal/file-sorter)** — a desktop utility for organizing files.
- **[20-20-20 Rule](https://github.com/AndriiVal/20-20-20-rule)** — a small Linux screen-break reminder script.
- **[Hieroglyphic Name](https://github.com/AndriiVal/hieroglyphic-name)** — a creative web experiment inspired by Egyptian hieroglyphics.

## Technical focus

- **Backend:** Ruby, Rails, REST APIs, PostgreSQL, application maintenance and modernization
- **Reliability & integrations:** retry/backoff policies, deadline management, Stripe, third-party APIs, LLM provider adapters
- **Testing & tooling:** RSpec, WebMock, GitHub Actions, RuboCop, Brakeman, Docker, Git, Linux
- **AI development:** LLM application architecture, Claude Code, OpenAI Codex, MCP

## Certification

**Claude Certified Architect — Foundations (CCA-F)**, Anthropic.

Outside software, I enjoy electronics, microcontrollers, guitars, and experimental builds.
