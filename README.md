# Easy Ride Planner

Welcome to the Easy Ride Planner project!

This repository hosts the landing page and user authentication system, where users can sign up, log in, and access the platform securely. Once authenticated, users are redirected to the main map and route planning interface (hosted in a separate repository (https://github.com/DarshiniSai/Easy-Ride-Planner), which offers route optimization, traffic analysis, turn by turn directions. In this project we used OSRM(Open Source Route Machine) which is a open source API for maps, but its not quite accurate though. Built with React, Vite, TailwindCSS, and Express, and powered by Clerk authentication, the platform combines a sleek user experience with a reliable backend for smooth and secure travel planning.
Think of it as the friendly front door — users land here, sign in, and then get redirected to the main ride planning interface.

# 🌍 Live Deployment
Deployed on Render: https://easyrideplanner.onrender.com/

# 📂 Project Structure
This repo contains:

Landing Page – First impression of the platform.

Authentication – Sign-up, login, and secure session handling.

🚦 Note: The actual map, routes, and ride planning features live in another repository.
You can find it here: Easy Ride Planner — Map & Routeshttps://github.com/DarshiniSai/Easy-Ride-Planner

# 🛠️ Tech Stack
Frontend: React, Vite, TailwindCSS, Radix UI

Backend: Express.js, Node.js

Auth: Clerk Authentication

Deployment: Render

# 🚀 Running Locally

Clone the repository
git clone https://github.com/DarshiniSai/EASY.git

Install dependencies
npm install

Start development mode
npm run dev


#📦 Deployment Notes
This repo is deployed as a full-stack service on Render.

If you deploy separately (frontend + backend), make sure to update API URLs in your frontend configuration.

