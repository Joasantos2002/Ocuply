# 🚀 Ocuply

> **All-in-one AI platform to optimize your resume, track applications, and land your dream job. Master your career journey with Ocuply.**

[![GitHub License](https://img.shields.io/github/license/Joasantos2002/Ocuply?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/Joasantos2002/Ocuply?style=flat-square)]()
[![Node Version](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen?style=flat-square)]()

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

Occuply is a comprehensive AI-powered platform designed to help job seekers optimize their career journey. From resume optimization with AI suggestions to tracking job applications and managing job search workflows, Ocuply provides all the tools needed to land your dream job efficiently.

## ✨ Features

- 📄 **AI-Powered Resume Optimization**: Get intelligent suggestions to improve your resume
- 📊 **Application Tracker**: Manage and track all your job applications in one place
- 🤖 **AI Assistant**: Get personalized career advice and job recommendations
- 📈 **Analytics Dashboard**: Monitor your job search progress with detailed insights
- 💼 **Job Recommendations**: Discover jobs matching your profile using AI
- 🔔 **Application Notifications**: Stay updated on application status changes
- 🎨 **Professional Templates**: Pre-built resume and cover letter templates

## 🛠️ Tech Stack

**Frontend:**
- React.js / Next.js
- TypeScript
- Tailwind CSS
- Shadcn/ui

**Backend:**
- Node.js / Express
- Python (for AI/ML features)
- PostgreSQL / MongoDB

**AI/ML:**
- OpenAI API / Google Gemini
- NLP for resume analysis
- Machine Learning for recommendations

**DevOps:**
- Docker
- GitHub Actions (CI/CD)
- Cloud Deployment (Vercel/Render)

## 📦 Installation

### Prerequisites

- Node.js >= 18.0.0
- npm or yarn
- Git

### Clone Repository

```bash
git clone https://github.com/Joasantos2002/Ocuply.git
cd Ocuply
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Environment Variables

Create `.env.local` file in the root directory:

```env
# Frontend
REACT_APP_API_URL=http://localhost:3001
REACT_APP_OPENAI_KEY=your_openai_api_key

# Backend
DATABASE_URL=postgresql://user:password@localhost:5432/ocuply
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_jwt_secret
```

## 🚀 Usage

1. **Start the application:**
   ```bash
   npm run dev
   ```

2. **Access the application:**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:3001`

3. **Create account** and start optimizing your resume

## 📁 Project Structure

```
Ocuply/
├── frontend/                 # React/Next.js frontend
│   ├── public/
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Next.js pages
│   │   ├── hooks/           # Custom hooks
│   │   ├── lib/             # Utilities and helpers
│   │   └── styles/          # Global styles
│   └── package.json
├── backend/                  # Express server
│   ├── src/
│   │   ├── routes/          # API routes
│   │   ├── controllers/      # Business logic
│   │   ├── models/          # Database models
│   │   ├── middleware/      # Custom middleware
│   │   └── utils/           # Helper functions
│   └── package.json
├── docs/                     # Documentation
├── .gitignore
├── LICENSE                   # MIT License
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: Joasantos2002
- **Email**: [Your email]
- **LinkedIn**: [Your LinkedIn]
- **GitHub**: [@Joasantos2002](https://github.com/Joasantos2002)

---

**Made with ❤️ by [Joasantos2002](https://github.com/Joasantos2002)**
