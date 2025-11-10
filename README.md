# 🎨 Artiflex – AI Image Generator & Editor  
AI-powered image creation & editing app built with Next.js, Shadcn UI, and Google Gemini 2.0 Flash.

Artiflex lets users **generate images from text prompts**, **edit existing images using natural language**, and **iteratively refine results with conversation context** — all in a clean, modern UI.

---

## 🚀 Features

✅ Text-to-Image Generation – Create high-quality images using Gemini 2.0 Flash  
✅ AI-Powered Image Editing – Modify uploaded images with natural language instructions  
✅ Conversation Memory – Refine outputs step-by-step using context awareness  
✅ Download Results – Save generated or edited images  
✅ Modern UI – Built with Next.js + Tailwind + Shadcn  
✅ API-First Structure – Can be reused in other apps  
✅ 100% Free to Run – Uses Google AI Studio free tier

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 15, TypeScript, Tailwind, Shadcn UI |
| AI Model | Google Gemini 2.0 Flash (Image + Text) |
| API | React Server Components, Edge functions |
| Deployment | Vercel |
| Extras | Drag & Drop, Base64 conversion, streaming responses |

---

## 📦 Project Structure

```text
artiflex/
├── app/ # Next.js app router
├── components/ # Reusable UI (shadcn)
├── lib/ # AI utilities + helpers
├── public/ # Static assets
├── styles/ # Tailwind config
└── README.md
```
🛠️ Local Development

1️⃣ Clone the repo
 
 ```sh
 git clone https://github.com/Code7x0/artiflex.git
 cd artiflex
 ```

 2️⃣ Install dependencies

 ```sh
 npm install
 ```
 3️⃣ Add environment variable
   
  Create ```.env.local```:
 ```sh
 GEMINI_API_KEY=your_google_ai_studio_key
 ```

 4️⃣ Run the dev server

 ```sh
 npm run dev
 ```
--- 

📘 How It Works (AI Flow)
User enters text → app sends request to Gemini

Gemini returns base64 image data

App converts & displays it instantly

User uploads image → asks “edit this by ___”

Gemini processes image + instruction → returns modified image

Conversation history maintains context for better refinement

---

🎯 Why I Built This
I wanted a lightweight alternative to MidJourney/Firefly that supports both generation + editing using natural language prompts. This project helped me learn real-world AI integration, image streaming, UI state management, and deployment workflows.

-- Useful for:

-- Portfolio / Resume

-- Internship showcase

-- AI + Web Dev upskilling

-- Hackathons & demos

---
📝 License
MIT License — free to use and modify.
