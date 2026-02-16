## 🚀 Мои проекты

---

### 🌐 [https://lifedream.tech](https://lifedream.tech) — главный сайт
Статьи и тестовый чат. Монолитное приложение. **В разработке**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Репозиторий:** [go-angular-pg](https://github.com/andreyDanilenko/go-angular-pg)

---

### 📊 [https://habits.lifedream.tech](https://habits.lifedream.tech) — трекер привычек
ERP-система с первым модулем "Привычки". Отдельные репозитории для фронтенда и бэкенда. **В разработке**

#### Фронтенд
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![FSD](https://img.shields.io/badge/FSD-2C2D72?style=for-the-badge&logo=featured&logoColor=white)

**Репозиторий:** [habits-client](https://github.com/andreyDanilenko/habits-client)

#### Бэкенд
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

**Репозиторий:** [habits-api](https://github.com/andreyDanilenko/habits-api)

---

### 🐳 [deployment-automation](https://github.com/andreyDanilenko/deployment-automation) — инфраструктура
Docker-оркестрация для запуска всех проектов за одним Nginx. Автоматический деплой через GitHub Actions.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Репозиторий:** [deployment-automation](https://github.com/andreyDanilenko/deployment-automation)

---

## 🔗 Взаимосвязь проектов

```mermaid
graph TD
    A[deployment-automation] --> B[go-angular-pg]
    A --> C[habits-client]
    A --> D[habits-api]
    B --> E[lifedream.tech]
    C --> F[habits.lifedream.tech]
    D --> F
```

*Основные проекты разворачиваются через `deployment-automation` и работают в единой Docker-сети за общим Nginx.*

---

## 🧪 Тестовые проекты

### 📁 [weather_vue](https://github.com/andreyDanilenko/weather_vue) — погода (OpenWeatherMap)
Тестовое приложение для демонстрации работы с API.

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=for-the-badge&logo=element&logoColor=white)

**Репозиторий:** [weather_vue](https://github.com/andreyDanilenko/weather_vue)

---

### 📁 [account-manager](https://github.com/andreyDanilenko/account-manager) — управление учетными записями
Тестовое задание: форма управления учетными записями с валидацией и сохранением в Pinia.

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Функционал:**
- Добавление/удаление учетных записей
- Два типа записей: LDAP (без пароля) и Локальная (с паролем)
- Валидация полей с визуальной индикацией ошибок
- Поле "Метка" с парсингом строки в массив объектов
- Сохранение состояния в Pinia с персистентностью

**Репозиторий:** [account-manager](https://github.com/andreyDanilenko/account-manager)

---

### 📁 [test_node_js](https://github.com/andreyDanilenko/test_node_js) — доска со стикерами (WebSocket + REST)
Тестовое задание: прототип модуля для совместной работы на виртуальных досках.

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)

**Функционал:**
- CRUD-операции для стикеров через REST API
- Рассылка событий через WebSocket (socket.io) всем подключенным клиентам
- Классовый стиль архитектуры
- Docker-окружение для PostgreSQL и Redis
- Semantic Commits, ESLint + Prettier

**Дополнительные возможности:**
- Аутентификация через JWT
- Управление порядком элементов (слои)

**Репозиторий:** [test_node_js](https://github.com/andreyDanilenko/test_node_js)
