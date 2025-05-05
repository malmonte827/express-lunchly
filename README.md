# 🍽️ Lunchly

> A restaurant reservation web app built with Express.js, PostgreSQL, and Nunjucks templating to manage customers and reservations.
[![Node.js](https://img.shields.io/badge/node-%3E=14-brightgreen)](https://nodejs.org/) [![Express](https://img.shields.io/badge/express-%3E=4.17-blue)](https://expressjs.com/) [![PostgreSQL](https://img.shields.io/badge/postgresql-%3E=12-blue)](https://www.postgresql.org/)

---

## 📋 Table of Contents

1. [About](#about)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation & Setup](#installation--setup)  
   - [Database Setup](#database-setup)  
8. [Contributing](#contributing)  
10. [Contact](#contact)  

---

## 🌟 About

**Lunchly** is a server-rendered web application for managing restaurant customers and reservations. It demonstrates:

- Class vs. static methods for data models  
- Server-side rendering with Nunjucks (Jinja-style templates)  
- CRUD flows for customers and reservations  

---

## ✨ Features

- **Customer Management:** View all customers, add new customers, and edit customer info.  
- **Reservation Management:** Create and view upcoming reservations per customer.  
- **Full Name Helper:** `Customer.fullName()` returns a customer’s complete name for templates.  
- **Static & Instance Methods:** Use `Customer.get(id)`, `Customer.save()` and similar `Reservation.save()` methods to abstract DB logic.  
- **Server-Side Templating:** Render HTML pages with Nunjucks, injecting data from PostgreSQL.

---

## 🛠 Tech Stack

- **Runtime:** Node.js  
- **Framework:** Express.js  
- **Database:** PostgreSQL  
- **Templating:** Nunjucks  
- **Development:** nodemon, SQLseed via Python script  
- **Styling:** CSS

---

## 🏁 Getting Started

### Prerequisites

- Node.js v14 or higher  
- PostgreSQL v12 or higher  
- Python 3 (optional; to inspect or regenerate sample data with `seed.py`)

### Installation & Setup

1. **Clone the repo**  
   ```bash
   git clone https://github.com/malmonte827/express-lunchly.git
   cd express-lunchly
   ```

2. **Install dependencies**
   ```bash
    npm install
   ```
3. **Database Setup**
   ```bash
    createdb lunchly
    psql lunchly < data.sql
    ```
---
## Contributing

We welcome contributions! To contribute:

- Fork the repository

- Create a new branch (git checkout -b feature-name)

- Commit your changes (git commit -m 'Add new feature')

- Push to the branch (git push origin feature-name)

- Open a pull request
---
## Contact

For questions or suggestions, reach out:

- Email: malmonte827@gmail.com
