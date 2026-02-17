# SP Office – Police Complaint Management Website

## 📌 Project Overview

This project is a **Police SP Office Web Portal** developed to digitize and simplify public interaction with the police department. The system allows citizens to submit complaints online, check complaint status, and enables administrators (police staff) to manage and monitor cases through a dashboard panel.

The goal of this project is to reduce manual paperwork, improve transparency, and provide faster communication between citizens and the police department.

---

## 🎯 Key Features

### Citizen Module

* Online Complaint Registration
* Complaint Status Tracking
* Secure Login for Users
* Public Information Pages

### Admin (Police Staff) Module

* Admin Login Panel
* Dashboard to view complaints
* Manage complaint records
* Monitor case progress

---

## 🧰 Technologies Used

### Frontend

* HTML5
* CSS3
* Tailwind CSS (Responsive UI Design)
* JavaScript (Client‑side functionality)

### Tools & Build

* PostCSS
* Autoprefixer
* Node.js (for build tools only)

### Server / Deployment

* Microsoft IIS (Internet Information Services)
* Static Website Hosting

---

## 📁 Project Folder Structure

```
my-website/
│
├── public/
│   ├── index.html          → Home page
│   ├── login.html          → User login
│   ├── admin-login.html    → Admin login
│   ├── complaint.html      → Complaint registration form
│   ├── status.html         → Complaint status checking
│   └── dashboard.html      → Admin dashboard
│
├── tailwind.config.js      → Tailwind configuration
├── postcss.config.js       → PostCSS configuration
├── package.json            → Build dependencies
└── node_modules/           → Installed packages
```

---

## ⚙️ How to Run Locally (Development)

### Step 1: Install Node.js

Download and install Node.js from: [https://nodejs.org](https://nodejs.org)

### Step 2: Install Dependencies

Open terminal inside **my-website** folder and run:

```
npm install
```

### Step 3: Build Tailwind CSS

Run the Tailwind build command:

```
npx tailwindcss -i ./src/input.css -o ./public/output.css --watch
```

### Step 4: Open Website

Open:

```
public/index.html
```

in your browser.

---

## 🌐 Deployment on IIS Server (Production)

### 1. Enable IIS in Windows

* Go to Control Panel → Programs → Turn Windows features on or off
* Enable:

  * Internet Information Services
  * IIS Management Console
  * World Wide Web Services

### 2. Create Website Folder

Copy the **public** folder into:

```
C:\inetpub\wwwroot\spoffice
```

### 3. Configure IIS

1. Open **IIS Manager**
2. Right‑click "Sites" → Add Website
3. Set:

   * Site Name: spoffice
   * Physical Path: C:\inetpub\wwwroot\spoffice
   * Port: 80 (or any free port)
4. Click OK

### 4. Run Website

Open browser and visit:

```
http://localhost/spoffice
```

---

## 🔐 System Workflow

1. User registers a complaint using the complaint form.
2. Data is recorded and assigned a complaint ID.
3. User checks status using complaint ID.
4. Admin logs in and monitors all submitted complaints via dashboard.

---

## 🚀 Advantages

* Reduces manual register work
* Saves time for police staff
* Easy complaint tracking
* Transparent process for citizens
* Accessible from anywhere

---

## 👨‍💻 Author

**Developed as a Government Police Office Digitalization Project**

This project demonstrates web development, UI design, and IIS deployment skills suitable for real‑world government office applications.

---

## 📜 License

This project is for educational and demonstration purposes.
