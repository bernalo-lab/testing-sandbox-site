
# 🧪 Software Testing Sandbox

A hands-on, Docker-powered learning environment where students can explore manual, automation, API, performance, and security testing.

## 🚀 Features

- **WebGoat** – Security testing on a vulnerable Java app
- **Mutillidae** – Full-stack security testing
- **RESTful Booker** – REST API testing
- **Jenkins** – CI/CD pipelines
- **OWASP ZAP** – Security scanning
- **Selenium Grid** – UI automation infrastructure
- **k6** – Performance testing

## 📁 Folder Structure

```
.
├── docker-compose.yml
├── index.html
└── performance
    └── k6
        └── test.js  # Add your k6 scripts here
```

## 🧰 Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## ⚙️ Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/testing-sandbox-site.git
cd testing-sandbox-site
```

2. Launch all services:

```bash
docker-compose up -d
```

3. Open the learning site:

- Open `index.html` in a browser
- Or host it locally using [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code

## 🌐 Access Your Tools

- WebGoat → http://localhost:8080  
- Mutillidae → http://localhost:8081  
- RESTful Booker → http://localhost:8082  
- Jenkins → http://localhost:8083  
- OWASP ZAP → http://localhost:8084  
- Selenium Grid → http://localhost:4444

## 📄 License

MIT License
