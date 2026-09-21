from pathlib import Path

readme = r'''# Hi, I'm Milad Fathi 👋

### Backend / Full-Stack Developer

I’m a software developer with several years of experience building web applications and APIs, with a strong focus on **PHP, Laravel, MySQL, and modern JavaScript**.

I enjoy building clean, maintainable software, improving existing systems, and learning new technologies. Recently, I’ve also been focusing more on **AI-assisted software development** and using tools such as **Cursor and AI coding agents** in my development workflow.

---

## 🚀 About Me

- 💻 Backend-focused developer with strong experience in **PHP & Laravel**
- 🌐 Experience building **REST APIs** and full-stack web applications
- 🧩 Interested in **clean architecture, SOLID, DDD, testing, and scalable systems**
- 🤖 Actively using **Cursor and AI tools** in my daily development workflow
- 🛠️ Building **Ripple**, my own developer tool for analyzing code-change impact
- 📱 Experience with **Flutter** and mobile application development
- ☁️ Familiar with **Docker, AWS, CI/CD, and production systems**
- 🌱 Always learning and improving my software engineering skills

---

## 🧠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,laravel,mysql,js,vue,nuxt,tailwind,flutter,dart,docker,aws,git,github,githubactions,linux&perline=5" alt="Tech Stack" />
</p>

### Backend
`PHP` · `Laravel` · `REST APIs` · `MySQL` · `Redis` · `PHPUnit`

### Frontend
`JavaScript` · `Vue.js` · `Nuxt` · `Tailwind CSS`

### Mobile
`Flutter` · `Dart`

### DevOps & Tools
`Docker` · `AWS` · `Linux` · `Git` · `GitHub Actions` · `Nginx`

### AI-Assisted Development
`Cursor` · `AI Coding Agents` · `AI-assisted Software Development`

---

## 🔥 Featured Project

### Ripple — Code Change Impact Analyzer

[![Ripple](https://img.shields.io/badge/Ripple-Code%20Change%20Impact%20Analyzer-111827?style=for-the-badge&logo=github)](https://github.com/miladfathi021/Ripple)

**Ripple** is a developer tool that analyzes code changes and helps developers understand their potential impact across a PHP codebase.

It analyzes things such as:

- Changed files and symbols
- Code dependencies
- Direct blast radius
- Affected flows
- Risk factors and deterministic risk scoring
- Semantic impact
- Historical file churn

I’m building Ripple from an empty repository while using **Cursor and AI-assisted development workflows** as part of the engineering process.

👉 **[View Ripple on GitHub](https://github.com/miladfathi021/Ripple)**

---

## 🏗️ Engineering Interests

I’m particularly interested in:

- Backend architecture
- API design
- Clean Code & SOLID
- Domain-Driven Design
- Performance & database optimization
- Automated testing
- Distributed systems
- Developer tools
- AI-assisted software engineering
- Agentic development workflows

---

## 📫 Let's Connect

<p align="left">
  <a href="mailto:miladfathi021@gmail.com">
    <img src="https://img.shields.io/badge/Email-miladfathi021%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/miladfathi021">
    <img src="https://img.shields.io/badge/GitHub-miladfathi021-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Milad%20Fathi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

<p align="center">
  <i>Building software, learning continuously, and exploring how AI can make developers more productive.</i>
</p>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")

print(f"Created: {path}")
