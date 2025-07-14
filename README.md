# MERN Stack Deployment & DevOps Assignment

## 🌐 Live Demo

- **Frontend:** [https://your-frontend-url.vercel.app](https://your-frontend-url.vercel.app)
- **Backend API:** [https://your-backend-url.onrender.com](https://your-backend-url.onrender.com)

## 🚀 Project Overview

This project demonstrates a production-ready MERN stack application, deployed with CI/CD pipelines and cloud services.

## 🛠️ Tech Stack

- **Frontend:** React (Vite), Tailwind CSS, Vercel
- **Backend:** Node.js, Express, MongoDB Atlas, Render
- **CI/CD:** GitHub Actions

## ⚙️ CI/CD Pipeline

- Automated with GitHub Actions:  
  - Lints, tests, and builds both client and server
  - Deploys backend to Render and frontend to Vercel
  - Runs health checks after deployment

**Example pipeline screenshot:**  
![CI/CD Pipeline](./path-to-your-screenshot.png)

## 📦 Deployment Instructions

1. **Backend:**  
   - Deployed to Render from the `server` directory
   - Environment variables set in Render dashboard

2. **Frontend:**  
   - Deployed to Vercel from the `client` directory
   - Environment variable `VITE_API_URL` set to backend URL

## 🔑 Environment Variables

See [`env.example`](./env.example) for all required variables.  
**Important:** Never commit your real `.env` file!

## 🖥️ Running Locally

```bash
npm install
cd server && npm install
cd ../client && npm install
npm dev
```
- The app will run with the backend on [http://localhost:5000](http://localhost:5000) and frontend on [http://localhost:5173](http://localhost:5173) (Vite default).

## 📊 Monitoring

- (Describe any monitoring tools you set up, e.g., health check endpoints, Sentry, etc.)

## 📸 Screenshots

- Add screenshots of your deployed app and CI/CD pipeline here.

---

## 📚 Resources

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Render](https://render.com/)
- [Vercel](https://vercel.com/)
- [GitHub Actions](https://docs.github.com/en/actions) 