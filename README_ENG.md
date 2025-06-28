# 👨‍💻 Portfolio: Developments and Projects

Welcome to my portfolio! Here you'll find a curated list of my personal, academic, and community-driven projects, covering a range of topics from game modding to web development and desktop applications.

## 🐎 Studbook Web Scraper & Race Estimator
**Freelance / Academic project.**  
A Python-based script developed for collecting and analyzing horse racing data, designed to assist users in making informed betting decisions before a race event. It scrapes online data, processes it into structured reports, and highlights key statistics for each horse.

**Project overview:**
- Originally developed as a freelance tool for bettors, automating the collection of race and horse data from dynamic websites using Selenium and Playwright.
- Processes and structures data with pandas, storing it in a normalized SQLite3 database.
- Generates daily reports with calculated variables and race-by-race recommendations.

**Current evolution:**
- The project is now evolving into a more advanced data analysis tool:
  - Refactoring to support asynchronous scraping using `asyncio`.
  - Expanding the number of variables analyzed for better prediction quality.
  - Improving code structure to support experimentation with predictive algorithms.

**Academic collaboration:**  
This tool is also part of a joint research initiative in collaboration with a professional statistician. A poster presentation on the algorithmic logic will be featured at the *LI Coloquio Argentino de Estadística* in Tucumán later this year.

**Screenshots:**

<p float="left">
  <img src="screenshots/studbook_scrapper/s1.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s2.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s3.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s4.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s5.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s6.png" width="400"/>
  <img src="screenshots/studbook_scrapper/s7.png" width="400"/>
</p>

---

## 🧙 BFME2 Patch Switcher (PyQt6)
**Community / Hobby project.**  
A practical PyQt6-based GUI tool for managing patch versions, mods, and utilities for *The Lord of the Rings: The Battle for Middle-Earth II*. Designed to help organize and update an abandonware community.

**Key features:**
- GUI patch switcher and updater for BFME2, distributed to players since 2023.
- Connects to a remote JSON file to fetch patch updates, utilities, and installers.
- Fully self-contained desktop app with binary distribution.

**Screenshots:**

<p float="left">
  <img src="screenshots/bfme2_switcher/s1.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s2.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s3.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s4.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s5.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s6.PNG" width="400"/>
</p>

---

## 🏥 [ClinicaMedicaGestorDeTurnos-WPF](https://github.com/alexander5109/ClinicaMedicaGestorDeTurnos-WPF)
**Academic project.**  
A desktop application built with **WPF and .NET 8.0** for managing medical appointments in a clinical setting. Designed as a hands-on project for the *"Programación II"* course at the *Tecnicatura Universitaria en Programación* (UTN, 2024).

**Key features:**
- Modern UI with custom-styled buttons and dynamic view switching.
- Supports both **JSON** and **SQL Server** as persistence backends.
- Binds logic directly to UI components, avoiding MVVM for simplicity.
- Fully functional CRUD system with separated modules for patients, doctors, and appointment scheduling.

**Screenshots:**

<p float="left">
  <img src="screenshots/clinica_medica/s1.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s2.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s3.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s4.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s5.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s6.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s7.PNG" width="400"/>
</p>

---

## 🏫 [FormacionLaboralXXI-DjangoWebApp](https://github.com/alexander5109/FormacionLaboralXXI-DjangoWebApp)
**Academic project.**  
A Django-based web application simulating a vocational training management system. It models students, institutions, courses, and training centers using a normalized relational schema. Developed in **2023** during the *Programmer course* at *Centro de Formación Profesional N.º 406 (Morón, Argentina)*.

> ⚠️ **Note:** This is a learning project, not intended for real-world deployment. All authenticated users can edit data (students, institutions, courses) to explore Django’s ORM and architecture. Deletions are restricted to preserve data during testing.

**Features:**
- Models: `Estudiante`, `Curso`, `Institucion`, `Provincia`, `FamiliaProfesional`, and more.
- Hierarchical + many-to-many relationships.
- Auto-generated slugs and timestamped records.
- Django admin panel and basic login system.
- Optional avatars and feedback form (`Queja`).
- SQLite + Bootstrap template for frontend visualization.

**Screenshots:**

<p float="left">
  <img src="screenshots/django_formacionlaboralxxi/s1.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s2.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s3.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s4.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s5.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s6.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s7.jpg" width="400"/>
  <img src="screenshots/django_formacionlaboralxxi/s8.jpg" width="400"/>
</p>

---

## 🛒 [CursosStore-FrontendJS](https://github.com/alexander5109/CursosStore-FrontendJS)
**Academic project.**  
A simple frontend-only e-commerce prototype built with HTML, CSS, and JavaScript. It consumes public API data to simulate a course catalog with cart functionality. Developed in 2024 as part of the *TalentoTech Frontend* course.

**Features:**
- Product listing from API.
- Shopping cart using `localStorage`.
- Mobile-friendly UI with vanilla JS logic.

**Screenshots:**

<p float="left">
  <img src="screenshots/talentotech_frontend/s1.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s2.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s3.PNG" width="400"/>
</p>

---

## 🎮 [BFME2-Top 10 Best Players Challenge System](https://github.com/alexander5109/BFME2-ChallengeSystemTop10Players)
**Community / Hobby project.**  
A challenge tracking system designed for the *BFME2* multiplayer community. It maintains historical data in CSV format, stores player rankings in JSON, and publishes reports on a Discord channel. Originally architected for Discord bot integration, it currently runs manually.  
Developed in 2022 and continuously maintained, I actively incorporate user feedback to add features, fix bugs, and optimize performance.

**Screenshots:**

<p float="left">
  <img src="screenshots/bfme2_challenges/s1.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s2.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s3.PNG" width="400"/>
</p>

---

### 🧩 *Battle for Middle-earth II* – GameReplays.org Patch Development & Live Support
**2013–2025 | GameReplays.org – Community Technical Contributor**

He participado activamente en el mantenimiento, testeo y desarrollo de parches para *BFME2* bajo el motor SAGE, colaborando con la comunidad internacional para mantener vivo un juego clásico con fuerte base de jugadores competitivos. Mi rol evolucionó de tester a co-desarrollador, y finalmente a responsable principal de lanzamientos técnicos.

#### 🛠️ Roles y responsabilidades:
- Co-desarrollador de las versiones 1.09 y 1.09v2 (aproximadamente 100 betas combinadas)
- Desarrollador principal de la versión 1.09v3.0 (65 betas)
- Tester en versiones previas (1.07 y 1.08), colaborando con balance, QA y reporte de bugs
- Autor del *Patch Switcher* en Python con GUI, permitiendo cambiar entre versiones sin alterar archivos binarios
- Mantenimiento de archivos `.ini` complejos bajo restricciones de motor cerrado (sin tocar el `.exe`), equivalente a trabajo con DSLs embebidos
- Coordinación comunitaria para balance competitivo, diseño de mapas y procesamiento de feedback continuo

#### 🧰 Herramientas clave:
- **WinMerge**: uso intensivo para comparar builds y cambios en scripts
- **TortoiseGit**: gestión de versiones y revisión colaborativa por más de 10 años
- **Python + Tkinter**: desarrollo de GUI utilitaria para facilitar testing comunitario
- **Debugeo manual** de comportamiento emergente bajo condiciones limitadas de trazabilidad

#### 📌 Publicación destacada:
> “After a long journey of testing with over 65 beta versions, we are excited to share the highly anticipated Patch 1.09 Version 3.0 Final”  
> 👉 [Ver publicación oficial en GameReplays.org](https://www.gamereplays.org/battleformiddleearth2/portals.php?show=page&name=bfme2-patch-1.09-version-3.0-live)

---

## 🎮 [BFME2 - Bos Primigenius Taurus (Tower War)](https://github.com/alexander5109/BFME2-BosPrimigeniusTaurusTheTW)
**Community / Hobby project.**  
A fully custom *Tower War* map for *BFME2*, fundamentally reworking core gameplay through scripting. This project served as my introduction to game modding and programming logic. Developed and distributed between 2018 and 2023, it has been actively maintained since then.  
Players regularly send feedback via email, which I carefully review to implement updates and improvements, keeping the experience fresh and balanced.


**Screenshots:**

<p float="left">
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo1.PNG?raw=true" width="400"/>
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo3.PNG?raw=true" width="400"/>
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo2.PNG?raw=true" width="400"/>
</p>

---

## 📫 Contact

- 📧 Email: [xanderseling@gmail.com](mailto:xanderseling@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/alexander5109](https://www.linkedin.com/in/alexander5109/)
