# 👨‍💻 Portfolio: Developments and Projects

Welcome to my portfolio! Here you'll find a curated list of my personal and academic projects, covering a range of topics from game modding to web development and desktop applications.

## 🐎 Studbook Web Scrapper & Race Stimator
Freelance project. A Python-based script developed for collecting and analyzing horse racing data, designed to assist users in making informed betting decisions before a race event. It scrapes online data, processes it into structured reports, and highlights key statistics for each horse.

Project overview:
- Originally developed as a freelance tool for bettors, it automates the collection of race and horse data from dynamic websites using Selenium and Playwright.
- Processes and structures the data with pandas, storing it in a normalized SQLite3 database.
- Generates daily reports with calculated variables and race-by-race recommendations.

Current evolution:
- The project is now being expanded with a stronger focus on data analysis. Refactoring efforts are underway to:
- Incorporate asynchronous scraping using asyncio for better efficiency.
- Extend the number of variables analyzed to improve prediction quality.
- Improve code structure for future experimentation with predictive algorithms.

Academic collaboration:
This project is part of an ongoing academic research initiative in collaboration with a professional statistician. Together, we will present a poster detailing the algorithmic logic behind this tool at the LI Coloquio Argentino de Estadística, to be held in Tucumán later this year.

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

## 🧙 BFME2 Patch Switcher (PyQt6)
Hobbie/community-for project. A practical PyQt6-based GUI tool for managing patch versions, mods, and utilities for *The Lord of the Rings: The Battle for Middle-Earth II*. Designed to keep an abandonware community updated and organized.

**Key features:**
- GUI patch switcher and updater for BFME2, distributed to players since 2023.
- Integrates with a remote JSON file to check for patch updates, utilities, and installer links.
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

## 🏰 [ClinicaMedicaGestorDeTurnos-WPF](https://github.com/alexander5109/ClinicaMedicaGestorDeTurnos-WPF)
Academic project. A desktop application built with **WPF and .NET 8.0** for managing medical appointments in a clinical setting. It allows users to create, view, and update records for doctors, patients, and scheduled appointments through a clean graphical interface.
Designed as a hands-on project for the **"Programación II" course** at the *Tecnicatura Universitaria en Programación* (UTN, 2024), the app emphasizes practical use of WPF for desktop development.

**Key features:**
- Modern UI with custom-styled buttons and dynamic view switching.
- Supports both **JSON** and **SQL Server** as data persistence backends, allowing flexible testing and deployment.
- Uses direct bindings between code and UI components, intentionally avoiding the MVVM pattern to focus on core application logic.
- Fully functional CRUD system with separated modules for patients, doctors, and appointment scheduling.

**Screenshots (frontend views):**

<p float="left">
  <img src="screenshots/clinica_medica/s1.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s2.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s3.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s4.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s5.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s6.PNG" width="400"/>
  <img src="screenshots/clinica_medica/s7.PNG" width="400"/>
</p>


## 🏰 [FormacionLaboralXXI-DjangoWebApp](https://github.com/alexander5109/FormacionLaboralXXI-DjangoWebApp)
Academic project. A Django-based web application inspired by the structure of real-world vocational training systems. It simulates the management of students, institutions, courses, and administrative regions using a normalized relational model.
This project was developed in **2023** as part of the *Programmer course* at **Centro de Formación Profesional N.º 406 (Morón, Argentina)**.

> ⚠️ **Note:** This is a **demonstration project**, not intended for production use. All authenticated users can create and edit records—including students, institutions, and courses—to showcase Django’s ORM, view architecture, and admin integration. Deletion is intentionally restricted to avoid data loss during testing.

**Core features:**
- Custom data models for `Estudiante`, `Curso`, `Institucion`, `Provincia`, and `FamiliaProfesional`, with both hierarchical and many-to-many relationships.
- Login system and Django admin dashboard.
- Slug generation, automatic metadata (created/updated), and flexible course enrollment.
- User avatars support.
- Forms for contact/feedback, modeled as a (`Queja`) in the database.
- SQLite3 backend with a Bootstrap-styled frontend for CRUD operation demonstration.

## 🏰 [CursosStore-FrontendJS](https://github.com/alexander5109/CursosStore-FrontendJS)
Academic project. A simple but functional frontend-only e-commerce prototype built with plain HTML, CSS, and JavaScript. It fetches public API data to simulate a catalog of courses, allowing the user to view products, add them to a shopping cart, and simulate a purchase flow using LocalStorage. Created as part of the TalentoTech Frontend course i took in 2024.
**Screenshots (frontend views):**

<p float="left">
  <img src="screenshots/talentotech_frontend/s1.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s2.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s3.PNG" width="400"/>
</p>

**Screenshots (frontend views):**

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


## 🎮 [BFME2-ChallengeSystemTop10Players](https://github.com/alexander5109/BFME2-ChallengeSystemTop10Players)
Hobbie/community for project. A league challenges system tracker for BFME2 players, featuring a CSV history, player data storage in JSON and Discord integration to publish reports in a server channel. Intended to work as an API for discord bot but currently lacking a server to implement a bot, so requires manual call from my computer for now. 

<p float="left">
  <img src="screenshots/bfme2_challenges/s1.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s2.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s3.PNG" width="400"/>
</p>


## 🎮 [BFME2-BosPrimigeniusTaurusTheTW](https://github.com/alexander5109/BFME2-BosPrimigeniusTaurusTheTW)
Hobbie/community for project. A Tower War style of map that basicaly reworked the entire gameplay of BFME2 in just a portable map. With this projects i learned BFME2 modding and most important, programing logic, when i designed the scripts of this map adventure. It's creation began in 2018 and was rather finishd in 2021, with further implementations at 2022 and 2023.
 
<p float="left">
	<img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo1.PNG?raw=true" alt="Image 1">
	<img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo3.PNG?raw=true" alt="Image 1">
	<img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo2.PNG?raw=true" alt="Image 1">
</p>
## 📫 Contact
Mail: [xanderseling@gmail.com](mailto:xanderseling@gmail.com)
Linkedin: [https://www.linkedin.com/in/alexander5109/]
