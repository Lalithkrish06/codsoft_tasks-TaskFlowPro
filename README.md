<h1 align="center">🚀 TaskFlow Pro — Modern Project Management Platform</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Active">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

<p align="center">
  <strong>Plan • Organize • Collaborate • Deliver</strong>
  <br><br>
  A modern full-stack project management workspace for teams to manage projects, organize tasks, track progress, collaborate efficiently, and visualize project performance.
</p>

---

## 🌐 Platform Access

<div align="center">

### 🚀 Explore TaskFlow Pro

<a href="https://taskflow.lalithkrish.dev/">
  <img src="https://img.shields.io/badge/Live_Platform-TASKFLOW.LALITHKRISH.DEV-00C853?style=for-the-badge" alt="Live Platform">
</a>
<a href="https://github.com/Lalithkrish06/TaskFlowPro">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository">
</a>

</div>

---

## 🎥 Project Demonstration

<div align="center">

### 🚀 TaskFlow Pro — Project Management in Action

<a href="https://www.linkedin.com/posts/lalithkrish-data_reactjs-nodejs-mongodb-ugcPost-7478385414290972672-Ex4G/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFOj_WYBncOFydeAPBILXlA2BQoiO9StjuA">
  <img src="https://img.shields.io/badge/Watch_Project_Demo-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Project Demonstration">
</a>

</div>

---

## 📖 Project Overview

**TaskFlow Pro** is a modern project management platform designed to help individuals and teams plan, organize, execute, and monitor projects from a centralized workspace.

The platform combines **project management, Kanban task boards, calendar scheduling, team collaboration, analytics, notifications, search, and report generation** into a unified productivity experience.

Built with a modern frontend architecture and Supabase-powered backend services, TaskFlow Pro demonstrates practical software engineering concepts including **authentication, reusable components, responsive design, data visualization, scalable architecture, and collaborative workflows**.

---

## 🎯 Platform Vision

TaskFlow Pro is built around a simple productivity cycle:

```text
                 🎯 PLAN
                   │
                   ▼
              📁 PROJECT
                   │
                   ▼
               📋 TASKS
                   │
                   ▼
              👥 COLLABORATE
                   │
                   ▼
              📊 TRACK
                   │
                   ▼
              📈 ANALYZE
                   │
                   ▼
              🚀 DELIVER
```

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 **OTP Authentication** | Secure user authentication through Supabase |
| 📁 **Project Management** | Create and organize project workspaces |
| 📋 **Kanban Board** | Manage tasks through visual workflow boards |
| 📅 **Calendar Scheduling** | Organize deadlines and project events |
| 👥 **Team Collaboration** | Manage team members and project participation |
| 📊 **Analytics Dashboard** | Visualize project and task performance |
| 📈 **Live Statistics** | Monitor project progress and productivity metrics |
| 🔔 **Notifications** | Stay informed about project activities |
| 🔍 **Smart Search** | Quickly discover relevant project information |
| 📄 **Report Export** | Generate PDF and Excel reports |
| 🌙 **Dark / Light Theme** | Personalized workspace experience |
| 📱 **Responsive UI** | Designed for different screen sizes |
| ⚡ **Modern UX** | Smooth and organized project navigation |

---

## 🧩 Core Modules

### 🔐 Authentication

Secure access and account management through:

- OTP Authentication
- User Login
- Account Access
- Protected Application Areas

---

### 📊 Dashboard

The centralized dashboard provides a high-level overview of workspace activity.

**Dashboard Insights**

- Project statistics
- Task progress
- Activity overview
- Productivity metrics
- Project status

---

### 📁 Project Management

Create and manage projects from a centralized workspace.

```text
📁 Project
   │
   ├── 🎯 Project Details
   ├── 📋 Tasks
   ├── 👥 Team
   ├── 📅 Schedule
   └── 📊 Analytics
```

---

### 📋 Kanban Task Board

Visualize project workflows through a Kanban-style board.

```text
┌──────────────┐
│   TODO       │
│              │
│ 📋 Task 01   │
│ 📋 Task 02   │
└──────────────┘

┌──────────────┐
│ IN PROGRESS  │
│              │
│ ⚙️ Task 03   │
└──────────────┘

┌──────────────┐
│  COMPLETED   │
│              │
│ ✅ Task 04   │
└──────────────┘
```

This provides a simple visual representation of project progress.

---

### 📅 Calendar

The calendar module helps teams organize project schedules and deadlines.

**Scheduling Capabilities**

- Project dates
- Task deadlines
- Calendar events
- Timeline visibility
- Schedule organization

---

### 👥 Team Collaboration

Manage project participants through a dedicated team workspace.

**Team Features**

- Team member overview
- Project participation
- Collaboration workspace
- Team-focused project management

---

### 📊 Analytics

Transform project activity into meaningful visual insights.

**Analytics Includes**

- Project statistics
- Task distribution
- Progress tracking
- Performance indicators
- Visual charts

---

## 🏗️ System Architecture

```text
                    👤 USER
                      │
                      ▼
             ┌──────────────────┐
             │  React Frontend  │
             └────────┬─────────┘
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
      📁 Projects   📋 Tasks   👥 Teams
          │           │           │
          └───────────┼───────────┘
                      ▼
             ┌──────────────────┐
             │ Application Logic│
             │ Hooks / Context  │
             │ Services / APIs  │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │     Supabase     │
             ├──────────────────┤
             │ Authentication   │
             │ PostgreSQL       │
             │ Cloud Services   │
             └────────┬─────────┘
                      │
                      ▼
              📊 Analytics & Data
```

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| ⚛️ Frontend | React |
| 🔷 Language | TypeScript |
| 🎨 Styling | Tailwind CSS |
| ☁️ Backend | Supabase |
| 🗄️ Database | PostgreSQL |
| 🔐 Authentication | Supabase OTP Auth |
| 📊 Charts | Recharts |
| 🧠 State Management | React Context API |
| ⚡ Build / Development | Vite |
| 🚀 Deployment | Netlify / Vercel |
| 🔧 Version Control | Git & GitHub |

---

## 📸 Application Showcase

### 🏠 Landing Page

<div align="center">

<img width="1892" height="1026" alt="TaskFlow Pro Landing Page" src="https://github.com/user-attachments/assets/61148a4d-d3e5-4c66-a226-3d3f81247974" />

<br>

<strong>A polished landing experience introducing the TaskFlow Pro workspace.</strong>

</div>

---

### 🔐 Authentication

<div align="center">

<img width="1303" height="898" alt="TaskFlow Pro Authentication" src="https://github.com/user-attachments/assets/6d426104-b70f-43d6-830f-af66008190d7" />

<br>

<strong>Secure authentication experience for accessing the project workspace.</strong>

</div>

---

### 📊 Dashboard

<div align="center">

<img width="1316" height="902" alt="TaskFlow Pro Dashboard" src="https://github.com/user-attachments/assets/54cd99d8-e300-462c-8c23-49712b9b611b" />

<br>

<strong>Centralized dashboard for monitoring projects, tasks, and productivity.</strong>

</div>

---

### 📁 Project Workspace

<div align="center">

<img width="1918" height="981" alt="TaskFlow Pro Project Workspace" src="https://github.com/user-attachments/assets/6a95fde2-daca-435d-b0d8-25e2edaa8c64" />

<br>

<strong>Organize project information and manage work from a dedicated workspace.</strong>

</div>

---

### 📋 Kanban Board

<div align="center">

<img width="1917" height="1006" alt="TaskFlow Pro Kanban Board" src="https://github.com/user-attachments/assets/584b4d91-be25-45b5-b903-3d29f8f95186" />

<br>

<strong>Visual task management using a clean Kanban workflow.</strong>

</div>

---

### 📅 Calendar

<div align="center">

<img width="1918" height="1002" alt="TaskFlow Pro Calendar" src="https://github.com/user-attachments/assets/899d8cd3-2712-47da-b127-878b962852e6" />

<br>

<strong>Plan deadlines, events, and project schedules through the calendar workspace.</strong>

</div>

---

### 👥 Team Management

<div align="center">

<img width="1918" height="1002" alt="TaskFlow Pro Team Management" src="https://github.com/user-attachments/assets/48adee61-ce21-4a9f-9e3c-b3d3446a1d1a" />

<br>

<strong>Manage team participation and collaboration within projects.</strong>

</div>

---

### 📊 Analytics Dashboard

<div align="center">

<img width="1877" height="1021" alt="TaskFlow Pro Analytics" src="https://github.com/user-attachments/assets/49ea1910-d53f-4118-a955-bd0e2bb2d20a" />

<br>

<strong>Visual analytics for understanding project and task performance.</strong>

</div>

---

## 🔄 Application Workflow

```text
             🔐 Authentication
                    │
                    ▼
              📊 Dashboard
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
     📁 Project  📅 Calendar  👥 Team
          │
          ▼
       📋 Kanban
          │
          ▼
      📈 Analytics
          │
          ▼
       📄 Reports
          │
          ▼
        🚀 Delivery
```

---

## 📂 Project Structure

```text
TaskFlowPro/
│
├── 📁 public/
│   ├── favicon.ico
│   ├── logo.svg
│   └── assets/
│
├── 📁 src/
│   │
│   ├── 📁 assets/
│   │   ├── images/
│   │   ├── icons/
│   │   └── styles/
│   │
│   ├── 📁 components/
│   │   ├── common/
│   │   ├── dashboard/
│   │   ├── projects/
│   │   ├── kanban/
│   │   ├── analytics/
│   │   ├── calendar/
│   │   ├── team/
│   │   ├── authentication/
│   │   └── layout/
│   │
│   ├── 📁 pages/
│   │   ├── Landing/
│   │   ├── Login/
│   │   ├── Dashboard/
│   │   ├── Projects/
│   │   ├── Board/
│   │   ├── Calendar/
│   │   ├── Team/
│   │   ├── Analytics/
│   │   └── Profile/
│   │
│   ├── 📁 hooks/
│   ├── 📁 context/
│   ├── 📁 services/
│   ├── 📁 api/
│   ├── 📁 utils/
│   ├── 📁 routes/
│   ├── 📁 types/
│   ├── 📁 config/
│   │
│   ├── App.tsx
│   └── main.tsx
│
├── 📁 supabase/
├── 📁 screenshots/
├── 📁 docs/
│
├── .env.example
├── .gitignore
├── package.json
├── tsconfig.json
├── README.md
└── LICENSE
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Lalithkrish06/TaskFlowPro.git
```

### 2️⃣ Navigate to the Project

```bash
cd TaskFlowPro
```

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Configure Environment Variables

Create your environment file from the provided example:

```bash
cp .env.example .env
```

Then add your Supabase project credentials to `.env` before running the application.

### 5️⃣ Start Development Server

```bash
npm run dev
```

The application will be available through the local development URL provided by Vite.

---

## 🎯 Project Highlights

| Area | Highlights |
|---|---|
| 🏗️ Architecture | Production-inspired project structure |
| 🔐 Authentication | OTP-based authentication |
| 📁 Projects | Centralized project management |
| 📋 Tasks | Kanban workflow management |
| 📅 Scheduling | Calendar-based planning |
| 👥 Collaboration | Team management |
| 📊 Analytics | Project performance visualization |
| 📄 Reports | PDF and Excel export |
| 🎨 UI/UX | Modern workspace interface |
| 📱 Responsive | Multi-screen experience |
| 🧩 Components | Reusable component architecture |
| ⚡ Performance | Modern React + Vite development |
| ☁️ Backend | Supabase integration |
| 🗄️ Database | PostgreSQL |

---

## 💡 Why This Project Matters

TaskFlow Pro demonstrates how multiple productivity features can be combined into a unified project management workspace.

The project brings together:

```text
React
   +
TypeScript
   +
Tailwind CSS
   +
Supabase
   +
PostgreSQL
   +
Kanban
   +
Analytics
   +
Calendar
   +
Team Collaboration
   ↓
Modern Project Management Platform
```

This makes TaskFlow Pro a practical demonstration of **frontend engineering, backend integration, database-driven applications, authentication, visualization, responsive UI design, and scalable application architecture**.

---

## 🧠 Skills Demonstrated

- ⚛️ React Development
- 🔷 TypeScript
- 🎨 Tailwind CSS
- ☁️ Supabase Integration
- 🗄️ PostgreSQL
- 🔐 Authentication
- 📊 Data Visualization
- 📋 Kanban Workflow Design
- 📅 Calendar Interface Development
- 👥 Team Collaboration Systems
- 🧩 Component-Based Architecture
- 🪝 React Context & Hooks
- 🔌 API / Service Integration
- 📱 Responsive Web Development
- 🚀 Deployment
- 🔧 Git & GitHub

---

## 📚 Learning Outcomes

Through TaskFlow Pro, the project demonstrates practical experience in:

- Building full-stack-inspired React applications
- Structuring scalable frontend architecture
- Integrating Supabase services
- Working with PostgreSQL-backed applications
- Implementing authentication workflows
- Creating Kanban-based task management
- Building analytics dashboards with charts
- Designing calendar-based scheduling interfaces
- Developing reusable React components
- Creating responsive productivity interfaces
- Organizing application services and data layers
- Preparing applications for production-style deployment

---

## 🚀 Future Roadmap

TaskFlow Pro can evolve into a more advanced collaborative productivity ecosystem.

### 💬 Collaboration

- Team Chat
- Real-Time Comments
- Activity Feed
- Mention & Discussion System

### 🤖 AI Productivity

- AI Task Assistant
- AI Task Prioritization
- Smart Project Insights
- Automated Task Suggestions
- Project Risk Detection

### 📅 Scheduling

- Google Calendar Sync
- Smart Scheduling
- Meeting Management
- Deadline Notifications

### 🔔 Communication

- Email Notifications
- Push Notifications
- Custom Alerts
- Task Reminder System

### 📎 Productivity

- File Attachments
- Time Tracking
- Task Dependencies
- Advanced Reporting

### 🌐 Platform Expansion

- Multi-Language Support
- Mobile Application
- Advanced Permissions
- Enterprise Workspaces
- Video Meeting Integration

---

## 🌍 Real-World Applications

TaskFlow Pro can be extended for:

- 🏢 Software Development Teams
- 🎓 Student Project Teams
- 🚀 Startups
- 📊 Business Operations
- 🧑‍💻 Freelance Teams
- 🏗️ Project Management Organizations
- 📚 Academic Project Management
- 🏢 Enterprise Workspaces
- 🔬 Research Teams

---

## 🔗 Project Links

<div align="center">

<a href="https://taskflow.lalithkrish.dev/">
  <img src="https://img.shields.io/badge/Live-Platform-00C853?style=for-the-badge" alt="Live Platform">
</a>
<a href="https://github.com/Lalithkrish06/TaskFlowPro">
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository">
</a>
<a href="https://www.linkedin.com/posts/lalithkrish-data_reactjs-nodejs-mongodb-ugcPost-7478385414290972672-Ex4G/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFOj_WYBncOFydeAPBILXlA2BQoiO9StjuA">
  <img src="https://img.shields.io/badge/Project_Demo-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Project Demo">
</a>

</div>

---

## 🐛 Issues & Suggestions

Have you found a bug, encountered an issue, or have an idea to improve **TaskFlow Pro**?

Your feedback is welcome! 🚀

<div align="center">

### 💬 Contribute • Report • Improve

<a href="https://github.com/Lalithkrish06/TaskFlowPro/issues">
  <img src="https://img.shields.io/badge/Report-an_Issue-EA4335?style=for-the-badge" alt="Report Issue">
</a>
<a href="https://github.com/Lalithkrish06/TaskFlowPro">
  <img src="https://img.shields.io/badge/Star-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Star Repository">
</a>

<br><br>

**Have an idea? → Open an issue and help make TaskFlow Pro better! 🚀**

</div>

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Developer

<div align="center">

### 🚀 Lalith Krish

**AI & Data Science Engineer**

*Building intelligent systems • AI applications • Modern web platforms • Data-driven solutions*

<br>

<a href="mailto:lalithkrish2006@gmail.com">
  <img src="https://img.shields.io/badge/Email-lalithkrish2006%40gmail.com-EA4335?style=for-the-badge" alt="Email">
</a>
<a href="https://www.linkedin.com/in/lalithkrish-data/">
  <img src="https://img.shields.io/badge/LinkedIn-Lalith_Krish-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/Lalithkrish06">
  <img src="https://img.shields.io/badge/GitHub-Lalithkrish06-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="https://lalithkrish.dev/">
  <img src="https://img.shields.io/badge/Portfolio-lalithkrish.dev-000000?style=for-the-badge" alt="Portfolio">
</a>

</div>

---

<div align="center">

### 🚀 TaskFlow Pro

**Plan smarter. Collaborate better. Deliver faster.**

<br>

⭐ **If you found this project useful, consider giving the repository a star!**

</div>
