
# MahilaSuraksha – Women Safety Complaint App

MahilaSuraksha is a simple and user-friendly web-based complaint form designed to help women report safety concerns such as harassment, abuse, and threats.
The form collects essential details and sends them to a backend server for processing.
---

## 👨‍💻 Group Members
Mayuri Surve

Pragati Gore

Vaishnvi Shete

---

## 🛠️ Technologies Used
HTML5 – Structure of the web page.

CSS3 – Styling and responsive design.

JavaScript (Fetch API) – Handles form submission and API requests.

Node.js / Express (Backend) – To store complaint details (optional).

---

## 📁 Project Structure

```
MahilaSuraksha/
│
├── backend/ # Server-side code
│ ├── src/main/java/com/mahila/...
│ ├── controller/
│ ├── model/
│ ├── repository/
│ └── service/
│
├── frontend/ # Client-side code
│ ├── index.html
│ ├── style.css
│ └── script.js
│
├── README.md
└── pom.xml
```

---

## ✨ Features
- 📝 Online complaint form
- 📍 Location details capture
- 📂 Multiple complaint types (Harassment, Abuse, Threats, Other)
- ✅ Declaration before submission
- 📡 Backend REST API integration (Spring Boot)
- 📊 Data storage in PostgreSQL

---

## 🚀 How to Run This Project

### ⚙️ Step 1: Backend (Spring Boot + PostgreSQL)

1. **Clone the repo**  
```bash
git clone https://github.com/UnnatiManeDeshmukh/MahilaSurksha.git
cd MalilaSurksha/backend
```

2. **Create a PostgreSQL database**  
Database name: `complaint_db`

3. **Configure DB in `application.properties`**  
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/complaint_db
spring.datasource.username=postgres
spring.datasource.password=unnati22
spring.jpa.hibernate.ddl-auto=update
```

4. **Run the Spring Boot app**  
```bash
./mvnw spring-boot:run

---

### 🌐 Step 2: Frontend (HTML + CSS + JS)

1. Open terminal in `frontend/` folder  
```bash
cd ../frontend
python -m http.server
```

2. Visit the web page  
[http://localhost:3108](http://localhost:3108)

> 📢 Ensure backend is running at `http://localhost:3108`

---

## 📸 Preview

### 🧾 Request Form  
![Request Form](https://github.com/UnnatiManeDeshmukh/BooksBuddy/blob/main/Frontend1/OutPut.JPG)

### ✅ Admin Panel  
![Admin Panel](https://github.com/UnnatiManeDeshmukh/BooksBuddy/blob/main/Frontend1/OutPut1.JPG)



### 🧪 API Testing (Postman)  
![API Postman Output](https://github.com/UnnatiManeDeshmukh/BooksBuddy/blob/main/Frontend1/POST_OP.JPG)
---


##📞 Contact
For any queries or issues, please contact:

- 📧 Email: mayurisurve1517@gmail.com
- 📧 Email: vaishnavishete1507@gmail.com
- 📧 Email: pragatigore8822@gmail.com
 - 🌐 GitHub: [UnnatiManeDeshmukh](https://github.com/UnnatiManeDeshmukh)




---
