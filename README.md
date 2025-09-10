# PM Internship Allocation System - Backend

## 📌 Overview
This is the **backend service** for the **Prime Minister’s Internship Allocation System**, developed for Smart India Hackathon (SIH).  
It provides **RESTful APIs** to handle student data, AI-based scoring integration, percentile & rank calculation, and multi-round seat allocation logic.  

Built with **Node.js + Express**, deployed on **Render** for scalability and security.

---

## 🚀 Features
- 🛡️ Secure authentication & authorization (JWT/OAuth2)  
- 📝 Manage student applications & profiles  
- 🤖 AI/ML Scoring Engine integration (JSON-based output)  
- 📊 Percentile & rank calculation  
- 🔄 Multi-round seat allocation with vacancy handling  
- 📑 APIs for frontend dashboards & admin reports  

---

## 🛠️ Tech Stack
- **Backend Framework:** Node.js, Express  
- **Database:** PostgreSQL / MySQL  
- **ORM (optional):** Sequelize / Prisma  
- **AI Service Integration:** FastAPI / Python microservice (score endpoint)  
- **Deployment:** Render  

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (>= 16.x)  
- PostgreSQL/MySQL database  
- npm or yarn  

### Steps
```bash
# Clone the repository
git clone https://github.com/<your-org>/pm-internship-backend.git

# Navigate into the project
cd pm-internship-backend

# Install dependencies
npm install

# Run development server
npm run dev
