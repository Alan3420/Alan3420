## Alan Novas Mateo

**Desarrollador junior full-stack** centrado en Python y desarrollo web. Construyo aplicaciones con APIs REST en FastAPI y Flask, frontends en Vue 3 y bases de datos relacionales, con atención a la arquitectura por capas, los tests y la documentación.

Actualmente busco mi primera oportunidad profesional como desarrollador.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alan_Novas_Mateo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alan-novas-mateo-690853278)

---

### Tecnologías

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Bases de datos y herramientas**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Google Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflarepages&logoColor=white)

---

### Proyectos destacados

#### [Game Rank](https://github.com/Alan3420/Game-Rank) · [Demo](https://game-rank-2h1.pages.dev/)
Plataforma full-stack para descubrir, valorar y organizar videojuegos con datos de la API de RAWG.
- API REST en FastAPI con autenticación JWT, límite de peticiones y migraciones con Alembic.
- Migrada desde Flask sin cambios para el frontend: tests de contrato que comparan las 35 rutas con la versión original.
- Frontend en Vue 3 + Vite + PrimeVue con panel de administración y moderación de comentarios.
- 48 tests unitarios y 28 de contrato con pytest en GitHub Actions; desplegada en Google Cloud Run, Aiven MySQL y Cloudflare Pages.

#### [Pokémon Sonimu](https://github.com/Alan3420/pokemon_sonimu)
Aplicación web de batallas Pokémon por turnos desarrollada en equipo.
- Arquitectura por capas (rutas, servicios, repositorios, clientes) en Flask.
- Integración con PokeAPI mediante un cliente con caché LRU y expiración por TTL.
- Motor de combate con efectividad de tipos, precisión y orden por velocidad; historial persistente en SQLite.

#### [Generador de facturas PDF](https://github.com/Alan3420/generador-de-facturas-pdf)
Herramienta de automatización que genera facturas en PDF desde Excel o desde la terminal.
- Cálculo de IVA e IRPF y numeración correlativa.
- Modo interactivo y modo por lotes con Python, fpdf2 y openpyxl.
