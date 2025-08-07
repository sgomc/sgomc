# 👋 Welcome to sgomc’s Repository

Hello! I’m **Maccollins Obijiaku**, a first‑year Computer Science student at Trinity College Dublin, based in Cavan, Ireland. I’m passionate about applying data analysis, algorithms, and software development to build practical solutions. Below you’ll find a showcase of my key projects, technologies I use, and how to get in touch.

---

## 🗂️ Project Portfolio

### 1. Gym Occupancy Predictor (gym-goer)

**Tech:** Python, pandas, NumPy, matplotlib

A data‑driven application that analyzes historical gym attendance data to recommend the best times to work out. Key features:

* **Data Ingestion:** Processes CSV logs of crowd counts by timestamp.
* **Peak/Off‑Peak Analysis:** Uses pandas to compute daily and weekly occupancy trends.
* **Curve Fitting:** Applies simple regression to predict traffic patterns for gyms with limited data.
* **Visualization:** Generates interactive plots showing optimal visit windows.
* **Outcome:** Achieved a H1 in my Leaving Cert project; now available as an open‑source prototype.

### 2. Educational (Hackaton) Website (maths‑in‑ohio)

**Tech:** HTML, CSS, JavaScript, Altervista hosting

A responsive educational platform designed to make basic arithmetic engaging for students:

* **Custom Design:** Tailored layout and styling for clear readability.
* **Interactive Exercises:** JavaScript‑powered quizzes for addition, subtraction, multiplication, division.
* **Deployment:** Locally.
* **https://sgomc.github.io/Maths-in-Ohio/Main.html  hosted here

### 3. Collaborative Coding Project (programming‑project‑group‑10)

**Tech:** Java, GitHub, Agile workflow

A team‑based software development exercise in which we:

* **Designed** a modular Java application (e.g., a tournament scheduler).
* **Managed** version control and pull requests using GitHub.
* **Practiced** agile ceremonies with regular stand‑ups and retrospectives.
### 4. 🌐 Arcane: Front-End Showcase with Elementor

**Overview:**
Arcane is a portfolio website built on WordPress using the Elementor page-builder plugin to demonstrate modern front-end design and deployment workflows. It highlights your ability to craft visually appealing, responsive sites and to manage a live hosting environment end-to-end.


---

#### 🔑 Core Features

* **Elementor-Powered Layouts**
  Clean, customizable sections built entirely with Elementor’s drag-and-drop interface, showing off skills in layout composition, typography, and responsive breakpoints.

* **Custom Theming & Styling**
  Additional CSS tweaks and Elementor theme overrides to tailor the site’s look beyond default templates—demonstrating mastery of both the tool and underlying HTML/CSS.

* **Live Hosting & Deployment**
  Hosted on Altervista; covers the full cycle of deploying WordPress, configuring DNS/FTP, and maintaining updates and backups in a production environment.

* **Showcase Sections**

  * **Hero Banner** with call-to-action
  * **Project Galleries** featuring screenshots and live links
  * **About & Contact** forms styled with Elementor widgets

---

#### 🛠️ Technologies & Tools

* **CMS & Builder:** WordPress, Elementor Pro
* **Markup & Styling:** HTML5, CSS3 (custom overrides)
* **Hosting:** Altervista (FTP upload, site backups)
* **Graphics:** Adobe XD → SVG exports, optimized via SVGOMG

---

#### 🎯 Purpose & Impact

Arcane isn’t just a demo site—it’s a **proof of competence** in:

1. **Rapid Prototyping:** Leveraging Elementor to spin up professional layouts in minutes.
2. **Design Consistency:** Applying global styles, typography settings, and color schemes across pages.
3. **Responsive Best Practices:** Ensuring pixel-perfect rendering on desktop, tablet, and mobile breakpoints.
4. **Live Environment Management:** Handling WordPress installations, plugin updates, and routine maintenance on a public host.

---

#### 🔗 Live Demo & Code

* **Live Site:** [https://arcane.altervista.org/](https://arcane.altervista.org/)

* **Notes:** While the codebase is managed through Elementor’s exports and custom CSS files, I can provide detailed style snippets or cloned theme files on request.


### 5. Project Title: AI-Powered CV Parser & Resume Builder

#### Project Description

This project is a full-stack web application designed to automatically parse and structure data from a CV document using a self-hosted AI model. Users can upload a PDF or image of their resume, and the application's AI backend intelligently extracts key information—such as personal details, work experience, education, and skills—into a structured JSON format. This data is then used to dynamically populate and render various professional resume templates, which can be downloaded as a new, clean PDF or DOCX file.

The core challenge of this project was to build a robust data extraction pipeline on resource-constrained hardware (a dual-core Celeron server with 4GB RAM). This was achieved by moving away from expensive, monolithic cloud AI APIs and instead using a locally-hosted, open-source Large Language Model (`gemma:2b`) managed by Ollama.

The backend orchestrates a complex, multi-step "intelligent slicing" algorithm. It first uses Tesseract for OCR, then programmatically isolates logical sections of the CV. Each section is then passed to the local AI with a series of highly-specific, engineered prompts to extract and structure the data. This modular, "prime-per-section" approach maximizes the accuracy of the smaller AI model while efficiently managing the server's limited CPU and memory resources.

#### Key Features

*   **AI-Powered CV Parsing:** Leverages a self-hosted `gemma:2b` model via Ollama to extract structured data from resume images.
*   **Dynamic Template Rendering:** Uses React to dynamically render the extracted CV data into multiple, professionally designed resume templates.
*   **Asynchronous Job Processing:** The backend is built with a robust, asynchronous polling architecture to handle the long-running AI analysis without timing out the client.
*   **PDF & DOCX Export:** Allows users to download their newly formatted resume using `jsPDF` and `html-to-docx`.
*   **Full-Stack Self-Hosted Solution:** The entire application, from the web server to the AI, is designed to run on a single, low-power machine, ensuring data privacy and zero operational cost.

#### Technology Stack

*   **Backend:** Java (OpenJDK), Simple `HttpServer`, `systemd`
*   **AI:** Ollama, `gemma:2b`, Tesseract (via Tess4J)
*   **Database:** MariaDB
*   **Frontend:** React, TypeScript, Vite, Tailwind CSS
*   **Web Server / Proxy:** Nginx
*   **OS:** Ubuntu Server
## 🛠️ Technical Skills & Tools

* **Languages:** Java, Python, JavaScript, Bash (basic)
* **Data:** pandas, NumPy, matplotlib, Excel (pivot tables, macros)
* **Web:** HTML5, CSS3, responsive design, Altervista deployment
* **Algorithms & DS:** Strong problem‑solving (44+ LeetCode Qs), sorting, search, dynamic programming
* **Version Control:** Git, GitHub workflows (branching, PRs)
* **Collaboration:** Microsoft Teams, Slack, Zoom, Notion
* **Systems:** Windows, Linux (Ubuntu), shell scripting fundamentals

## 🚀 Getting Started

1. **Clone the repo:**

   ```bash
   git clone https://github.com/sgomc/your-repo-name.git
   ```
2. **Explore folders:** Each project has its own directory with code and README.
3. **Run demos:** Follow individual project READMEs for setup instructions.

## 📫 Contact & Connect

* **GitHub:** [github.com/sgomc](https://github.com/sgomc)
* **LinkedIn:** [Maccollins Obijiaku](https://www.linkedin.com/in/maccollins-obijiaku-47b473315)
* **Email:** ([maccobii4@gmail.com])

Feel free to open issues, suggest enhancements, or collaborate on any project. Thanks for visiting!


![snake gif](https://github.com/sgomc/sgomc/blob/output/github-snake-dark.svg)
  

