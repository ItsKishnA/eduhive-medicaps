# 🚀  EduHive

> Empowering education by connecting learners and educators through a dynamic online platform.

---

## 🎯 Objective

EduHive addresses the challenge of providing accessible, efficient, and engaging digital education.
It serves students, educators, and institutions by offering an all-in-one platform for course creation, enrollment, and management.
The real-world value: democratizing quality education with easy-to-use tools for teaching and learning.

---

### Team Members:  
- Avi Mahajan [@ItsKishnA](https://github.com/ItsKishnA)

### Your Approach:  
- We adopted a strategic design and implementation methodology focused on a user-centric approach, specifically tailoring   EduHive for students.
- Our core aim was to simplify the learning experience, enhance accessibility, and seamlessly integrate AI-driven capabilities like real-time interactions.
- Key aspects included iterative prototyping, active feedback integration, and balancing technical scalability with an intuitive user experience. 

---

## 🛠️ Tech Stack

### Core Technologies Used:
- Framework: Next.js (React-based Fullstack Framework)
- Styling: TailwindCSS
- Database: Supabase Postgres
- ORM: Prisma ORM
- Hosting: Vercel

## ✨ Key Features

Highlight the most important features of your project:

- ✅ Minimalistic and responsive UI with TailwindCSS and Lucide icons
- ✅ User authentication and secure access via NextAuth & Supabase 
- ✅ Access and learn from educational videos via links without uploading.  
- ✅ Enable students to create, edit, and organize notes linked to specific videos, making learning more engaging and structured. 

Add images, GIFs, or screenshots if helpful!

---

## 📽️ Demo & Deliverables

- Demo Video Link: [View Demo](https://youtu.be/euP7ss4KQlk)
- Pitch Deck / PPT Link: [View Pitch Deck](https://www.canva.com/design/DAGl1dRg2s4/ma6pbfygN6AThNtBWsL1DQ/edit)

---

## 🧪 How to Run the Project

### Requirements:
- Node.js 

### Local Setup:
```bash
# Clone the repo
git clone https://github.com/itzraghavv/eduhive

# Install dependencies
cd eduhive

# Setup Environment Varianbles
cp env.example .env

# Generate a NEXTAUTH_SECRET (only once)
openssl rand -base64 32

# Install Packages
npm install

# After installing dependencies
npx prisma generate

# (optional) If you need to apply migrations
npx prisma migrate dev

# Start development server
npm run dev
```

---

## 🧬 Future Scope

List improvements, extensions, or follow-up features:

- 🗣️ Chat and Collaboration: Enable real-time chat and collaborative note-taking among students.
- 🧠 Smarter AI Features: Personalize learning with AI-based suggestions and note summarization.
- 🖼️🎤 Advanced Media Handling: Allow image uploads and voice recordings for richer learning experiences.
- 🌐 Global Accessibility: Add multilingual support and offline access for global learners.
- 🛡️ Security Enhancements: Implement encrypted communication and secure file handling.
  
---

## 📎 Resources / Credits

- [Supabase](https://supabase.com/) for backend services
- [Tailwind CSS](https://tailwindcss.com/) for UI styling
- [Groq AI](https://groq.com/) for multimodal capabilities

---

## 🏁 Final Words

EduHive was a journey to reimagine digital learning.
From authentication to real-time uploads, every challenge led to meaningful learning.
Huge thanks to the open-source community and hackathon mentors for constant inspiration!

---
