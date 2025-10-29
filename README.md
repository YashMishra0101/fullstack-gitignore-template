# 🧑‍💻 Full-Stack Ignore Templates

A **professionally crafted collection** of `.gitignore` and `.prettierignore` templates for **modern full-stack JavaScript and TypeScript projects**.  
This repository helps developers maintain **clean, secure, and professional codebases** by excluding unwanted, generated, or sensitive files from Git and Prettier.

---

## 📦 File Overview

| File Name            | Language   | Applies To         | Description                                                                                        |
| -------------------- | ---------- | ------------------ | -------------------------------------------------------------------------------------------------- |
| `.gitignore`         | JavaScript | Frontend + Backend | For JS-based full-stack projects (React, Node, Express, MongoDB, Mongoose).                        |
| `.gitignore.ts`      | TypeScript | Frontend + Backend | For TypeScript-based full-stack projects — ignores build info, `.tsbuildinfo`, and compiled files. |
| `.prettierignore`    | JavaScript | Frontend + Backend | For non-TypeScript projects — excludes build outputs, caches, and environment files from Prettier. |
| `.prettierignore.ts` | TypeScript | Frontend + Backend | For TypeScript projects — skips TS, Vite, and build artifacts during Prettier formatting.          |

> 🧩 These four files together cover **frontend (React, Tailwind CSS)** and **backend (Node.js, Express, MongoDB, Mongoose)** setups.

---

## 🎯 Purpose

This repository provides **ready-to-use ignore templates** designed for both **frontend and backend** projects — whether you’re using plain JavaScript or TypeScript.  
Each file is structured, documented, and production-ready — helping developers keep their repositories clean and secure.

---

## 🧩 Supported Stack

| Layer               | Technologies                                     |
| ------------------- | ------------------------------------------------ |
| **Frontend**        | React (with or without TypeScript), Tailwind CSS |
| **Backend**         | Node.js + Express.js                             |
| **Database**        | MongoDB + Mongoose                               |
| **Package Manager** | pnpm (fully optimized for pnpm)                  |

> 🖖👉 These templates are optimized for **pnpm** users.  
> For npm or Yarn, just adjust lockfile and cache folder names as needed.

---

## 🗂 Repository Structure

```

📦 fullstack-ignore-templates/
│
├── .gitignore                  # Common ignore (Frontend + Backend without TypeScript)
├── .prettierignore             # Prettier ignore (Frontend + Backend without TypeScript)
├── LICENSE.md                  # License file for open-source usage and distribution
├── ts.gitignore                # Common ignore (Frontend + Backend with TypeScript)
├── ts.prettierignore           # Prettier ignore (Frontend + Backend with TypeScript)
└── README.md                   # Documentation (this file)


```

---

## ⚡ Why Use These Templates

- ✅ **All-in-One Setup** – Works for both frontend and backend, no separate files needed.
- 🧩 **Supports JS & TS** – Separate versions for TypeScript and non-TypeScript projects.
- 🔒 **Security-Oriented** – Prevents sensitive `.env` and `.local` configuration files from being pushed.
- ⚡ **Optimized for pnpm** – Includes pnpm caches, lock files, and workspace ignores.
- 🧹 **Clean & Professional** – Excludes build folders, logs, and temporary system files.
- 💡 **Beginner-Friendly Comments** – Every section explains what’s being ignored and why.
- 💼 **Production-Ready** – Ideal for freelancers, startups, and enterprise projects alike.

---

## 🤝 Contributing

Contributions are welcome!
If you want to improve existing templates or add support for other stacks (like Next.js, NestJS, or Remix):

- Create a **Pull Request** with clear explanations.
- Open an **Issue** to suggest improvements.
- Share your own **stack-specific ignore templates** with the community.

Together, we can make cleaner, safer repos for everyone 💪.

---

## 👩‍💻 Author

**Yash Mishra**
* 📧 [yashrkm0011@gmail.com](mailto:yashrkm0011@gmail.com)
* 💼 [LinkedIn](https://www.linkedin.com/in/yash-mishra-356280223/)
* 🐦 [Twitter (X)](https://x.com/YashRKMishra1)

---

## ⭐ Support

If this repository helped you, please **star ⭐ it on GitHub** —
it encourages future improvements and helps more developers keep their projects clean, consistent, and professional.

---

> _Maintained with ❤️ by Yash Mishra — empowering developers to build clean, organized, and production-ready projects._
