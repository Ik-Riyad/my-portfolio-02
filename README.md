# 🚀 Ibrahim Khan Riyadh - Professional Portfolio

> A modern, fully-responsive portfolio showcasing Full-Stack development skills with a clean, cyberpunk-inspired design.

## ✨ Overview

This portfolio highlights professional experience, technical skills, and innovative projects in full-stack web development. Built with modern web technologies, it features a responsive design and interactive UI components.

## 🎯 Key Features

### 🏗️ **Modular Architecture**
- 11 major components with clear folder structure  
- 45+ reusable sub-components  
- Clean separation of concerns for maintainability  
- Server-side rendering for SEO and performance  

### 🎨 **Design & UX**
- Cyberpunk-inspired aesthetic with neon gradients  
- Fully responsive across all devices  
- Smooth animations and hover effects  
- Dark theme with professional color palette  

### ⚡ **Performance & SEO**
- Static Site Generation (SSG) for fast loading  
- Server Components reduce JS bundle size  
- Optimized meta tags and structured data for SEO  
- Progressive enhancement works even without JavaScript  

### 📧 **Interactive Features**
- Functional contact form with Resend email integration  
- Smooth scroll navigation with active section highlighting  
- Mobile-first responsive layouts  
- Toast notifications for user feedback  

## 🛠️ Tech Stack

### **Core Technologies**
- **Next.js 15** (App Router & Server Components)  
- **React 18**  
- **TypeScript**  
- **Tailwind CSS**  

### **UI & Components**
- **Shadcn UI**  
- **Lucide React**  
- **Radix UI**  
- **React Hook Form**  

### **Data & State Management**
- **TanStack Query**  
- **Zod**  
- **React Context**  

### **Backend Integration**
- Next.js Server Actions (server-side form handling)  
- **Resend** (email service)  
- JSON-based content management  

## 📁 Project Structure

src/
├── app/ # Next.js App Router
│ ├── layout.tsx # Root layout
│ ├── page.tsx # Homepage
│ ├── not-found.tsx # Custom 404 page
│ └── error.tsx # Error boundary
├── components/ # Modular components
├── data/ # JSON content files
├── lib/ # Utility functions and server actions
└── hooks/ # Custom React hooks


## 🚀 Getting Started

### Prerequisites
- **Node.js 18+**  
- **Yarn** or **npm**  

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd my-portfolio

2. Install dependencies:
yarn install
# or
npm install

3. Set up environment variables:
cp .env.example .env.local

Add your Resend API key for the contact form:
RESEND_API_KEY=your_api_key_here
CONTACT_EMAIL=your_email@example.com

yarn dev
# or
npm run dev

5. Open in browser: http://localhost:3000

📧 Contact Form

.Uses Resend
 for email sending

.Add your API key and email to .env.local to enable submissions


You can **copy all of this directly** into your README.md file.  

If you want, I can also **add a “Projects & Experience” section** at the bottom to showcase your actual work like Blood Donation System, Historical Artifacts Tracker, etc., which will make your portfolio stronger.  

Do you want me to add that?

