# ⚡ Bijli-Track

**Bijli-Track** is a responsive web application designed to help users **monitor and manage their electricity bills and electricity usage** through a simple and intuitive interface.

The application provides a centralized platform for recording electricity bill information, monitoring consumption, and analyzing electricity-related data over time.

---

## 🚀 Features

### 💡 Electricity Bill Monitoring

* Record electricity bill information
* Monitor electricity expenses over time
* Keep track of electricity consumption
* View historical bill information
* Organize electricity-related records in one place

### 📊 Usage & Bill Analysis

* View electricity usage data
* Analyze billing information
* Monitor changes in electricity expenses
* Compare electricity data across different billing periods
* Visualize relevant electricity information

### 📱 Responsive Design

* Fully responsive interface
* Works across desktop, tablet, and mobile devices
* Clean and user-friendly dashboard
* Modern UI with Tailwind CSS

### ☁️ Cloud Database

The application uses **Supabase** for backend services and data persistence.

* PostgreSQL database
* Supabase integration
* Secure data storage
* Real-time-ready backend infrastructure

---

## 🛠️ Tech Stack

| Technology       | Purpose                           |
| ---------------- | --------------------------------- |
| **React**        | Frontend user interface           |
| **TypeScript**   | Type-safe application development |
| **Supabase**     | Backend and database services     |
| **PostgreSQL**   | Relational database               |
| **Tailwind CSS** | Responsive UI styling             |
| **Vite**         | Development and build tooling     |
| **JavaScript**   | Application functionality         |

---

## 🏗️ Application Architecture

The application follows a modern frontend architecture with React on the client side and Supabase providing backend and database services.

```text
                    ┌──────────────────────┐
                    │        User          │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      React UI        │
                    │    TypeScript        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Supabase        │
                    │   Backend Services   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     PostgreSQL       │
                    │      Database        │
                    └──────────────────────┘
```

---

## 📁 Project Structure

```text
Bijli-Track/
│
├── public/
│
├── src/
│
├── supabase/
│
├── .gitignore
├── bun.lockb
├── components.json
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
├── vite.config.ts
└── README.md
```

### Directory Overview

| Directory / File     | Description                                       |
| -------------------- | ------------------------------------------------- |
| `src/`               | Main application source code                      |
| `public/`            | Public static assets                              |
| `supabase/`          | Supabase configuration and database-related files |
| `tailwind.config.ts` | Tailwind CSS configuration                        |
| `vite.config.ts`     | Vite configuration                                |
| `package.json`       | Project dependencies and scripts                  |
| `tsconfig.json`      | TypeScript configuration                          |
| `eslint.config.js`   | ESLint configuration                              |

---

# ⚙️ Prerequisites

Before running the project, make sure you have:

* **Node.js**
* **npm** or **Bun**
* **Git**
* A **Supabase** project

---

# 🔧 Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/Bijli-Track.git
cd Bijli-Track
```

## 2. Install Dependencies

### Using npm

```bash
npm install
```

### Using Bun

```bash
bun install
```

---

## 3. Configure Supabase

Create a project in Supabase and configure the required environment variables for the application.

Create a `.env` file in the project root:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Replace the placeholder values with the credentials from your Supabase project.

> **Security:** Never commit your `.env` file or private Supabase credentials to GitHub.

---

## ▶️ Running the Application

### Using npm

```bash
npm run dev
```

### Using Bun

```bash
bun run dev
```

The development server will provide a local URL, typically:

```text
http://localhost:5173
```

Open the URL in your browser to use Bijli-Track.

---

# 📊 How Bijli-Track Works

The application is designed around the following workflow:

```text
        User
          │
          ▼
   Enter Bill Information
          │
          ▼
     Store Bill Data
          │
          ▼
   Monitor Electricity
       Expenses
          │
          ▼
    Analyze Historical
         Data
          │
          ▼
     Make Informed
     Usage Decisions
```

Users can maintain their electricity billing information and use the application to better understand their electricity expenses over different billing periods.

---

# 🎯 Project Objectives

Bijli-Track was developed to provide practical experience with:

* Modern React development
* TypeScript
* Responsive web application development
* Database integration
* Supabase
* PostgreSQL
* Data management
* Electricity bill monitoring
* Data visualization and analysis
* Modern UI development with Tailwind CSS
* Frontend application architecture

---

# 🔮 Future Improvements

Potential improvements include:

* 📈 Advanced electricity usage charts
* 📊 Monthly and yearly bill comparisons
* 💰 Bill cost forecasting
* 🔔 Bill due-date reminders
* 📱 Improved mobile experience
* 📉 Electricity consumption trend analysis
* 📄 Bill history export
* 📥 PDF bill upload
* 💡 Personalized electricity-saving recommendations
* 📊 More detailed analytics dashboard

---

# 👨‍💻 Author

**Shoaib Ahmed Abbasi**

**BS Software Engineering Student**

### Bijli-Track

Built with:

**React · TypeScript · Supabase · PostgreSQL · Tailwind CSS · Vite**

---

⭐ **If you found Bijli-Track useful, consider giving the repository a star!**
