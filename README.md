<div align="center">
  <img src="https://img.icons8.com/color/96/000000/student-housing.png" alt="Logo" width="80" height="80">
  <h1>🏠 Student Accommodation Management System</h1>
  <p><strong>Streamline. Simplify. Succeed.</strong></p>
  <p>A modern, high-performance web application designed to manage student housing facilities with elegance and efficiency.</p>
</div>

---

## 🔗 Live Demo

<div align="center">
  <a href="[https://your-vercel-app-url.vercel.app](https://student-accommodation-app.vercel.app)" target="_blank">
    <img src="https://img.shields.io/badge/🌐_View_Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo">
  </a>
  <br/>
  <sub>Click above to explore the live application</sub>
</div>

---

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
</div>

---

## ✨ Overview

Say goodbye to chaotic spreadsheets and disconnected systems. The **Student Accommodation Management System** brings all your daily operational tasks into one **sleek, intuitive dashboard**. Designed for administrators and staff, this system transforms how you manage students, rooms, finances, and maintenance.

**Core Benefits:**
- 🚀 **Lightning Fast** – Powered by Vite + React
- 🎯 **Intuitive UI** – Clean, modern interface
- 📱 **Fully Responsive** – Works on any device
- 🔒 **Secure & Reliable** – Built with best practices

---

## 🧭 Core Modules

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <img src="https://img.icons8.com/fluency/48/000000/user-group-man-man.png"/>
        <br/>
        <strong>👨‍🎓 Student Management</strong>
        <br/>
        <sub>Add, manage, and assign students to rooms</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://img.icons8.com/fluency/48/000000/bedroom.png"/>
        <br/>
        <strong>🛏️ Room Management</strong>
        <br/>
        <sub>Track availability & occupancy status</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://img.icons8.com/fluency/48/000000/money-bag.png"/>
        <br/>
        <strong>💳 Payment Tracking</strong>
        <br/>
        <sub>Record payments & manage balances</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://img.icons8.com/fluency/48/000000/maintenance.png"/>
        <br/>
        <strong>🛠️ Maintenance</strong>
        <br/>
        <sub>Log & track maintenance requests</sub>
      </td>
    </tr>
  </table>
</div>

### 📊 Dashboard Overview
Your command center at a glance:
- **Total Students** – Current occupancy count
- **Room Occupancy** – Live availability metrics
- **Payment Overview** – Real-time financial snapshot
- **Maintenance Activity** – Active & pending requests

---

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <th>Category</th>
      <th>Technologies</th>
    </tr>
    <tr>
      <td><strong>🎨 Frontend</strong></td>
      <td>React 18 • Vite • Tailwind CSS • React Router • Axios</td>
    </tr>
    <tr>
      <td><strong>⚙️ Backend</strong></td>
      <td>Node.js • Express • REST API</td>
    </tr>
    <tr>
      <td><strong>🗄️ Database</strong></td>
      <td>PostgreSQL • Prisma ORM</td>
    </tr>
    <tr>
      <td><strong>🚀 Deployment</strong></td>
      <td>GitHub • Vercel (Frontend) • Render/Heroku (Backend)</td>
    </tr>
  </table>
</div>

---

## 📁 Project Structure

```bash
src/
├── components/          # Reusable UI components
│   ├── DashboardCard.jsx
│   ├── StudentTable.jsx
│   └── Navbar.jsx
├── pages/              # Main views
│   ├── Dashboard.jsx
│   ├── Students.jsx
│   ├── Rooms.jsx
│   ├── Payments.jsx
│   └── Maintenance.jsx
├── layouts/            # Layout wrappers
├── services/           # API calls
├── context/            # React context providers
├── hooks/              # Custom hooks
├── App.jsx
├── main.jsx
└── index.css
