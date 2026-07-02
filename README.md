# 📚 Interactive E-Learning Platform for Special Education Students (MBK)

> A full-stack web application developed to support **Murid Berkeperluan Khas (MBK)** in Malaysian primary schools through interactive learning, gamified assessments, and learning analytics.

![Laravel](https://img.shields.io/badge/Laravel-12-red?style=for-the-badge&logo=laravel)
![Vue.js](https://img.shields.io/badge/Vue.js-3-42b883?style=for-the-badge&logo=vue.js)
![PHP](https://img.shields.io/badge/PHP-8-blue?style=for-the-badge&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-38BDF8?style=for-the-badge&logo=tailwind-css)
![CloudPanel](https://img.shields.io/badge/Deployment-CloudPanel-success?style=for-the-badge)

---

# 📖 Project Overview

This project was developed as a Final Year Project for the Bachelor of Computer Science (Software Engineering) at Universiti Sains Malaysia (USM).

The system is designed specifically for **students with learning disabilities (MBK)** enrolled in Malaysia's Special Education Integration Program (PPKI). It provides an engaging digital learning environment through interactive digital textbooks, gamified quizzes, role-based dashboards, and data-driven learning analytics.

Unlike traditional learning platforms, this system enables teachers and parents to monitor student engagement and learning progress while encouraging student independence through personalized learning experiences.

---

# ✨ Key Features

## 👨‍🎓 Student

- Secure Login
- Personalized Dashboard
- Interactive Digital Textbooks
- Gamified Science Quizzes
- Quiz History
- Progress Tracking
- Multiple Quiz Attempts

---

## 👩‍🏫 Teacher

- Teacher Dashboard
- Upload Educational Videos
- YouTube Content Management
- Student Performance Dashboard
- Learning Analytics
- Progress Reports

---

## 👨‍👩‍👧 Parent

- Parent Dashboard
- View Child Performance
- Learning Progress Monitoring
- Performance Analytics
- Student Independence Tracking

---

## 👨‍💼 Administrator

- User Management
- Student Management
- Teacher Management
- Parent Management
- School Registration
- System Administration

---

# 📊 Learning Analytics

One of the core features of this platform is the Learning Analytics module.

The system records:

- Quiz scores
- Quiz completion timestamps
- Student progress
- Learning trends
- Interaction history

Teachers can monitor student engagement through visual dashboards while parents can view their child's academic development.

The platform also analyses quiz completion timestamps to identify unusual answering behaviour that may indicate parental assistance, helping teachers better understand genuine student learning independence.

---

# 🏗 System Architecture


<img width="975" height="490" alt="image" src="https://github.com/user-attachments/assets/86753632-331f-4acd-9ba4-2aaa13a5fbac" />


The application follows the MVC architecture using Laravel while Vue.js provides a responsive and interactive frontend.

---

# 🛠 Technology Stack

## Frontend

- Vue.js
- Tailwind CSS
- JavaScript
- HTML5
- CSS3

## Backend

- Laravel
- PHP

## Database

- MySQL

## Authentication

- Laravel Authentication
- Role-Based Access Control (RBAC)

## Deployment

- CloudPanel
- Nginx
- Let's Encrypt SSL

## Development Methodology

- Agile Development
- MVC Architecture
- RESTful Design

---

# 👥 User Roles

The platform supports four different user roles.

| Role | Features |
|------|----------|
| Student | Learning Dashboard, Quizzes, Digital Textbooks |
| Teacher | Content Management, Analytics, Reports |
| Parent | Child Progress Monitoring |
| Administrator | User & School Management |

---

# 📚 Modules

## Student Dashboard

- Learning Progress
- Digital Textbooks
- Quiz Attempts
- Performance History

---

## Content Management

- Upload Learning Videos
- Manage Educational Resources
- YouTube Integration

---

## Interactive Learning

- Gamified Quizzes
- Multiple Attempts
- Score Tracking

---

## Performance Analytics

- Quiz Performance
- Progress Reports
- Learning Trends
- Student Independence Monitoring

---
# 📸 Screenshots
<img width="1656" height="904" alt="Screenshot 2026-06-05 145627" src="https://github.com/user-attachments/assets/1d98172d-789b-4b9f-9ce9-00bebd313659" />
<img width="1639" height="899" alt="Screenshot 2026-06-05 145446" src="https://github.com/user-attachments/assets/8706c928-6224-4cc3-90fb-ce2d872f8031" />
<img width="1622" height="888" alt="Screenshot 2026-06-05 145208" src="https://github.com/user-attachments/assets/70563499-e576-450d-8091-96949332093e" />
<img width="1615" height="890" alt="Screenshot 2026-06-05 145143" src="https://github.com/user-attachments/assets/bfeb277d-67df-4714-be57-85022d5cd861" />
<img width="1638" height="903" alt="Screenshot 2026-06-05 144950" src="https://github.com/user-attachments/assets/f5e3779d-ae7d-4923-82ff-9b8e361c74ed" />






# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

Install PHP dependencies

```bash
composer install
```

Install Node packages

```bash
npm install
```

Copy environment file

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Configure your database in `.env`

Run migrations

```bash
php artisan migrate
```

Start development server

```bash
php artisan serve
```

Compile frontend

```bash
npm run dev
```

---

# 📂 Project Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/

composer.json
package.json
README.md
```

---

# 🔒 Security Features

- Authentication
- Role-Based Access Control
- Input Validation
- CSRF Protection
- Session Management
- Secure Password Hashing

---

# 🧪 Testing

The system was tested using:

- Unit Testing
- Integration Testing
- System Testing
- User Acceptance Testing (UAT)

All major functionalities including authentication, quizzes, dashboards, analytics, and content management were validated before deployment.

---

# 🚀 Deployment

The application is deployed using:

- CloudPanel
- Nginx
- MySQL
- Let's Encrypt SSL

---

# 💡 Challenges

### Building Role-Based Access

Implemented four different dashboards with dedicated permissions for Students, Teachers, Parents, and Administrators.

### Learning Analytics

Developed an analytics engine capable of monitoring quiz completion timestamps, learning progress, and engagement metrics.

### Content Management

Integrated YouTube educational resources to allow teachers to deliver localized learning content directly through the platform.

---

# 🔮 Future Improvements

- AI-powered learning recommendations
- Mobile application
- Push notifications
- Offline learning mode
- Additional subjects
- Advanced analytics dashboard
- Multi-language support

---

# 👨‍💻 Developer

**Khalil Ahmad Bin Zainalabidin**

Bachelor of Computer Science (Software Engineering)

Universiti Sains Malaysia

LinkedIn:
https://www.linkedin.com/in/khalil-ahmad-bin-zainalabidin

Email:
khalilahmadbinzainalabidin@gmail.com

---

# 📄 License

This project is developed for academic and portfolio purposes.

Feel free to fork this repository for educational use.
