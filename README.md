# Twitter (X) Clone 🚀

**Final Year Minor Project (2024)**

## 📌 Project Overview

This project is a **Twitter (X) Clone** developed as part of our **final-year minor project**.
The application allows users to **post tweets, like posts, follow users, and view timelines**, similar to a real-world social media platform.

The project focuses on **frontend development, API integration, cloud deployment, and database interaction**, following real-world full-stack architecture.

---

## 🧑‍🤝‍🧑 Team Contribution

* **My Role:**

  * Frontend development using **React**
  * API integration with backend
  * Deployment of backend on **AWS EC2**
  * Security configuration using **AWS IAM**
* **Teammate’s Role:**

  * Backend development using **Django**
  * Database logic and API creation

---

## 🛠️ Tech Stack

### Frontend

* **React.js** – Dynamic and responsive user interface
* **JavaScript (ES6+)**
* **HTML5 & CSS3**

### Backend

* **Django (Python)** – REST API development (handled by teammate)

### Database

* **AWS RDS (MySQL)** – Stores users, tweets, likes, and follower data

### Cloud & Deployment

* **AWS EC2** – Hosting the Django backend
* **AWS IAM** – Secure access control and permissions
* **HTTP/REST APIs** – Communication between frontend and backend

---

## ⚙️ Typical Workflow

```
User Action (React UI)
        |
        v
React sends HTTP API Request
        |
        v
Django Backend (Hosted on AWS EC2)
        |
        v
AWS RDS (MySQL Database)
        |
        v
Response sent back to Django
        |
        v
React updates UI dynamically
```

---

## 🔄 Detailed Workflow Explanation

1. **User Interaction (Frontend – React)**

   * User posts a tweet, likes a post, or follows another user.
   * React captures the event and triggers an API call.

2. **API Communication**

   * React sends HTTP requests to Django backend APIs.
   * Data is sent and received in JSON format.

3. **Backend Processing (Django on EC2)**

   * Django processes the request.
   * Business logic is applied.
   * Required database queries are executed.

4. **Database Interaction (AWS RDS – MySQL)**

   * Stores and retrieves structured data such as users, posts, likes, and followers.
   * Optimized queries ensure faster timeline loading.

5. **Response Handling**

   * Django sends processed data back to the frontend.
   * React updates the UI without page reload.

6. **Deployment & Security**

   * Backend hosted on AWS EC2.
   * IAM roles and security groups restrict unauthorized access.

---

## 🚧 Challenges Faced & Solutions

### 1. API Integration Issues

**Problem:** Frontend data format mismatched backend API responses.
**Solution:** Coordinated with backend teammate and tested APIs using Postman before integration.

### 2. Deployment & Security Configuration

**Problem:** Access issues due to IAM and security group misconfigurations.
**Solution:** Properly configured IAM roles and EC2 security rules to allow secure access.

### 3. Performance Optimization

**Problem:** Timeline loading was slow with increased data.
**Solution:** Backend query optimization and efficient frontend state management.

---

## ✅ Key Learnings

* Real-world **frontend–backend collaboration**
* Cloud deployment using **AWS EC2**
* Secure access using **IAM roles**
* API integration and debugging
* Understanding scalable social media architecture

---

## 📌 Conclusion

This project gave hands-on experience in **full-stack development**, **cloud deployment**, and **team collaboration**, closely simulating a real-world software development environment.

---

## 📎 Future Enhancements

* Real-time notifications
* Media uploads (images/videos)
* Advanced caching
* CI/CD pipeline integration

---

## 📧 Contact

For queries or collaboration, feel free to connect via GitHub.
