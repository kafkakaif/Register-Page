<div align="center">

# Branch Registration Form

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

*"Simple registration, smarter selection."*

</div>

---

## Overview

This is a **lightweight registration form** built with plain **HTML, CSS, and JavaScript**. It collects user details — name, age, email, and mobile number — and lets users select a **branch location**, dynamically revealing a **branch-specific dropdown** of available options.

No frameworks, no dependencies — just clean, functional front-end code.

---

## Features

- 🧾 Simple registration fields (name, age, email, mobile number)
- 🏢 Branch selector with 4 locations: Chennai, Madanapalle, Kadiri, Kurabalakota
- 🔄 Dynamic dropdown switching based on selected branch
- 🎨 Full-width styled background with a clean form layout
- ⚡ Zero dependencies — pure HTML/CSS/JS

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | JavaScript (Vanilla) |

---

## Project Structure

```
├── register.html
└── img/
    └── 4820992.webp
```

---

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Ensure the `img/` folder sits alongside `register.html`
3. Open `register.html` directly in your browser

No build tools or server setup required.

---

## How It Works

Selecting a branch from the dropdown triggers a JavaScript `toggle()` function, which shows the dropdown matching that branch and hides the rest — each branch has its own set of options.

---

## Roadmap

- [ ] Add form validation (required fields, email/mobile format)
- [ ] Connect form submission to a backend
- [ ] Improve accessibility (labels, ARIA attributes)
- [ ] Make layout responsive for mobile screens

---

<div align="center">

**License:** [MIT](LICENSE)

</div>
