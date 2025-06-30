# Simple Java Servlet Web Application

This is a basic Java **web application built using Servlets and JSP** (without using Spring Framework). It demonstrates how to:

- Create a simple HTML form to collect student information
- Submit the form to a servlet
- Display a dynamic welcome message using form data

## 📁 Features

- No Spring, no frameworks — pure Servlets and JSP (if extended)
- `web.xml` based servlet configuration
- Form input using `index.html`
- Response handled by `Welcome.java`

---

## 🚀 How to Run

### ✅ Prerequisites

- Java JDK (8 or higher)
- Apache Tomcat 9 or higher
- Maven (optional but recommended)
- An IDE like Eclipse / VS Code or any text editor

---

### 🛠 Folder Structure

```
MyWebApp/
├── src/
│   └── main/java/Welcome.java
├── webapp/
│   ├── index.jsp
│   └── WEB-INF/
│       └── web.xml
|__ pom.xml
```

---

### 🔧 Steps to Run on Tomcat

1. **Download & Install Tomcat**  
   [https://tomcat.apache.org/download-90.cgi](https://tomcat.apache.org/download-90.cgi)

2. **Build the Project**

   - If using Eclipse: Right-click → Export → WAR file
   - Or manually compile Java file and keep folder structure

3. **Deploy to Tomcat**

   - Copy the generated `.war` file (or project folder) into:  
     `<TOMCAT_HOME>/webapps/`

4. **Start Tomcat**

   - Run `startup.bat` (Windows) or `startup.sh` (Linux/Mac) from the `bin` folder

5. **Access the App**
   - Open browser: [http://localhost:8080/MyWebApp/](http://localhost:8080/MyWebApp/)
   - Fill in the form and submit

---

## 🧑‍💻 Example

**Input:**

- Student: Alice
- Department: Computer Science

**Output:**

```
Welcome Alice from Computer Science
```

---

## 📌 Notes

- This is meant for educational/demo purposes.
- You can enhance it by adding JSP, JDBC, or switching to annotation-based servlet config.

---
