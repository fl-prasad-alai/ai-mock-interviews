<div align="center">
  <br />
    <img src="https://github.com/user-attachments/assets/1c0131c7-9f2d-4e3b-b47c-9679e76d8f9a" alt="Project Banner">
  <br />
  
  <div>
    <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="next.js" />
    <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="vapi" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="firebase" />
  </div>

  <h3 align="center">Prepwise: A job interview preparation platform powered by AI Voice agents</h3>
</div>

---

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Code Snippets](#code-snippets)
6. 🔗 [Assets](#assets)
7. 🚀 [More](#more)

---

## 🤖 Introduction

Prepwise is a platform designed to help users practice and prepare for job interviews using AI-powered voice agents. The project is built with **Next.js** for frontend and backend logic, **Firebase** for authentication and data storage, and **TailwindCSS** for styling. AI voice agents guide interviews and provide instant feedback to users.  

The interface is modern, responsive, and focused on a smooth user experience for interview practice.  

---

## ⚙️ Tech Stack

- Next.js  
- Firebase  
- Tailwind CSS  
- Vapi AI  
- shadcn/ui  
- Google Gemini  
- Zod  

---

## 🔋 Features

- **Authentication**: Sign up and sign in with email/password handled by Firebase.  
- **Create Interviews**: Generate job interviews with AI voice agents.  
- **AI Feedback**: Receive structured feedback on interviews from AI.  
- **Interview Page**: Conduct AI-driven interviews in real-time.  
- **Dashboard**: Track and manage all your interviews.  
- **Responsive Design**: Works well on both desktop and mobile devices.  

---

## 🤸 Quick Start

### Prerequisites

Make sure the following are installed on your machine:

- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/en/)  
- [npm](https://www.npmjs.com/)  

---

### Clone the Repository

```bash
git clone git@github.com:fl-prasad-alai/ai-mock-interviews.git
cd ai-mock-interviews

### Install Dependencies
```bash
npm install

### Set Up Environment Variables
Create a .env.local file in the project root with the following:

```bash
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=

### Run the Project 
```bash
npm run dev
Open http://localhost:3000 in your browser.
