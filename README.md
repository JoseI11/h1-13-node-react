<a name="readme-top"></a>

<div align="center">
  <img src="no-country.jpg" alt="logo" width="140" height="auto" />
  <h1><b>Justina.io</b></h1>
  <p>MVP / prototipo desarrollado en hackathon (repositorio colaborativo).</p>
</div>

# 📗 Table of Contents
- [📖 About the Project](#about-project)
  - [🧩 Project Status](#project-status)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features (UI)](#key-features-ui)
  - [👤 My Contribution](#my-contribution)
  - [📸 Screenshots](#screenshots)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)

# 📖 Justina.io <a name="about-project"></a>
**Justina.io** es un MVP/prototipo desarrollado en un hackathon con el objetivo de explorar una plataforma para facilitar la interacción entre pacientes y profesionales de salud, incluyendo una base de UI para autenticación y un flujo inicial de gestión de turnos.

## 🧩 Project Status <a name="project-status"></a>
- Alcance: **MVP / prototipo de hackathon** (tiempo acotado).
- En el estado actual, el proyecto prioriza **UI y estructura inicial**, y no incluye un flujo end-to-end completo (integración total con backend/DB) para todas las funcionalidades.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://vitejs.dev/">Vite</a></li>
    <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://tailwindcss.com/">Tailwind CSS</a></li>
    <li><a href="https://zustand-demo.pmnd.rs/">Zustand</a></li>
    <li><a href="https://formik.org/">Formik</a></li>
    <li><a href="https://github.com/jquense/yup">Yup</a></li>
    <li><a href="https://axios-http.com/">Axios</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
    <li><a href="https://expressjs.com/">Express.js</a></li>
    <li><a href="https://www.prisma.io/">Prisma</a></li>
    <li><a href="https://github.com/kelektiv/node.bcrypt.js/">Bcrypt</a></li>
    <li><a href="https://github.com/motdotla/dotenv#readme">Dotenv</a></li>
    <li><a href="https://github.com/evanshortiss/env-var#readme">env-var</a></li>
    <li><a href="https://github.com/auth0/node-jsonwebtoken#readme">jsonwebtoken</a></li>
  </ul>
</details>

<details>
  <summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features (UI) <a name="key-features-ui"></a>
- **Login** (UI)
- **Registro de usuarios** (UI)
- **Recuperar contraseña** (UI)
- **Home/Landing** (UI)
- **Calendario / Turnero** (UI)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👤 My Contribution <a name="my-contribution"></a>
En el marco del hackathon, mis aportes se enfocaron en la experiencia de autenticación y UI:
- Implementación de la **pantalla de Login** y su estructura visual.
- Maquetación y estilos del **Registro de usuarios** (formularios y consistencia visual).
- Integración de librerías del stack del proyecto para formularios/validación y UI.

> Nota: al tratarse de un repositorio colaborativo, otras funcionalidades fueron trabajadas por otros integrantes del equipo.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📸 Screenshots <a name="screenshots"></a>
> Las capturas están alojadas dentro del repositorio para facilitar la revisión.

![Login](docs/screenshots/login.png)
![Registro](docs/screenshots/register.png)
![Recuperar contraseña](docs/screenshots/recover-password.png)
![Home](docs/screenshots/home.png)
![Calendario / Turnero](docs/screenshots/calendar.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# 💻 Getting Started <a name="getting-started"></a>

## Prerequisites <a name="prerequisites"></a>
- Node.js (recomendado 18+)
- npm / pnpm / yarn (según el proyecto)
- (Opcional) MySQL si se requiere backend/DB

## Setup <a name="setup"></a>
Clonar el repositorio:
```bash
git clone https://github.com/No-Country-simulation/h1-13-node-react.git
cd h1-13-node-react
```

Install <a name="install"></a>
Instalar dependencias en cada parte del proyecto (si aplica):
```bash
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
```
Usage <a name="usage"></a>
Ejecutar en modo desarrollo (si aplica):
```bash
# Frontend
cd client
npm run dev

# Backend
cd ../server
npm run dev
```
### Authors <a name="authors"></a>

LinkedIn: https://www.linkedin.com/in/mart%C3%ADn-kun-b13620209/
<br>
LinkedIn: https://www.linkedin.com/in/diego-vidal-lopez/
<br>
LinkedIn: https://www.linkedin.com/in/joseimhoff/
<br>
Gmail: Bjcampagnoli@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>
🔭 Future Features <a name="future-features"></a>

Integración completa de autenticación (end-to-end).

Persistencia y gestión completa de turnos con backend/DB.

Mejoras de validaciones y manejo de errores.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!
Feel free to check the issues page



<p align="right">(<a href="#readme-top">back to top</a>)</p> ```
