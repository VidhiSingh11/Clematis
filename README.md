# 🌿 Clematis - Mental Health & Wellness Platform

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

> **"Counseling. Coaching. Consultation."**

**Clematis** is a frontend web project designed to provide a safe haven for people to explore their mental health. It offers resources, booking for therapy sessions, and community workshops to help users find support and guidance.

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Services Offered](#-services-offered)
- [Design System](#-design-system)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Contact](#-contact)

---

## 🔭 About the Project

At Clematis, the mission is to ensure everyone has the right to access mental health support. The platform connects users with mental health professionals for individual, family, and couples therapy, as well as creative workshops.

The project is a static frontend prototype featuring a responsive design, booking interfaces, and resource libraries.

---

## ✨ Key Features

* **Responsive Navigation:** Fully responsive navigation bar with active state highlighting.
* **Resource Library:** A dedicated section for sharing knowledge, including breathing techniques, self-care habits, and wellness tips.
* **Event Management:** Display of upcoming creative community events like Crocheting, Embroidery, and Pottery workshops.
* **Testimonial Slider:** A JavaScript-powered auto-sliding carousel displaying user success stories.
* **Pricing Plans:** A tiered pricing display for memberships (Monthly, Family, Virtual Aid).
* **User Authentication UI:** Frontend design for User Login and Sign Up pages.

---

## 🧘 Services Offered

Users can view and "book" the following sessions via the **Book Online** page:

| Service | Price | Duration |
| :--- | :--- | :--- |
| **Group Wellness** | ₹1,500 | 1 hr |
| **Corporate Seminars** | ₹1,100 | 1 hr |
| **Personal Wellness** | ₹900 | 1 hr |
| **Family Workshop** | ₹1,500 | 1 hr |
| **Support Group** | ₹1,000 | 1 hr |
| **Virtual Consultation** | ₹850 | 1 hr |

---

## 🎨 Design System

The project utilizes a specific nature-inspired color palette and typography.

### Color Palette
* **Primary Green:** `#0b3910` (Backgrounds, Headers)
* **Cream/Beige:** `#fff8eb` (Text, Cards)
* **Accent Gold:** `#e4c58a` (Buttons, Highlights)
* **Active State:** `#F08475` (Salmon/Pink for active links)

### Typography
* **Headings:** 'Corben', cursive (Imported via Google Fonts)
* **Body Text:** Arial, Helvetica, sans-serif

---

## 🛠 Tech Stack

* **HTML5:** Semantic structure for all pages (`index.html`, `contact.html`, etc.).
* **CSS3:** Custom styling in `style.css` combined with **Bootstrap 5.3.0** for grid systems and components.
* **JavaScript:**
    * Bootstrap Bundle (CDN) for interactive components like the navbar toggler.
    * Custom vanilla JS for the Testimonial Image Slider.
* **Icons:** FontAwesome v6.0.0.

---

## 🚀 Getting Started

To run this project locally, you do not need a backend server as it is currently a static implementation.

1.  **Clone or Download the Repository.**
2.  **Ensure File Structure:**
    Make sure `style.css` is in the same folder as your `.html` files.
3.  **Launch:**
    Open `index.html` in any modern web browser (Chrome, Edge, Firefox).

### Project Structure
```text
/Clematis
├── index.html       # Homepage (Hero, About, Events)
├── BookOnline.html  # Service listing and booking UI
├── plans.html       # Pricing and Membership plans
├── resources.html   # Articles and Tips
├── contact.html     # Address and Contact Info
├── login.html       # Sign Up/Login Form
└── style.css        # Global Stylesheet
