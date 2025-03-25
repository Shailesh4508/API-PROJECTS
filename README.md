# 🚀 API Projects Through Postman

This repository contains a collection of API testing projects using **Postman**, covering **REST** and **SOAP APIs**, along with automation using **Newman** (Postman’s CLI runner). 📌

## 📂 Repository Contents

### ✅ API Testing Projects
- 🔹 **Basic GET Request** - Demonstrates a simple GET request using Postman.
- 🔹 **E2E Scenario #1** - An end-to-end API testing scenario covering multiple interactions.
- 🔹 **Project #1: JSON Server (Dummy API)** - CRUD operations using a dummy REST API.
- 🔹 **Project #2: SOAP API Testing** - Testing SOAP-based web services.
- 🔹 **Project #3: Restful Booker API** - Covers functional API testing using the Restful Booker API.
- 🔹 **Project #4: Data-Driven Testing** - Demonstrates parameterized API testing.

---
## 🌐 Working with REST and SOAP APIs in Postman

### 📌 REST APIs
**REST (Representational State Transfer)** is a widely used web service communication method that utilizes HTTP verbs like **GET, POST, PUT, DELETE**.

#### 🔧 Steps to Send a REST API Request in Postman:
1️⃣ Open Postman and create a new request.
2️⃣ Select **GET** (or other HTTP method).
3️⃣ Enter the API **endpoint URL**.
4️⃣ Click **Send** and view the response.

### 📌 SOAP APIs
**SOAP (Simple Object Access Protocol)** is a messaging protocol that exchanges structured information.

#### 🔧 Steps to Send a SOAP Request in Postman:
1️⃣ Create a new **POST** request.
2️⃣ Enter the **SOAP endpoint URL**.
3️⃣ Set the **Content-Type** header to `text/xml`.
4️⃣ In the **Body** section, select `raw` and enter the **SOAP XML request**.
5️⃣ Click **Send** to execute the request and review the response.

📌 **For more details on SOAP in Postman, check [this guide](https://blog.postman.com/making-soap-requests-using-postman-2014/).**

---
## 🤖 Automating API Tests with Newman

**Newman** is Postman’s command-line collection runner that enables automated API testing and integration into **CI/CD pipelines**. 🚀

### 📌 Install Newman
Ensure **Node.js** and **npm** are installed, then run:
```bash
npm install -g newman
```

### 📌 Run a Collection using Newman
```bash
newman run <collection-file>.json
```
🔹 Replace `<collection-file>.json` with your Postman collection file.

### 📌 Run a Collection with Environment Variables
```bash
newman run <collection-file>.json -e <environment-file>.json
```
🔹 Useful when working with **multiple environments**.

📌 **For detailed Newman usage, check [Postman’s official docs](https://www.postman.com/product/automated-testing/).**

![image](https://github.com/user-attachments/assets/59954999-fd46-4676-8b5c-ac6d4510c415)

---
## 🎯 Conclusion

This repository serves as a **practical guide** for testing APIs using **Postman** and **Newman**. 📢

🔹 Learn **REST and SOAP API testing**
🔹 Implement **automated API tests**
🔹 Explore **real-world API projects**

✨ Happy API Testing! ✨
