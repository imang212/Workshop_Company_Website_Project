# Machine Workshop – Company Website

**Machine Workshop** is a company website created for a small family business engaged in metal machining and locksmithing.  
The site was designed and developed as a complete system with administration, a database, responsive design, and multilingual support.

## Author
**Author:** Patrik Poklop  
**Supervisor:** Bc. Jakub Pokorný  
**School:** Secondary Industrial School, Resslova 5, Ústí nad Labem  
**Class:** 4ITB  
**Year:** 2022/2023  

## Project Overview
The goal of this project was to create a modern and responsive website for a metal machining workshop.  
The website serves to present the company, display offered services, showcase machines, and allow customers to submit job requests online.

### Key Features:
- Company presentation and service descriptions  
- Machine gallery with image zoom functionality  
- Online order submission form  
- News section with admin content management  
- User registration and login system  
- Language switcher (CZ/EN)  
- Cookies consent popup  
- Responsive design for mobile devices  

## Technologies Used
| Technology | Description |
|-------------|-------------|
| **HTML5** | Structure and content of the website. |
| **CSS3 / Bootstrap** | Styling, layout, and responsive design. |
| **JavaScript (ES6)** | Interactive elements (slider, menu, fetch API). |
| **PHP** | Server-side logic, login, registration, database handling. |
| **MySQL** | Database for users, orders, and news. |
| **jQuery / AJAX** | Dynamic data loading and deletion without reloading the page. |

## Main Functionalities
- **Responsive Navigation** – adapts to both PC and mobile devices  
- **Automatic Slider** – JavaScript-powered image slider (manual and auto switching)  
- **User Registration and Login** – input validation, password encryption, duplication checks  
- **Language Switching** – handled via PHP sessions  
- **News Section** – admin-only management, data fetched via `fetch API`  
- **Order Form** – sends requests to email and stores them in the database  
- **Cookies Banner** – user consent popup for cookies  
- **Admin Panel** – manage orders and users via PHP, jQuery, and AJAX  

## Database Design

**ERD Model:**  
<img width="923" height="569" alt="image" src="https://github.com/user-attachments/assets/9c874b10-47ed-4470-8e8a-fc3c6b413416" />

The database contains the following tables:
- `users` – user accounts  
- `orders` – customer orders  
- `news` – news posts  

Each account links its own `user_id` with related orders and news.

## Website Structure
Main sections of the website:
1. **Homepage** – Title, company introduction, and an automatic image slider  
2. **Services** – Overview of company activities (flexbox/grid layout)  
3. **Order Form** – PHP form to send requests and save them to the database  
4. **Price List & Materials** – Table listing materials used by the workshop  
5. **Machine Gallery** – Images with zoom functionality via `zoom.js`  
6. **News** – Loaded and deleted dynamically via `fetch API` and `Ajax`  
7. **Contacts** – Email, phone, business hours, and embedded map  

## Responsiveness
- Fully optimized for mobile devices (Android/iOS)  
- Expandable mobile menu powered by JavaScript  
- Adaptive layout for smaller screens  

## Admin Panel
- **Logged-in users** can view and manage their own account information  
- **Admin users** can:
  - Manage and delete orders  
  - Add or remove news posts  
  - View all registered users  
- All actions are handled dynamically using `AJAX` and `jQuery`  

## Learning Outcomes
During this project, I learned to:
- Efficiently combine **HTML, CSS, PHP, and JavaScript**  
- Design and implement **database logic using MySQL**  
- Use **Bootstrap** for responsive layouts  
- Implement **interactive web features** with AJAX and fetch API  

## Screenshots
### **Homepage**
<img width="907" height="458" alt="image" src="https://github.com/user-attachments/assets/0293c4d4-72ed-4bbb-aa1a-504504ce0e99" />

### **Account Management**
<img width="905" height="443" alt="image" src="https://github.com/user-attachments/assets/f374d3e5-6882-4565-bf86-d72f637ea827" />

### **Order Management**
<img width="902" height="476" alt="image" src="https://github.com/user-attachments/assets/701f59d1-9f09-4343-a73c-3782aaa0f542" />

### **News Management**
<img width="907" height="451" alt="image" src="https://github.com/user-attachments/assets/119e0d89-fef6-49c6-9af7-22a9523f99ea" />

### **Responsive Layout**
<img width="294" height="555" alt="image" src="https://github.com/user-attachments/assets/1d247b76-9baa-47eb-9dc4-205d76a3e9e2" />

## References

1. [HTML – Wikipedia](https://cs.wikipedia.org/wiki/Hypertext_Markup_Language)  
2. [CSS – Wikipedia](https://cs.wikipedia.org/wiki/Kask%C3%A1dov%C3%A9_styly)  
3. [MySQL – Wikipedia](https://cs.wikipedia.org/wiki/MySQL)  
4. [PHP – Wikipedia](https://cs.wikipedia.org/wiki/PHP)  
5. [PHP Official Documentation](https://www.php.net)  
6. [JavaScript – Wikipedia](https://cs.wikipedia.org/wiki/JavaScript)  
7. [Bootstrap – Wikipedia](https://cs.wikipedia.org/wiki/Bootstrap)

---
