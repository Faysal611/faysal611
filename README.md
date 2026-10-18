<!-- Banner -->
<div align="center">
  <img src="https://user-images.githubusercontent.com/113350806/236842414-18101a37-92f5-4de7-a46d-eeaca6e16cbd.gif" alt="Banner" width="100%" />
</div>

<!-- Header & Headline -->
<div align="center">
  <h1>Faysal Hasan</h1>
  <h3>Full-Stack Software Engineer &nbsp;|&nbsp; Next.js, FastAPI & PostgreSQL &nbsp;|&nbsp; AI & Machine Learning</h3>

  <!-- Quick Links -->
  <p>
    <a href="https://www.linkedin.com/in/md-faysal-hasan" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:faysalhasan950@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/Faysal611" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>

---

## Overview

- **Full-Stack Engineering:** Architecting scalable web applications and asynchronous REST APIs using **Next.js**, **React**, **FastAPI**, and **Node.js**.
- **AI & Machine Learning:** Developing tool-calling **AI Agents** with LLM APIs (**Google Gemini**) and building applied machine learning workflows in **Python**.
- **Database Architecture:** Designing relational and document-based schemas using **PostgreSQL**, **SQLAlchemy**, and **MongoDB**.

---

## Technical Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,nextjs,react,fastapi,nodejs,express,postgres,mongodb,tailwind,mui,firebase,vite,git&perline=15" alt="Tech Icons" />
</div>

<br />

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript_(ES6+)-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Backend & DB** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **AI / ML & Tools** | ![Google Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=python&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

## Featured Projects

### 1. Autonomous AI Coding Agent
[![Source Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/Faysal611/ai-agent)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LLM Function Calling](https://img.shields.io/badge/Architecture-Tool_Calling-009688?style=flat-square)
![uv](https://img.shields.io/badge/Tooling-uv-DE5FE9?style=flat-square)

A CLI-based autonomous coding agent built in Python using the **Google Gemini API**. The system leverages LLM function calling (tool use) to inspect directories, manipulate source files, and execute Python scripts autonomously within a sandboxed workspace.

- **Autonomous Tool Execution:** Implemented custom tool declarations that allow the model to list directory trees, read file contents, write/overwrite code, and run Python scripts with dynamic CLI arguments.
- **Sandboxed File System Security:** Enforced strict working-directory scoping (`root_folder`) to isolate agent operations and prevent unauthorized file modifications outside the target project environment.
- **Developer CLI & Observability:** Built with modern `uv` package management and includes a `--verbose` execution mode to trace prompt reasoning and tool-call payloads in real time.

---

### 2. Campus Cuisine — Hostel & Dining Management System
[![Source Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/Faysal611/campus-cuisine-client)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://wonderful-mandazi-cdc2fe.netlify.app/)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)

A full-stack university hostel management platform designed to streamline daily dining operations, meal scheduling, and student feedback through role-based access control.

- **Student Portal:** Features Firebase authentication, interactive meal discovery with category and price filtering, and full CRUD workflows for submitting and managing dining reviews.
- **Administrative Dashboard:** Centralized management interface for overseeing registered students, updating meal inventories, and moderating platform feedback.
- **System Architecture:** Engineered with **React.js**, **Tailwind CSS**, and **Material UI**, utilizing **TanStack Query** and **Context API** for asynchronous state synchronization with a **Node.js / Express.js** and **MongoDB Atlas** backend.

---

### 3. Assembly: Endgame — State-Driven Word Puzzle
[![Source Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/Faysal611/assembly-endgame)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://assembly-endgame-faysal950.netlify.app/)
![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_(ES6+)-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

An interactive word-deduction application built with **React 19** where players have eight attempts to identify a hidden term before high-level programming languages are systematically eliminated down to Assembly.

- **Interactive State Management:** Tracks real-time letter guesses, remaining attempts, and dynamic UI state transitions across virtual keyboard inputs.
- **Frontend Tooling:** Built using **React 19** and **Vite** with modular ES6+ architecture, **SweetAlert2** modal feedback, and celebratory canvas animations.

---

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Faysal611&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Faysal611&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" height="165" />
</div>
