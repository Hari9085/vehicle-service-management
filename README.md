# 🚗 VehicleCare — Vehicle Service Management System

<p align="center">
  <strong>A modern web application for managing vehicle service records.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
</p>

## 📌 About the Project

**VehicleCare** is a web-based Vehicle Service Management System designed to organize customer information, vehicle details, and service records in one place.

The application provides a simple dashboard with three main operations — **Create, Read, and Update**. Users can add service records, search for specific records, modify existing information, and delete records when necessary.

The interface features a dark futuristic theme, neon accents, and an animated network background.

## ✨ Features

- 🔐 **User Authentication** — Registration and login interface.
- ➕ **Create Records** — Add customer, vehicle, and service details.
- 🔍 **Read & Search** — Search service records by customer name or service date.
- ✏️ **Update Records** — Edit existing service information.
- 🗑️ **Delete Records** — Remove unwanted service records from the Update section.
- 📊 **Dashboard Statistics** — View total, pending, in-progress, and completed services.
- 🏍️ **Vehicle Information** — Store vehicle number, brand, model, and service type.
- 📅 **Service Tracking** — Track service dates and current status.
- 🎨 **Modern UI** — Responsive dark theme with cyan and purple neon accents.
- 🌐 **Animated Background** — Moving particles and connected network lines.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, responsive layout, and animations |
| JavaScript | Frontend interaction and CRUD operations |
| Node.js | Backend runtime |
| Express.js | Server and API routes |
| MySQL | Relational database |
| Git & GitHub | Version control and project hosting |

## 🖥️ Application Modules

### 1. Create
Add a new vehicle service record with:
- Customer name
- Phone number and email
- Vehicle registration number
- Vehicle brand and model
- Service type
- Service date
- Service status

### 2. Read
- View matching service records.
- Search by customer name.
- Search by service date.
- Display only records matching the search criteria.

### 3. Update
- Search for an existing service record.
- Edit customer, vehicle, or service details.
- Save the updated information.
- Delete a record after confirmation.

### 4. Dashboard
View service statistics, including:
- Total services
- Pending services
- Services in progress
- Completed services

## 📁 Project Structure

```text
VehicleCare/
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── server.js
├── db.js
├── schema.sql
├── package.json
├── .gitignore
└── README.md
```

*The structure above is illustrative. Adjust it to match the actual files in your repository.*

## ⚙️ Installation and Setup

### Prerequisites

Install the following tools:

- [Node.js](https://nodejs.org/)
- [MySQL](https://dev.mysql.com/downloads/)
- [Git](https://git-scm.com/)

### Step 1: Clone the repository

```bash
git clone https://github.com/Hari9085/vehicle-service-management.git
cd vehicle-service-management
```

Replace the repository URL with your actual GitHub repository URL.

### Step 2: Install dependencies

```bash
npm install
```

If dependencies are not listed in `package.json`, install the packages required by your backend.

### Step 3: Configure MySQL

1. Start your MySQL server.
2. Open MySQL Workbench or your preferred MySQL client.
3. Execute the SQL statements in `schema.sql`.
4. Configure your database connection in `db.js`.

Use environment variables for database credentials rather than committing passwords to GitHub.

### Step 4: Start the application

```bash
node server.js
```

Open your browser and visit:

```text
http://localhost:3000
```

*These instructions assume your backend uses port 3000 and the file names shown above.*

## 🔄 CRUD Workflow

```text
              ┌───────────────────┐
              │    Home Page      │
              └─────────┬─────────┘
                        │
          ┌─────────────┼─────────────┐
          ▼             ▼             ▼
      ┌────────┐    ┌────────┐    ┌────────┐
      │ Create │    │  Read  │    │ Update │
      └───┬────┘    └───┬────┘    └───┬────┘
          │             │             │
          ▼             ▼        ┌────┴────┐
      Save Record   Search      Edit     Delete
                        │
                        ▼
                 Matching Results
```

## 🔒 Security Considerations

- Keep database credentials and session secrets out of source control.
- Validate user input on both the frontend and backend.
- Use parameterized SQL queries to reduce SQL injection risk.
- Hash passwords securely.
- Protect service-record API routes with appropriate authentication and authorization.
- Use HTTPS when deploying the application publicly.

## 🚀 Deployment

The frontend can be hosted on static hosting platforms such as GitHub Pages or Netlify.

**Important:** GitHub Pages cannot run a Node.js backend or connect directly to a MySQL server. To deploy the complete application, host the backend on a Node.js-compatible service and use a separately hosted MySQL database.

## 🎯 Project Objectives

- Apply CRUD operations in a real-world management application.
- Practice frontend and backend integration.
- Understand relational database operations.
- Build a searchable service-record management interface.
- Develop a responsive and user-friendly web application.

## 🔮 Future Improvements

- Service appointment booking.
- Customer service history.
- Automated service reminders.
- PDF invoices and service reports.
- Role-based access for administrators and service staff.
- Advanced filtering and reporting.

## 👨‍💻 Author

**Harish**

- GitHub: [@hari9085](https://github.com/hari9085)

## 📄 License

This project is available for educational and personal learning purposes. Add a formal license file if you intend to distribute it under a specific open-source license.
