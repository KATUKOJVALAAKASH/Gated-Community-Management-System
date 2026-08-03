# 🏘️ Gated Community Management System

A web-based **Gated Community Management System** developed using **Java Servlets, JSP, Hibernate, MySQL, HTML, CSS, and Bootstrap**. The application provides separate modules for **Residents** and **Administrators**, allowing residents to raise complaints and administrators to manage and resolve them efficiently.

---

## 📌 Features

### 👤 Resident
- Secure Registration & Login
- Raise Complaints
- View Submitted Complaints
- View Solved Complaints
- View Personal Profile
- Session-based Authentication

### 🛡️ Admin
- Secure Admin Login
- View All Complaints
- Update Complaint Status
- Manage Resident Complaints
- Logout Functionality

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Java | Backend Logic |
| Servlets | Request Handling |
| JSP | View Layer |
| Hibernate ORM | Database Operations |
| MySQL | Database |
| HTML5 | Structure |
| CSS3 | Styling |
| Bootstrap | Responsive UI |
| Apache Tomcat | Application Server |
| Maven | Dependency Management |

---

## 📂 Project Structure

```
GatedCommunityProject/
│
├── src/
│   ├── controller/
│   ├── dao/
│   ├── entity/
│   ├── util/
│   └── resources/
│
├── WebContent/
│   ├── css/
│   ├── images/
│   ├── jsp/
│   └── WEB-INF/
│
├── pom.xml
└── README.md
```

---

## 🚀 Functional Flow

```
Resident Registration
          │
          ▼
      Login
          │
          ▼
Resident Dashboard
     │      │
     │      ├────────► Raise Complaint
     │
     ├────────► View Complaints
     │
     ├────────► Solved Complaints
     │
     └────────► My Profile


Admin Login
      │
      ▼
Admin Dashboard
      │
      ├────────► View Complaints
      │
      └────────► Update Status
```

---

# 📸 Application Screenshots

## Home Page

> <img width="1536" height="842" alt="Screenshot 2026-08-03 134011" src="https://github.com/user-attachments/assets/82076ac0-b4cf-4fb6-a0fc-b66ea392fba0" />


```md
![Home](images/home.png)
```

---

## Resident Registration

> <img width="597" height="864" alt="Screenshot 2026-08-03 134202" src="https://github.com/user-attachments/assets/3825c7f3-4212-467b-a990-ac8111d11844" />


```md
![Register](images/register.png)
```

---

## Login Page

> <img width="630" height="602" alt="Screenshot 2026-08-03 134357" src="https://github.com/user-attachments/assets/29dd12d2-526e-4994-9740-b96dab292fba" />


```md
![Login](images/login.png)
```

---

## Resident Dashboard

> <img width="1366" height="847" alt="Screenshot 2026-08-03 134409" src="https://github.com/user-attachments/assets/fbb127e6-4553-4729-a6a2-75be104896d7" />


```md
![Resident Dashboard](images/resident-dashboard.png)
```

---

## Raise Complaint

> <img width="710" height="779" alt="Screenshot 2026-08-03 134433" src="https://github.com/user-attachments/assets/098ab704-1562-4403-a3b2-6f9f013fb45d" />


```md
![Raise Complaint](images/raise-complaint.png)
```

---

## My Complaints

> <img width="1319" height="562" alt="Screenshot 2026-08-03 134451" src="https://github.com/user-attachments/assets/0d0bbfd9-4226-49ec-a781-dea29e963c76" />


```md
![My Complaints](images/my-complaints.png)
```

---

## Solved Complaints

> <img width="1404" height="536" alt="Screenshot 2026-08-03 134631" src="https://github.com/user-attachments/assets/fc1e2195-7bf8-49a4-a171-b5b1704f202f" />


```md
![Solved Complaints](images/solved-complaints.png)
```

---

## Resident Profile

> <img width="849" height="827" alt="Screenshot 2026-08-03 134644" src="https://github.com/user-attachments/assets/a4505780-352e-45b7-b41c-034a52812f53" />


```md
![Profile](images/profile.png)
```

---

## Admin Dashboard

> <img width="1503" height="633" alt="Screenshot 2026-08-03 134703" src="https://github.com/user-attachments/assets/002c0764-be66-492f-9bee-1e3f20a6562b" />


```md
![Admin Dashboard](images/admin-dashboard.png)
```

---

# 🗄️ Database

The project uses **MySQL** with **Hibernate ORM** for persistence.

Main tables include:

- User
- Complaint
- Admin

Complaint Status:

- OPEN
- COMPLETED
- Pending

---

# ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/KATUKOJVALAAKASH/Gated-Community-Management-System.git
```

### 2. Import into Eclipse/IntelliJ

Import as a **Maven Existing Project**.

### 3. Configure MySQL

Create a database.

Example:

```sql
CREATE DATABASE gatedcommunity;
```

Update your Hibernate configuration with your database credentials.

### 4. Build the Project

```bash
mvn clean install
```

### 5. Deploy

Deploy the generated WAR file on **Apache Tomcat**.

### 6. Run

Open:

```
http://localhost:8080/GatedCommunityProject/
```

---

# 🔑 Default Admin Credentials

```
Username: admin
Password: admin
```

*(Change these according to your database configuration.)*

---

# ✨ Future Enhancements

- Email Notifications
- Visitor Management
- Maintenance Payment Module
- Resident Notice Board
- Event Management
- Role-Based Access Control
- Complaint Priority Levels
- Dashboard Analytics
- Search & Filter Complaints
- Mobile Responsive UI Improvements

---

# 👨‍💻 Author

**Akash Katukojvala**

- GitHub: https://github.com/KATUKOJVALAAKASH
- LinkedIn: https://www.linkedin.com/in/akash-katukojvala/

---

# 📄 License

This project is developed for educational and learning purposes. Feel free to fork, modify, and enhance it.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
