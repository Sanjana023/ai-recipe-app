# 🍳 Serve — AI Powered Recipe Platform

Serve is a full-stack AI-powered recipe platform that helps users turn everyday pantry items into delicious, customized recipes using artificial intelligence.

---

## 🚀 Overview

Serve allows users to scan images of their pantry items using AI and instantly receive personalized recipe recommendations based on available ingredients, mood, and cuisine preferences. The platform also offers an intelligent AI chef that can search for any recipe in the world.

This project is designed as a **production-ready, scalable application** showcasing real-world AI integration, modern UI/UX, and secure backend architecture.

---

## ✨ Features

### 🤖 AI Pantry Scanner
- Scan or upload images of pantry items
- AI automatically detects ingredients
- Generates recipes based on available items

### 👨‍🍳 AI Chef Search
- "How To Cook" AI search button
- Search any recipe globally
- Smart recommendations based on mood and cuisine

### 📚 Recipe Library
- Browse recipes by:
  - Cuisine (global recipes)
  - Mood & preferences
- Digital cookbook-style explore screen

### 📄 Detailed Recipe Pages
Each recipe includes:
- Prep time & cook time
- Serving size
- Complete ingredient list
- Step-by-step cooking instructions
- Nutritional breakdown per serving
- Chef tips & tricks
- Smart ingredient substitutions

### 📥 Save & Export
- Export recipes as PDF for offline use (using react-pdf-renderer)
- Save recipes into personalized collections

---

## 💳 Pricing Plans

### 🆓 Free Plan ($0 / month)
- 10 pantry scans
- 5 AI meal recommendations
- Access to standard recipes

### ⭐ Pro Plan ($7.99 / month)
- Unlimited pantry scans
- Unlimited AI recipe generations
- Additional recipe insights
- Enhanced AI features

---

## 🛠 Tech Stack

### Frontend
- Next.js
- ShadCN UI
- Fully responsive modern UI

### Backend & Infrastructure
- Strapi (Headless CMS for recipe management)
- Neon (PostgreSQL database)
- Clerk (Authentication & user management)
- Arcjet (Bot protection & API rate limiting)
- AI services for:
  - Image recognition
  - Recipe generation
  - Ingredient substitution

---

## 🔐 Authentication & User Management

- Google OAuth login
- Secure user sessions
- Manage account details:
  - Username
  - Email addresses
  - Active login sessions
  - Billing & subscriptions

All user data is securely stored and synced with the database.

---

## 📦 Installation & Setup

```bash
git clone https://github.com/Sanjana023/ai-recipe-app.git
cd ai-recipe-app
cd frontend
npm run dev
cd ..
cd backend
npm run develop
```

## Environment Variables
Make sure to create .env file with appropriate keys such as:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY= 
CLERK_SECRET_KEY= 
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
ARCJET_KEY= 
NEXT_PUBLIC_STRAPI_URL= 
STRAPI_API_TOKEN= 
GEMINI_API_KEY= 
UNSPLASH_ACCESS_KEY= 
```
---


