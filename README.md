## 🚀 My Projects [[RU]](https://github.com/andreyDanilenko/andreyDanilenko/blob/main/README.ru.md)

---

### 🌐 [https://lifedream.tech](https://lifedream.tech) — main site
Articles and a test chat. Monolithic application. **In development**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Repository:** [go-angular-pg](https://github.com/andreyDanilenko/go-angular-pg)

---

### 📊 [https://habits.lifedream.tech](https://habits.lifedream.tech) — habit tracker
ERP system with the first module "Habits". Separate repositories for frontend and backend. **In development**

#### Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![FSD](https://img.shields.io/badge/FSD-2C2D72?style=for-the-badge&logo=featured&logoColor=white)

**Repository:** [habits-client](https://github.com/andreyDanilenko/habits-client)

#### Backend
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

**Repository:** [habits-api](https://github.com/andreyDanilenko/habits-api)

---

### 🐳 [deployment-automation](https://github.com/andreyDanilenko/deployment-automation) — infrastructure
Docker orchestration for running all projects behind a single Nginx. Automatic deployment via GitHub Actions.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Repository:** [deployment-automation](https://github.com/andreyDanilenko/deployment-automation)

---

## 🔗 Project Relationships

```mermaid
graph TD
    A[deployment-automation] --> B[go-angular-pg]
    A --> C[habits-client]
    A --> D[habits-api]
    B --> E[lifedream.tech]
    C --> F[habits.lifedream.tech]
    D --> F
```

*Main projects are deployed via `deployment-automation` and run in a single Docker network behind a shared Nginx.*

---

## 🧪 Test Projects

### 📁 [react_test](https://github.com/andreyDanilenko/react_test) — product catalog with filters
Test assignment: product catalog with authorization, sorting, and cart.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![RTK Query](https://img.shields.io/badge/RTK_Query-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![FSD](https://img.shields.io/badge/FSD-2C2D72?style=for-the-badge&logo=featured&logoColor=white)

**Stack:** React 19, TypeScript, Redux Toolkit + RTK Query, React Router v7, Tailwind CSS v4, Vite, FSD

**Repository:** [react_test](https://github.com/andreyDanilenko/react_test)

---

### 📁 [weather_vue](https://github.com/andreyDanilenko/weather_vue) — weather (OpenWeatherMap)
Test application demonstrating API integration.

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=for-the-badge&logo=element&logoColor=white)

**Repository:** [weather_vue](https://github.com/andreyDanilenko/weather_vue)

---

### 📁 [account-manager](https://github.com/andreyDanilenko/account-manager) — account management form
Test assignment: account management form with validation and Pinia state persistence.

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Repository:** [account-manager](https://github.com/andreyDanilenko/account-manager)

---

### 📁 [test_node_js](https://github.com/andreyDanilenko/test_node_js) — sticky notes board (WebSocket + REST)
Test assignment: prototype module for real-time collaborative virtual boards.

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)

**Repository:** [test_node_js](https://github.com/andreyDanilenko/test_node_js)
