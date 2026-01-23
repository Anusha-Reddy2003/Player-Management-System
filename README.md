
# 🏏 Player Management System (Java + Hibernate + MySQL)

A full-stack **Java Web Application** built using **Servlets, JSP, Hibernate (JPA), and MySQL** to manage cricket players. Tables are auto-generated using `persistence.xml` and annotated Entity classes (no manual SQL table creation needed).

---

## 📁 Tech Stack

- **Backend**: Java Servlets, Hibernate (JPA)
- **Frontend**: JSP, HTML, CSS
- **Database**: MySQL (Tables auto-created via Entity classes)
- **ORM Tool**: Hibernate with `persistence.xml`
- **IDE**: Eclipse (Maven Project)
- **Build Tool**: Maven

---

## 🔧 Features

- Add New Players
- View All Players
- Auto Table Creation using Hibernate
- Clean MVC Structure (Servlet → DAO → Entity)
- Easy Deployment using Apache Tomcat

---

## 💡 Folder Structure
Player-Management-System/  
├── src/main/java/  
│ ├── controller/ # Servlets  
│ ├── dao/ # Data Access Objects (Hibernate)  
│ └── entity/ # Player Entity (JPA)  
├── src/main/webapp/  
│ ├── add-player.jsp  
│ ├── index.jsp  
│ └── WEB-INF/web.xml # Deployment Descriptor  
├── pom.xml # Maven config  
├── persistence.xml # Hibernate + JPA config  
└── README.md  

---

## 🧪 Database Setup

- ✅ No need to manually create tables in MySQL.
- Hibernate auto-generates the table from your `Player` entity when the app runs.
- Make sure you update `persistence.xml` with your DB username and password.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Anusha-Reddy2003/Player-Management-System.git
   ```
2. Open in Eclipse (as a Maven project).  
3. Configure Apache Tomcat server.  
4. Run on server.  

Visit:  
http://localhost:8080/Player-Management-System/add-player.jsp

---

## 📸 Demo

![Player Management System UI]
https://github.com/Anusha-Reddy2003/Player-Management-System/blob/main/Screenshots/MainPage.png
https://github.com/Anusha-Reddy2003/Player-Management-System/blob/main/Screenshots/AddPlayer.png
https://github.com/Anusha-Reddy2003/Player-Management-System/blob/main/Screenshots/DisplayPlayers.png
---

## 🎯 Use Case

Helps sports organizations or clubs manage player information efficiently with a user-friendly interface and database-backed persistence.

---

## 🧠 What I Learned

- Hands-on experience with Servlet life cycle and request handling
- Integrated Hibernate ORM with JPA for auto table creation
- MVC pattern implementation in a real-world project
- Configuring and deploying a Java web app on Tomcat

---

## ✅ Prerequisites

- Java 8+
- Apache Tomcat 9+
- Maven installed
- MySQL Server running

---

## 🛠️ Build & Deploy

```bash
mvn clean install
# Deploy WAR to Tomcat
```
---

## 🐞 Known Issues

- No validation on inputs (to be added using JavaScript)
- No update/delete functionality yet

## 📝 To-Do

- [ ] Add client-side validation with JavaScript
- [ ] Add search and filter functionality
- [ ] Convert to Spring Boot with REST APIs
- [ ] Add unit tests

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---


## 🔮 Future Plans

- Add JavaScript for dynamic validation  
- Convert to Spring Boot  
- Add player stats, filtering, and update/delete options  
