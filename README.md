# 🌱 Adaptive Nutrition Site

**AdaptiveNutritionSite** is a web platform for automating the selection and accounting of school meals for primary school students. It drastically reduces teachers' administrative workload and provides the school cafeteria with accurate production data, helping minimize food waste and errors.

---

## 🎯 Project Goal

Develop and implement a system that allows students (with parental support) to select meals weekly, automatically aggregates and validates choices, and generates structured reports for teachers and the cafeteria.

---

## 📝 Key Features

- **Student/Parent Interface:**  
  Simple weekly meal selection with a single click per day. Intuitive UI for primary school students.

- **Teacher/Admin Interface:**  
  Dashboard showing students who have or haven't made their choices, with automated weekly class summaries.

- **Cafeteria Reporting:**  
  One-click export to Excel with detailed and aggregated reports for efficient meal preparation.

- **Roles & Permissions:**  
  Different roles (Student/Parent, Teacher, Administrator, Cafeteria) with access control.

- **Automated Data Handling:**  
  Eliminates manual data collection and consolidation; supports allergy management and special diets.

---

## 💻 Technology Stack

- **Backend:** Python / Django (MVC architecture)  
- **Frontend:** Django Templates (HTML, CSS, JS)  
- **Database:** PostgreSQL  
- **Excel Reporting:** openpyxl library  
- **Authentication & Security:** Django built-in auth, GDPR/FZ-152 compliant for student data

---

## 🏗 Architecture

- **Three-tier architecture:** Client – Server – Database  
- **Models:** Class, Pupil, Dish, DailyMenu, WeeklyBreakfasts  
- **Controllers:** Views handling business logic and data aggregation  
- **Templates:** Rendered HTML pages for parents, teachers, and admins

---

🎨 UX/UI Design

Minimalist and intuitive design for primary school students

Color scheme: neutral (blue, black, white)

Student view: one-page weekly menu selection

Teacher/admin view: admin panel + class dashboards with automatic highlights (green for chosen, red for missing)

No unnecessary navigation – focus on completing tasks quickly and accurately

🔒 Security & Compliance

User roles and permissions

GDPR / Russian FZ-152 compliant handling of personal data

Reliable authentication and authorization via Django

📌 Key Advantages

Reduces teacher workload by up to 3 hours per week

Provides accurate and standardized meal reports

Ensures dietary restrictions and allergies are respected

Minimizes food waste by 15–25%

Scalable and extendable for multiple schools

🔗 Live Prototype & Demo

https://adaptivenutrition.onrender.com/
