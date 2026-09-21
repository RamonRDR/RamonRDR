<div align="center">

# Ramon Rodriguez

### Software Developer · Python · Automation · APIs · SAP · AI & Data

I build reliable software that turns complex business processes into maintainable, testable automation.

**Brazil · Open to remote international opportunities**

<a href="https://www.linkedin.com/in/ramon-e-rodriguez/">
  <img src="https://img.shields.io/badge/LinkedIn-Ramon%20Rodriguez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/RamonRDR">
  <img src="https://img.shields.io/badge/GitHub-RamonRDR-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

## About me

My background sits at the intersection of **software engineering, automation, enterprise systems, and accounting domain expertise**.

I started by solving real operational problems and gradually turned those solutions into structured software: reusable modules, SAP automations, API integrations, desktop applications, CI pipelines, automated tests, technical documentation, and production-oriented recovery flows.

Today, my main focus is **Python development, backend and API engineering, AI-assisted software development, automation, and quality-oriented engineering**.

I care about software that is not only able to run, but also able to be **understood, tested, reviewed, recovered, and maintained**.

---

## Engineering toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/SAP%20ECC%20%2F%20BPC-0FAAFF?style=flat-square&logo=sap&logoColor=white" alt="SAP ECC / BPC" />
  <img src="https://img.shields.io/badge/Flet-02569B?style=flat-square" alt="Flet" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab CI" />
</p>

**What I usually work on:** business automation · backend services · APIs · SAP integration · desktop tools · testing · CI/CD · technical documentation · AI-assisted engineering

---

## Selected impact

- Reduced selected enterprise accounting routines from **30–40 minutes to ~3 minutes per company** through automation.
- Helped remove **20+ person-hours of repetitive monthly work** across accounting operations.
- Evolved an internal automation platform into a structured software product with **2,754 passing automated tests**, CI, controlled releases, recovery mechanisms, and documented architecture.
- Built solutions that connect **Python, SAP ECC, SAP BPC/EPM, APIs, enterprise service workflows, filesystem operations, and evidence generation**.
- Applied software engineering practices to operational finance problems where reliability, traceability, and safe failure behavior matter as much as speed.

---

## BAS architecture at a glance

The diagram below is a **sanitized, high-level view** of the architecture. It intentionally excludes proprietary business rules, credentials, infrastructure details, and internal configuration.

```mermaid
flowchart LR
    U[Accounting User] --> UI[Flet Desktop UI]
    UI --> S[Application Services]

    S --> SAP[SAP ECC]
    S --> BPC[SAP BPC / EPM]
    S --> API[APIs / ServiceNow]

    SAP --> E[Evidence & Recovery]
    BPC --> E
    API --> E
    S --> E

    E --> O[Logs · Files · Audit Evidence]
```

The key design idea is to keep **business rules and orchestration outside the UI**, isolate integration concerns, and make execution recoverable and auditable.

---

## Selected engineering work

<table>
<tr>
<td width="50%" valign="top">

<h3>Business Accounting Suite (BAS)</h3>

<p>
  <img src="https://img.shields.io/badge/PRIVATE-Enterprise%20Project-555555?style=flat-square" alt="Private enterprise project" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Flet-02569B?style=flat-square" alt="Flet" />
  <img src="https://img.shields.io/badge/SAP-ECC%20%2F%20BPC-0FAAFF?style=flat-square&logo=sap&logoColor=white" alt="SAP" />
</p>

<p>
A modular desktop automation platform built for enterprise accounting operations.
It grew from individual automation routines into a governed software product with reusable services, SAP integration, structured releases, automated testing, CI, recovery mechanisms, and technical documentation.
</p>

<p>
<strong>Engineering highlights:</strong> SAP GUI automation, SAP BPC/EPM, ServiceNow/WBS integration design, multi-session orchestration, evidence generation, controlled packaging, Spec-Driven Development, and production-oriented fail-safe behavior.
</p>

<p>
The current documented baseline reached <strong>2,754 passing automated tests</strong>, plus 275 skipped tests and 30 passing subtests in its final CI gate.
</p>

<p><em>Repository is private because it contains enterprise project material. This profile presents only a public technical summary.</em></p>

</td>
<td width="50%" valign="top">

<h3>Manolo Contabilidade</h3>

<p>
  <img src="https://img.shields.io/badge/PRIVATE-Source%20Code-555555?style=flat-square" alt="Private source code" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

<p>
A production website built with <strong>Next.js 14, TypeScript, and Tailwind CSS</strong>, including a deployment workflow designed for real-world shared hosting constraints.
</p>

<p>
The project includes local production builds, cPanel packaging, PM2 process configuration, server startup scripts, deployment documentation, and operational maintenance procedures.
</p>

<p><em>Source repository is private. The live website is publicly available below.</em></p>

<p>
<a href="https://manolocontabilidade.com.br"><strong>Visit live website →</strong></a>
</p>

</td>
</tr>

<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/RamonRDR/fullstack-calculator">Full-Stack Calculator</a></h3>

<p>
  <img src="https://img.shields.io/badge/PUBLIC-Repository-2EA44F?style=flat-square" alt="Public repository" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

<p>
A small full-stack application designed around correctness, readability, testability, and clear separation of concerns.
</p>

<p>
The React frontend communicates with a Go REST API while domain logic remains isolated from the HTTP layer. The repository includes validation, backend and frontend tests, technical design documentation, production builds, and GitHub Actions quality gates.
</p>

<p>
  <img src="https://img.shields.io/github/stars/RamonRDR/fullstack-calculator?style=flat-square" alt="GitHub stars" />
  <img src="https://img.shields.io/github/forks/RamonRDR/fullstack-calculator?style=flat-square" alt="GitHub forks" />
</p>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/RamonRDR/python-study-guide">Python Study Guide</a></h3>

<p>
  <img src="https://img.shields.io/badge/PUBLIC-Repository-2EA44F?style=flat-square" alt="Public repository" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/EN%20%7C%20PT--BR%20%7C%20ES-Multilingual-blue?style=flat-square" alt="Multilingual" />
</p>

<p>
A multilingual Python learning and reference project built as a structured engineering repository rather than a loose collection of notes.
</p>

<p>
It combines concept explanations, practical examples, exercises, automated tests, practical projects, documentation standards, contribution guidelines, localization, and an explicit AI-assisted development workflow.
</p>

<p>
  <img src="https://img.shields.io/github/stars/RamonRDR/python-study-guide?style=flat-square" alt="GitHub stars" />
  <img src="https://img.shields.io/github/forks/RamonRDR/python-study-guide?style=flat-square" alt="GitHub forks" />
</p>

</td>
</tr>
</table>

---

## How I approach engineering

I tend to work from the problem outward:

- understand the business rule before automating it;
- separate domain logic from interfaces and infrastructure;
- make failures explicit instead of hiding them;
- create automated tests around critical behavior;
- use CI as evidence, not as a substitute for validation;
- document architectural decisions and operational constraints;
- design recovery and observability as part of the system, not as afterthoughts;
- use AI tools as engineering accelerators while keeping human review, testing, and accountability in the loop.

That mindset comes from working on software where a "small script" can eventually become part of a real operational process.

---

## Education & languages

**Education**

- **B.Sc. in Computer Science — UNISOCIESC** · In progress
- **Postgraduate specialization in Artificial Intelligence, Machine Learning & Big Data** · Completed in 2026

**Languages**

- **Portuguese:** Native
- **English:** Intermediate
- **Spanish:** Good comprehension

---

## Areas I am especially interested in

`Python` · `Backend Engineering` · `Automation` · `AI / Agents` · `APIs` · `QA & Test Automation` · `Enterprise Integrations` · `Developer Tooling`

I am particularly interested in roles where software engineering meets **automation, AI, data, integrations, or complex business workflows**.

---

<div align="center">

### Let's connect

If you are working on Python, automation, backend systems, AI-enabled products, or enterprise integrations, feel free to reach out.

<a href="https://www.linkedin.com/in/ramon-e-rodriguez/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
</a>

</div>
