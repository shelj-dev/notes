# Foxtech Private Solutions

## Full Stack

- [Frontend](#frontend)  
  - [HTML](#html)
  - [CSS](#css)
  - [JS](#js)
- [Backend](#backend)  
- [Database](#database)  

### Stacks

- [MERN Stack](#mern-stack)  
- [MEAN Stack](#mean-stack)  
- [Python-Django Stack](#python-django-stack)  
- [LAMP Stack](#lamp-stack)  

---

## Frontend

Frontend refers to the part of a website or application that users interact with directly. It's everything you see on a website — from fonts and colors to dropdown menus and sliders.

**Key Technologies:**

- **HTML** → Structures the web content  
- **CSS** → Styles the content (colors, layout, spacing)  
- **JavaScript** → Adds interactivity and dynamic behavior  
- **React.js / Angular / Vue.js** → JavaScript frameworks/libraries for building dynamic UIs

---

## Backend

Backend is the server-side of a website or application. It handles data storage, security, and business logic, and communicates with the frontend.

**Key Technologies:**

- **Node.js + Express.js** → JavaScript runtime and web framework  
- **Django (Python)** → High-level Python framework  
- **PHP** → Popular scripting language, used with Apache  
- **Java / Spring Boot** → Enterprise-grade backend development  
- **APIs** → Used to send and receive data between frontend and backend

---

## Database

Databases are used to store, organize, and retrieve data in applications. They are a critical part of backend systems.

**Types of Databases:**

- **SQL Databases (Structured):**  
  - **MySQL**, **PostgreSQL**, **SQLite**  
  - Use tables, rows, and columns  
  - Suitable for structured data and relationships

- **NoSQL Databases (Unstructured or semi-structured):**  
  - **MongoDB**, **Firebase**  
  - Store data as JSON-like documents  
  - More flexible for modern web apps

---

## MERN Stack

>**MERN = MongoDB + Express.js + React.js + Node.js**

- MongoDB → NoSQL Database (document-based)  
- Express.js → Backend framework (JavaScript)  
- React.js → Frontend library (JavaScript)  
- Node.js → JavaScript runtime (for backend)

---

## MEAN Stack

>**MEAN = MongoDB + Express.js + Angular + Node.js**

- MongoDB → NoSQL Database  
- Express.js → Backend framework  
- Angular → Frontend framework (TypeScript)  
- Node.js → JavaScript runtime

---

## Python-Django Stack

>**Python-Django = Python + Django**

- Python → High-level programming language  
- Django → Backend framework (MTV architecture)  
- Features: Built-in ORM, admin panel, authentication, scalability

---

## LAMP Stack

>**LAMP = Linux + Apache + MySQL + PHP**

- Linux → Operating System  
- Apache → Web server  
- MySQL → Relational database (SQL-based)  
- PHP → Server-side scripting language

---
---

## HTML

**HTML** stands for **HyperText Markup Language**.  
It is used to create the basic **structure** of a webpage.

- Think of it as the **skeleton** of the website.
- It uses **tags** like `<h1>`, `<p>`, and `<img>` to define content.

🔤 **Basic HTML Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Welcome!</h1>
    <p>This is my very first website.</p>
  </body>
</html>
```

## CSS (Cascading Style Sheets)

**CSS** is used to style HTML content.  
It changes how your website looks — colors, fonts, layout, spacing, and more.

- Change background color  
- Set font styles  
- Align text  
- Add spacing (margin, padding)  
- Make the site look good on all screen sizes

```css

body {
  background-color: lightblue;
}

h1 {
  color: darkblue;
}

p {
  font-size: 18px;
}
```

## JavaScript (JS)

**JavaScript** is a programming language used to make websites interactive.

It runs inside the browser and allows you to:

- Show messages
- React to user actions (like clicks)
- Change content on the page
- Validate forms
- Create dynamic effects

---

## Example: Button Click

```html
<button onclick="sayHello()">Click Me</button>

<script>
  function sayHello() {
    alert("Hello, JavaScript Beginner!");
  }
</script>
```
