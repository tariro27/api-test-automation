# API Test Automation Suite

Automated API testing using **REST Assured** and **Postman + Newman**.

### 🚀 Features
- Covers GET, POST, PUT, DELETE
- JSON schema validation
- Data-driven testing
- CI/CD integration via GitHub Actions

### 🛠 Tech Stack
Java • REST Assured • Postman • Newman • Maven

### ▶ How to Run (Postman + Newman)
```bash
newman run postman_collections/sample_collection.json
```
### ▶ How to Run (REST Assured)
```bash
mvn clean test
