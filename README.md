# University Grade Management App

A desktop application built with **WinDev** to simplify the management of university student records and grades. It provides a secure, role-based interface for admins, teachers, and students to manage and view academic information.

---

## Features

- **Role-based login**: Secure access for Admins, Teachers, and Students.
- **Comprehensive Management**: Easily manage students, teachers, courses, and grades.
- **Automatic Grade Calculation**: Streamlined and accurate grade processing.
- **Visual Grade Consultation**: Role-specific visual displays of academic performance.
- **Organized Database**: Simple and efficient database structure for easy data handling.

---

## Technologies Used

- **WinDev**: For robust desktop application development.
- **HFSQL**: For efficient database management.

---

## How to Run the App

1.  **Clone this repository**:
    ```bash
    git clone [https://github.com/Taha2053/PFA1.git](https://github.com/Taha2053/PFA1.git)
    ```
    (Note: You will need WinDev to access the source code.)
2.  **Download the application**: Get the executable from the releases page:
    ```bash
    [https://github.com/Taha2053/PFA1/tags](https://github.com/Taha2053/PFA1/tags)
    ```

---

## Application Components

### Login Page

A secure login screen with role selection and authentication.

![Login Page](images/login.png)

Automatic authentication based on the user's role:

<p align="center">
  <img src="images/admin_login.png" alt="Admin Login Page" width="220"/>
  <img src="images/admin_logged_in.png" alt="Admin logged in" width="220"/>
  <img src="images/Teacher_loggedIn.png" alt="Teacher logged in" width="220"/>
  <img src="images/admin_logged_in.png" alt="Student logged in" width="220"/>
</p>

---

### Dashboards

**Admin Dashboard**
![Admin Dashboard](images/Admin_dashboard.png)

**Teacher Dashboard**
![Teacher Dashboard](images/teacher%20Dashboard.png)

**Student Dashboard**
![Student Dashboard](images/Student%20Dashboard.png)

---

### Profile Settings

Logout and application settings.

![Logout and settings](images/LogOut%20and%20Settings.png)

Profile Settings.

![Profile Settings](images/Profile%20Settings.png)

---

### Management Windows

**Manage Teachers**
![Manage Teachers](images/Gerer%20les%20profs.png)

**Manage Students**
![Manage Students](images/Gerer%20Les%20etudiants.png)

**Manage Departments**
![Manage Departments](images/Gerer%20les%20Departements.png)

**Manage Modules (Courses)**
![Manage Modules](images/Gerer%20les%20modules.png)

**Manage Programs (Formations)**
![Manage Programs](images/Gerer%20les%20Formations.png)

**Exam Dates Management**
![Exam Dates Management](images/Gerer%20les%20dates%20des%20examens%20.png)

**News Management**
![News Management](images/Gerer%20les%20Actualites.png)

**Semester Report (PV Semestriel)**
![Semester Report](images/PV%20Semestriel.png)

---

### Communication & Documents

**Contact Page**
<p align="center">
  <img src="images/Contact.png" alt="Contact" width="300"/>
  <img src="images/Envoyer%20un%20E-mail.png" alt="Send an Email" width="300"/>
</p>

**Annual Calendar**
![Calendar](images/Calendar.png)

**Statistics**
![Statistics](images/Statistics.png)

**Add Documents (PDF)**: Allows adding PDF documents for students to access.
![Add Document](images/Ajout%20des%20documents.png)

---

### Data Entry and Modification

**Add a Teacher**: (Applies similarly to adding other elements in the application.)
![Add a Teacher](images/Ajouter%20un%20prof.png)

**Modify a Teacher**: (Applies similarly to modifying other elements in the application.)
![Modify a Teacher](images/Modifier%20un%20prof.png)

---

### Grade Management for Teachers and Students

**Teacher's Grade Entry**: Teachers can input student grades.
![Student Grades (Teacher View)](images/Les%20Notes%20des%20Etudiants.png)

**Student's Grade Access**: Students can view their grades, module averages, module credits, attendance records, modules to retake (due to low average), and modules to retake (due to excessive absences or module average below 10).
![Student's Grades (Student View)](images/Les%20notes_WinEtudiant.png)

---

### Usability Features

**Filters**: Filters are provided in each window to facilitate convenient access to information.

**Deletion Confirmation**: Deleting elements from the application requires that the element is not linked to another and that the password must be entered to confirm the deletion.