# Module5Bootstrap
Assignment for Module 5 with bootstrap
Deployed on 
https://module5bootstrap.netlify.app/
# 📚 Knowledge Check — Bootstrap Basics, Utilities, Forms, and Components

> **Module 5 Assessment**  
> Create a fully functional, responsive web page using Bootstrap utilities, forms, tables, images, and components.

---

## 📝 Overview
This assignment assesses your understanding of **Bootstrap concepts** by building a complete web page. You will work with:
- Forms & validation
- Tables & responsive layouts
- Image utilities
- Buttons & display utilities
- Navigation bars

---

## 🚀 Instructions

### **1️⃣ Create a New Webpage Using Bootstrap**
- Set up a basic HTML file with the **Bootstrap CDN** linked in the `<head>` section.
- Use a `container` or `container-fluid` to structure your layout.

---

### **2️⃣ Part 1 — Form Creation and Layout**
- Build a **Registration Form** using Bootstrap’s form components:
  - Fields: **First Name**, **Last Name**, **Email**, **Password**, and a **terms checkbox**.
  - Use Bootstrap’s **grid layout** to place **First Name** & **Last Name** side-by-side.
  - Apply validation classes to make **Email** and **Password** required.
  - Add a **Submit** button styled with `btn-success`.

---

### **3️⃣ Part 2 — Table for Displaying Data**
- Simulate data collection:
  - Create a table using Bootstrap’s **table component**.
  - Hard-code sample user data.
  - Add `table-striped` and `table-hover` for better readability.
  - Make the table responsive with `table-responsive`.

---

### **4️⃣ Part 3 — Image and Button Utilities**
- Add a responsive image (`img-fluid`) inside a `container-fluid`.
- Below the main image, add a circular image (`rounded-circle`).
- Create **two buttons**:
  - One always visible.
  - One hidden on small screens using `d-none d-md-block`.

---

### **5️⃣ Part 4 — Navigation Bar**
- Build a **responsive navbar** with links: **Home**, **About**, **Contact**.
- Navbar should **collapse into a hamburger menu** on smaller screens.
- Use Bootstrap utilities and components for styling.

---

## 📋 Project Requirements

| Feature | Details |
|---------|---------|
| **Form Creation & Layout** | Bootstrap form components, grid for side-by-side fields, validation, `btn-success` submit button. |
| **Table Styling** | Responsive table, sample data, striped + hoverable rows. |
| **Image Utilities** | `img-fluid`, `rounded`, `rounded-circle`. |
| **Button Utilities** | Display utilities (`d-none d-md-block`). |
| **Navigation Bar** | Collapses on small screens, Bootstrap styling. |
| **Responsiveness & Layout** | Proper container usage, media queries, and responsive utilities. |

---

## 📤 Submission Guidelines

### **GitHub Repository**
- Create a **GitHub repo** for this assignment.
- Include your HTML, CSS, and any assets.
- Add a **README.md** describing the project.

### **Testing**
- Navbar collapses on small screens.
- All buttons, forms, tables, and images are styled properly.
- Works across devices and browsers.

### **File Structure**
```plaintext
📁 your-repo/
 ├── index.html
 ├── style.css
 ├── 📁 images/
 └── README.md
🎯 Bonus
Add comments in code highlighting extra features.

📊 Grading Criteria (25 Points)
Criteria	Points	Description
Form Creation	6 pts	Proper form components, grid, validation.
Table Styling	5 pts	Responsive table with styling.
Image Utilities	4 pts	Correct usage of Bootstrap image classes.
Button Utilities	4 pts	Responsive visibility utilities.
Navigation Bar	5 pts	Responsive navbar with proper collapse.
Responsiveness	1 pt	Page adjusts across screen sizes.

📌 Bootstrap CDN Example
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap JS (with Popper) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

---

If you want, I can also make an **“Enhanced Version”** of this README that **includes inline Bootstrap HTML examples** for each part (form, table, navbar, etc.) so students can copy and paste working snippets directly into their projects. That would make it more interactive and beginner-friendly.
