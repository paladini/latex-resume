# Fernando Paladini — Staff Software Engineer Resume

This repository contains my professional resume in LaTeX, focused on senior/staff engineering roles in backend platforms, AI-enabled developer productivity, and cloud-native systems.

## Why recruiters and hiring managers should care

I’m a Staff-level Software Engineer with 13+ years of experience delivering measurable business outcomes through software architecture, platform engineering, and technical leadership.

### Career highlights
- Led GenAI adoption and governance initiatives for an engineering organization with 3,000+ developers.
- Increased logistics throughput by **15%** with Go-based distributed services at Mercado Livre.
- Delivered and operated mission-critical GovTech systems with **99.9% uptime**.
- Built and maintain open-source AI tooling, including **mcp-me** (Model Context Protocol project).

### Core expertise
- **Backend & Architecture:** PHP, Node.js, Ruby on Rails, Go, Python, distributed systems, APIs.
- **Cloud & Platform:** AWS, Kubernetes, Terraform, CI/CD, observability.
- **AI Engineering:** GitHub Copilot enablement, MCP, LLM workflows, engineering metrics.

## Download the latest resume PDF

The latest compiled PDF is published automatically on every `main.tex` update:

- **Latest release:** `https://github.com/paladini/latex-resume/releases/tag/resume-latest`
- **Direct PDF link:** `https://github.com/paladini/latex-resume/releases/download/resume-latest/main.pdf`

## Source file

- `main.tex` — single source of truth for the resume.

## Local build (optional)

If you want to compile locally, install a LaTeX distribution with `latexmk` and run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

This produces `main.pdf` in the repository root.

## Automation

GitHub Actions compiles the resume and updates the `resume-latest` release whenever `main.tex` changes on `main`.
