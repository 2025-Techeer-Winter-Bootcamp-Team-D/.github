<p align="center">
  <a href="https://github.com/your_repo">
    <img src="로고_이미지_URL" width="900" style="height:auto;" />
  </a>
</p>

# 🔮 Table of Contents
- [Introduction](#-introduction)
- [Demo](#-demo)
- [System Architecture](#-system-architecture)
- [ERD](#-erd)
- [Tech Stack](#-tech-stack)
- [API](#-api)
- [Monitoring](#-monitoring)
- [How to Start](#-how-to-start)
- [Member](#-member)
<br>

# 📣 Introduction
실시간 주가 데이터, 기업 공시, 뉴스를 통합 분석하는 금융 정보 플랫폼입니다.

### URL
<blockquote>https://your-service-url.com</blockquote>

### Repositories
| Repository | Description |
|:---:|:---|
| [Backend](../backend) | Django 기반 API 서버 |
| [Frontend](../frontend) | 프론트엔드 애플리케이션 |
<br>

# 🎬 Demo
### 메인페이지
<img align="center" width="1000" alt="Main" src="메인페이지_이미지_URL">
<br><br>

### 기업 검색 & 기업 상세 페이지
<img align="center" width="1000" alt="Stock" src="주가조회_이미지_URL">
<br><br>

### 산업 페이지
<img align="center" width="1000" alt="News" src="뉴스분석_이미지_URL">
<br><br>

### 기업 비교 페이지
<img align="center" width="1000" alt="Disclosure" src="공시정보_이미지_URL">
<br><br>

# 🛠️ System Architecture
<img width="1405" alt="System Architecture" src="https://github.com/user-attachments/assets/4db2dd25-43b0-47e8-8e35-865de939a8a0" />
<img width="1385" alt="Data Pipeline" src="https://github.com/user-attachments/assets/2eae30f5-31ed-48f2-bc24-80ed80fdc9c2" />
<br><br>

# 🔑 ERD
<img width="1657" alt="ERD" src="https://github.com/user-attachments/assets/fc6fce42-a753-448c-8dfd-10c7fee212fa" />
<br><br>

# 💻 Tech Stack
<div align="center">
  <table>
    <tr>
      <th>Field</th>
      <th>Technology</th>
    </tr>
    <tr>
      <td><b>Frontend</b></td>
      <td>
        <!-- 프론트엔드 기술 스택 추가 -->
        <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
        <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
        <img src="https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white">
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white">
        <img src="https://img.shields.io/badge/Channels-092E20?style=for-the-badge&logo=django&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Database</b></td>
      <td>
        <img src="https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black">
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
        <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
        <img src="https://img.shields.io/badge/cAdvisor-0078D7?style=for-the-badge&logo=google&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>External API</b></td>
      <td>
        <img src="https://img.shields.io/badge/KIS_API-003366?style=for-the-badge&logoColor=white">
        <img src="https://img.shields.io/badge/DART_API-003366?style=for-the-badge&logoColor=white">
        <img src="https://img.shields.io/badge/Naver_API-03C75A?style=for-the-badge&logo=naver&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>ETC</b></td>
      <td>
        <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
      </td>
    </tr>
  </table>
</div>
<br>

# 📗 API
<img width="1580" height="1229" alt="image" src="https://github.com/user-attachments/assets/2677f0f1-9b7d-47f2-9737-6b8387468e92" />
<img width="1534" height="752" alt="image" src="https://github.com/user-attachments/assets/f69a140f-04d9-4d38-8ba1-f20cd360f7f3" />
<img width="1510" height="627" alt="image" src="https://github.com/user-attachments/assets/3f8f3611-ddda-4115-abfa-78ba7adbbb1d" />
<img width="1518" height="551" alt="image" src="https://github.com/user-attachments/assets/db5f4d1d-4f32-4842-bb25-f0c93e35f257" />


<br><br>

# 📊 Monitoring
<h3 align="left">Prometheus & Grafana</h3>
<table>
    <tr>
        <th colspan="2">Django Metrics</th>
    </tr>
    <tr>
        <td><img src="Grafana_이미지_URL_1" alt="Django Metrics"></td>
        <td><img src="Grafana_이미지_URL_2" alt="Django Metrics 2"></td>
    </tr>
    <tr>
        <th colspan="2">cAdvisor</th>
    </tr>
    <tr>
        <td><img src="cAdvisor_이미지_URL_1" alt="cAdvisor"></td>
        <td><img src="cAdvisor_이미지_URL_2" alt="cAdvisor 2"></td>
    </tr>
</table>
<br><br>

# 🚀 How to Start
#### 1. Clone The Repository
```bash
git clone https://github.com/your-org/Backend.git
git clone https://github.com/your-org/Frontend.git
```

#### 2. Backend ENV Setting
```bash
# Backend/.env
SECRET_KEY=
DEBUG=

# Database
DATABASE_HOST=
DATABASE_NAME=
DATABASE_USER=
DATABASE_PASSWORD=

# Redis
REDIS_URL=

# Celery
CELERY_BROKER_URL=

# External APIs
KIS_APP_KEY=
KIS_APP_SECRET=
DART_API_KEY=
NAVER_CLIENT_ID=
NAVER_CLIENT_SECRET=
GEMINI_API_KEY=
```

#### 3. Run Docker
```bash
docker-compose up --build
```

#### 4. Frontend Install & Run
```bash
yarn install
yarn run dev
```
<br>

# 👥 Member
| Name | 이름1 | 이름2 | 이름3 | 이름4 |
|:---:|:---:|:---:|:---:|:---:|
| Profile | <img width="100px" height="110px" src="프로필_이미지_URL_1" /> | <img width="100px" height="110px" src="프로필_이미지_URL_2" /> | <img width="100px" height="110px" src="프로필_이미지_URL_3" /> | <img width="100px" height="110px" src="프로필_이미지_URL_4" /> |
| Role | Team Leader, Backend | Backend | Frontend | Frontend |
| GitHub | <a href="https://github.com/"><img src="http://img.shields.io/badge/username1-green?style=social&logo=github"/></a> | <a href="https://github.com/"><img src="http://img.shields.io/badge/username2-green?style=social&logo=github"/></a> | <a href="https://github.com/"><img src="http://img.shields.io/badge/username3-green?style=social&logo=github"/></a> | <a href="https://github.com/"><img src="http://img.shields.io/badge/username4-green?style=social&logo=github"/></a> |

---

<div align="center">

**Techeer Winter 2025**

</div>
