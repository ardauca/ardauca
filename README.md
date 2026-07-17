# Hi there, I'm Arda Uça 👋

<p align="left">
  <a href="https://www.linkedin.com/in/arda-u%C3%A7a-ba5482310/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

Mathematics and Computer Science student at **Eskişehir Osmangazi University**, following a structured, project-based roadmap toward becoming a **Backend Software Engineer with AI & Cloud skills**.

I learn by building real projects rather than following isolated tutorials. Each project represents a new stage of my backend journey—from file-based applications to database integration, APIs, and AI-powered workflows.

---

# 🚀 Featured Projects

## 🤖 [Manga Translator](https://github.com/ardauca/manga_translator)
**AI-powered manga translation platform**

An AI-powered local-first application for translating manga pages from Japanese and English into Turkish using OCR and machine translation.

### Key Features
- **Manual speech bubble selection** via mouse drag on a custom Chrome extension interface.
- **Local OCR execution** using **PaddleOCR** running on the backend (FastAPI).
- **Advanced preprocessing** of images using **OpenCV** to improve OCR accuracy.
- **Bilingual target translations** powered by `deep-translator` using a free web-backed flow.
- **In-memory cache** on the backend to prevent repeated translations of identical segments.

**Tech Stack:** `Python` `FastAPI` `PaddleOCR` `OpenCV` `deep-translator` `JavaScript` `Chrome Extension API`

---

## 🌐 [SASTEK Official Website](https://github.com/ardauca/sastek-new-site)
**Official corporate web platform for SASTEK (Eskişehir Technical University Defense Industry and Technologies Club)**

A fully static, highly performant web application designed for student club representation and event management.

### Key Features
- **Fully static generation** built using the **Astro** framework.
- **Modern responsive styles** implemented via **Tailwind CSS v4**.
- **SEO-oriented architecture** with optimized meta tags, structured layout, and fast loading.
- **Content management workflow** separating code logic from data (events, sponsors, and team details are managed via data files under `src/data/`).
- **Cloudflare Pages** integration for instant builds and continuous deployment.

**Tech Stack:** `Astro` `TypeScript` `Tailwind CSS v4` `JavaScript` `Cloudflare Pages`

---

## 🗂️ [Contact Book CLI](https://github.com/ardauca/contact-book-cli)
**A contact management application designed to evolve from a file-based CLI tool into a production-ready API.**

### Current Features
- Full **CRUD** operations (Create, Read, Update, Delete) directly from the command line.
- **JSON-based data persistence** with built-in data preservation between runs.
- **Input validation** and error handling (try/except blocks) to prevent runtime crashes.
- Managed using a clean, modular pythonic project structure and Git feature branches.

### Backend Evolution Roadmap
- [ ] Migrate the data layer from JSON to **PostgreSQL** or **SQLite** using **SQLAlchemy** & **Alembic**.
- [ ] Wrap the contact manager logic in a REST API using **FastAPI**.
- [ ] Implement secure User Authentication & JWT.
- [ ] Containerize the full stack using **Docker** for local development and cloud deployment.
- [ ] Write unit tests with **pytest** to ensure functionality.

---

# 🛠️ Tech Stack & Ecosystem

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Backend & AI** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white) `PaddleOCR` `OpenCV` `deep-translator` |
| **Databases** | ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white) |
| **Frontend** | ![Astro](https://img.shields.io/badge/Astro-0C1222?style=flat-square&logo=astro&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

---

# 📈 Learning Roadmap & 2026 Goals

```text
[████████████████████] 100% 🟢 Python Fundamentals & Git/GitHub
[████████░░░░░░░░░░░░]  40% 🔵 SQL & Relational Database Basics (SQLite, basic queries)
[██████░░░░░░░░░░░░░░]  30% 🔵 FastAPI (Learning through Manga Translator backend)
[░░░░░░░░░░░░░░░░░░░░]   0% ⚪ PostgreSQL, SQLAlchemy & Alembic (Next Step)
[░░░░░░░░░░░░░░░░░░░░]   0% ⚪ Secure JWT Authentication & REST APIs
[░░░░░░░░░░░░░░░░░░░░]   0% ⚪ Docker & Containerization Workflows
[░░░░░░░░░░░░░░░░░░░░]   0% ⚪ Testing with pytest
[░░░░░░░░░░░░░░░░░░░░]   0% ⚪ Redis caching, Linux servers & AWS Basics
```

## 🎯 Career & 2026 Focus
- **Production-Style Backends**: Build APIs with proper modularity, error logging, and standard project layouts.
- **Relational Databases**: Transition projects to PostgreSQL, master schema design, indexing, and migrations.
- **Secure APIs**: Build solid token-based authentication models (OAuth2 / JWT).
- **DevOps Integrations**: Standardize environments with Docker containers and deploy web apps/backends to cloud providers.
