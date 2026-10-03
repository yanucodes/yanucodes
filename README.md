# Hi there, I'm Yanu 👋

I'm a Python developer who specializes in backend development, data analysis and image processing. For more than eight years, I wrote code in astrophysics research to reduce telescope data, analyze observations, and build the interactive tools my research projects needed.

In the last year, I completed the Software Engineering program at Masterschool Institute of Technology and took Coursera courses, and I built my own projects along the way. Now I'm looking for an opportunity to apply my skills to software with real, practical value for people.

## 🚀 Featured projects

- **[HomeShip](https://github.com/yanucodes/HomeShip)**: a REST API for a co-op chores game. Your household is a spaceship crew, and neglected chores raise yellow/red alerts that slow down or stop the ship.
  - **Architecture:** layered (router → service → repository), with JWT authentication, Alembic migrations, and an hourly idempotent cron job that respects each household's time zone.
  - **CI/CD with GitHub Actions:** unit and integration tests, an end-to-end smoke test against the containerized stack, and automatic deployment of the Docker image to Render.

  `FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `Docker` · `GitHub Actions`
- **[job-search-tool](https://github.com/yanucodes/job-search-tool)**: a job-search tracker for applications, recruiter contacts, fairs, and networking. Each one moves through its own timeline, and the history can be exported as a German PDF summary for the Arbeitsagentur. `Flask` · `Jinja2` · `LaTeX`
- **[Knitty](https://github.com/yanucodes/Knitty)**: an iOS app that counts rows and keeps per-row notes while knitting without a pattern. It uses an MVVM architecture, with a data model I iterated on until it represented a knitting project well. `Swift` · `SwiftUI` · `SwiftData`
- **Knitty-Vision** `WIP`: an extension for Knitty that counts stitches from photos.
  - **Method:** counting algorithms based on astronomical image analysis (source detection, profile fitting), with 15 approaches compared on a hand-labeled test set.
  - **Results:** the best method counts 75% of photos exactly and 95% within one stitch (MAE 0.35).
  - The source stays private during active development.

  `Python` · `SciPy` · `photutils` · `NumPy`

## 🔭 From research

Before software development, I worked as an astrophysics researcher ([publications on SciX](https://scixplorer.org/search?p=1&q=author%3A%22Khusanova%22&sort=score+desc&sort=date+desc&d=astrophysics)). Python was my daily tool for data reduction, image processing, analysis, and visualization.

### Selected projects

- **[obs_sofi](https://github.com/yanucodes/obs_sofi)** *(MSc thesis)*: a Python data-reduction package for the SOFI camera, integrated into the LSST (Vera Rubin Observatory) software stack.
- **[data_viewer](https://github.com/yanucodes/data_viewer)** *(PhD, 2017)*: an interactive Matplotlib tool that I used to inspect candidate z > 5 galaxies one by one (spectra, photometry, and best-fit models) for [Khusanova et al. 2020](https://doi.org/10.1051/0004-6361/201935400).
- **JWST data** *(postdoc)*: an interactive Matplotlib tool for detecting and removing detector-persistence artifacts in JWST/NIRCam data. The data I reduced and the source catalog I built are now used by collaborators.

## 🌱 I'm currently learning

- **AWS:** to gain more experience in cloud computing and to migrate HomeShip to AWS.
- **GenAI engineering:** to understand more deeply how AI works and to find new ways to apply it in my projects.
- **React:** by building the frontend for HomeShip.

## 🛠 Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)

## 📫 How to reach me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ykhusanova)
