# 👨‍💻 Portfolio: Desarrollos y Proyectos

Bienvenido a mi portfolio. Aquí se encuentra una descripción de mis proyectos personales, académicos y comunitarios, que abarcan desde modding de videojuegos, scripts, desarrollo web y aplicaciones de escritorio.

## 🐎 Aplicación de consola: Studbook Scraper y Estimador de Carreras (Python, Selenium)  
**Proyecto freelance / académico.**  
Una aplicación de consola en Python desarrollado para recolectar y analizar datos de carreras de caballos, diseñado para ayudar al jugador a tomar decisiones informadas antes de cada evento. Extrae datos en línea (sin API), los procesa en reportes estructurados y destaca estadísticas clave para cada caballo.

**Resumen del proyecto:**  
- Originalmente creado como herramienta freelance para apostadores, automatiza la recolección de datos de carreras y caballos desde sitios web dinámicos usando Selenium y Playwright.  
- Procesa y estructura datos con pandas, almacenándolos en una base SQLite3 normalizada.  
- Genera reportes diarios con variables calculadas y recomendaciones carrera por carrera.

**Evolución actual:**  
- El proyecto se está transformando en una herramienta más avanzada de análisis de datos:  
  - Refactorización para soportar scraping asíncrono con `asyncio`.  
  - Ampliación del número de variables analizadas para mejorar la calidad de las predicciones.  
  - Mejora de la estructura de código para facilitar experimentos con algoritmos predictivos.

**Colaboración académica:**  
Actualmente esta herramienta forma parte de una iniciativa de investigación conjunta con una estadística profesional. Presentaremos un póster sobre su lógica algorítmica en el *LI Coloquio Argentino de Estadística* que se realizará en Tucumán a fin de año.

**Capturas:**  

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

## 🧙 Aplicación de escritorio: BFME2 Patch Switcher (Python, PyQt6)  
**Proyecto comunitario / hobby.**  
Herramienta GUI práctica hecha con Python y PyQt6 para gestionar versiones de parches, mods y utilidades para *The Lord of the Rings: The Battle for Middle-Earth II*. Diseñada para mantener organizada y actualizada a una comunidad de abandonware.

**Características principales:**  
- Selector y actualizador de parches para BFME2, distribuido desde 2023.  
- Algoritmo eficiente para detectar diferencias entre versiones instaladas.
- Conexión con un archivo JSON remoto para obtener actualizaciones, utilidades e instaladores.  
- Aplicación de escritorio autónoma con distribución binaria (compilada con PyInstaller).

**Capturas:**  

<p float="left">
  <img src="screenshots/bfme2_switcher/s1.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s2.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s3.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s4.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s5.PNG" width="400"/>
  <img src="screenshots/bfme2_switcher/s6.PNG" width="400"/>
</p>

---

## 🏥 [Aplicación de escritorio: Gestor de Turnos de una Clínica Medica (C#, WPF) ](https://github.com/alexander5109/ClinicaMedicaGestorDeTurnos-WPF)  
**Proyecto académico.**  
Aplicación de escritorio construida con **WPF y .NET 8.0** para gestionar turnos médicos en un entorno clínico. Desarrollada como proyecto práctico para la materia *"Programación II"* de la *Tecnicatura Universitaria en Programación* (UTN, 2024).

**Características principales:**  
- Interfaz moderna con botones personalizados (hechos a mano con Gimp) y cambio dinámico de vistas.  
- Soporta persistencia de datos en **JSON** y **SQL Server**.  
- Vincula la lógica directamente a componentes UI, evitando MVVM para simplificar.  
- Sistema CRUD completo con módulos separados pero inter-relacionados para pacientes, médicos y turnos.

**Capturas:**  

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

## 🏫 [Sitio Web con BackEnd: Formacion Laboral XXI (Python Django)](https://github.com/alexander5109/FormacionLaboralXXI-DjangoWebApp)  
**Proyecto académico.**  
Aplicación web basada en Python con ORM Django que simula un sistema de gestión de formación profesional. Modela estudiantes, instituciones, cursos y centros de formación con un esquema relacional normalizado. Desarrollada en **2023** durante el *Curso de Programador* en el *Centro de Formación Profesional N.º 406 (Morón, Argentina)*.

> ⚠️ **Nota:** Proyecto didáctico, no para producción real. Todos los usuarios autenticados pueden editar datos (estudiantes, instituciones, cursos) para explorar el ORM y arquitectura de Django. Se restringen eliminaciones para preservar datos en pruebas.

**Características:**  
- Modelos: `Estudiante`, `Curso`, `Institucion`, `Provincia`, `FamiliaProfesional`, entre otros.  
- Relaciones jerárquicas y de muchos a muchos.  
- Slugs autogenerados y registros con timestamps.  
- Panel de administración de Django y sistema básico de login.  
- Soporte opcional para avatares y formulario de feedback (`Queja`).  
- Backend SQLite + plantilla Bootstrap para visualización frontend.

**Capturas:**  

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

## 🛒 [Página Web FrontEnd: Prototipo de E-commerce: Academia de cursos (HTML, CSS, JS)](https://github.com/alexander5109/CursosStore-FrontendJS)  
**Proyecto académico.**  
Prototipo simple y funcional de e-commerce frontend construido con HTML, CSS y JavaScript. Consume datos de APIs públicas para simular un catálogo de cursos con funcionalidad de carrito. Desarrollado en 2024 como parte del curso *TalentoTech Frontend*.

**Características:**  
- Listado de productos desde API.  
- Carrito de compras usando `localStorage`.  
- UI responsive y lógica con JavaScript puro.

**Capturas:**  

<p float="left">
  <img src="screenshots/talentotech_frontend/s1.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s2.PNG" width="400"/>
  <img src="screenshots/talentotech_frontend/s3.PNG" width="400"/>
</p>

---

## 🎮 [Aplicación de consola: BFME2 Top 10 Best Players: Challenge System (Python)](https://github.com/alexander5109/BFME2-ChallengeSystemTop10Players)  
**Proyecto comunitario / hobby.**  
Sistema de seguimiento de desafíos para la comunidad multijugador de *BFME2*. Mantiene historial en CSV, rankings de jugadores en JSON y publica reportes en un canal de Discord. Originalmente pensado para integración con bot de Discord, actualmente se ejecuta manualmente.  
Desarrollado en 2022 y mantenido continuamente, incorporo feedback para nuevas funcionalidades, corrección de errores y mejoras.

**Capturas:**  

<p float="left">
  <img src="screenshots/bfme2_challenges/s1.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s2.PNG" width="400"/>
  <img src="screenshots/bfme2_challenges/s3.PNG" width="400"/>
</p>

---
## 🧩 [El Señor de los Anillos: La Batalla por la Tierra Media II – GameReplays.org Patch Development](https://github.com/ValheruGR/BFME2)  
**Proyecto comunitario / hobby.**  
He participado activamente en el mantenimiento, testeo y desarrollo de parches para *BFME2* bajo el motor SAGE, colaborando con la comunidad internacional para mantener vivo un juego clásico con fuerte base de jugadores competitivos. Mi rol evolucionó de tester a co-desarrollador, y finalmente a responsable principal de lanzamientos técnicos y administrador de la sección BFME2 en GameReplays.org.

**Roles y responsabilidades:**  
- Co-desarrollador de las versiones 1.09 y 1.09v2 (aproximadamente 100 betas combinadas).  
- Desarrollador principal de la versión 1.09v3.0 (65 betas).  
- Tester en versiones previas (1.07 y 1.08), colaborando con balance, QA y reporte de bugs.  
- Autor del *Patch Switcher* en Python con GUI, permitiendo cambiar entre versiones sin alterar archivos binarios.  
- Mantenimiento de archivos .ini complejos bajo restricciones del motor cerrado (sin modificar el .exe), equivalente a trabajo con DSLs embebidos.  
- Coordinación comunitaria para balance competitivo, diseño de mapas y gestión de feedback continuo.

**Lo que aprendí:**  
- **Inglés técnico y comunicación internacional:** más de una década interactuando en foros, chats, gestión comunitaria y soporte para un software sin soporte oficial.  
- **Control de versiones:** uso intensivo de herramientas como **WinMerge** y **TortoiseGit** para comparar builds, gestionar cambios y realizar merge de ramas.  
- **Depuración avanzada:** búsqueda binaria entre builds para detectar bugs de runtime sin mensajes de error, en un entorno sin logs ni debugger.  
- **Soporte y QA:** resolución de bugs reportados por usuarios, creación de documentación, manejo de regresiones y coordinación de testers.

**Publicación destacada:**  
> “After a long journey of testing with over 65 beta versions, we are excited to share the highly anticipated Patch 1.09 Version 3.0”  
> 👉 [Ver publicación oficial en GameReplays.org](https://www.gamereplays.org/battleformiddleearth2/portals.php?show=page&name=bfme2-patch-1.09-version-3.0-live)

**Capturas:**  
<p float="left">
  <img src="screenshots/bfme2_patch/s1.PNG" width="400"/>
</p>

---

## 🎮 [BFME2 mapa personalizado: Bos Primigenius Taurus TW](https://github.com/alexander5109/BFME2-BosPrimigeniusTaurusTheTW)  
**Proyecto comunitario / hobby.**  
Mapa completamente personalizado *Tower War* para *BFME2*, que reestructura la jugabilidad central mediante modificación de los recursos presentes en el juego y scripting. Fue mi introducción al modding de juegos y lógica de programación. Desarrollado y distribuido entre 2018 y 2023, y mantenido activamente desde entonces.  
Los jugadores me envían comentarios por email, que analizo para implementar mejoras y actualizaciones, manteniendo la experiencia fresca y equilibrada.

**Capturas:**  

<p float="left">
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo1.PNG?raw=true" width="400"/>
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo3.PNG?raw=true" width="400"/>
  <img src="https://github.com/ecthelion5109/BosPrimigeniusTaurusTheTW/blob/main/_misc/_github_images/dibujo2.PNG?raw=true" width="400"/>
</p>

---

## 📫 Contacto

- 📧 Email: [xanderseling@gmail.com](mailto:xanderseling@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/alexander5109](https://www.linkedin.com/in/alexander5109/)
