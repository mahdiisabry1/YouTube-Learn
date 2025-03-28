YouTube-Learn 🎥➗🧠
Next.js YouTube Clone with AI-Powered Learning Content

Project Screenshot

A modern educational YouTube clone built with Next.js, featuring AI-generated learning content, smart recommendations, and creator tools.

Key Features ✨
Next.js 14 App Router for optimized performance

AI Lesson Generator: Create educational videos from text prompts

Smart Chapters: AI-generated video segments and summaries

Interactive Transcripts: Searchable, clickable transcripts with translations

Personalized Learning Paths: AI-curated content recommendations

Virtual Tutor: AI avatar for explanations (using ElevenLabs/Deepgram)

Automated Quizzes: AI-generated knowledge checks from video content

Tech Stack 💻
Core Framework
Next.js 14 (App Router)

TypeScript

Tailwind CSS + Shadcn UI

Backend Services
Next.js API Routes

Prisma ORM

PostgreSQL (Vercel Storage)

Firebase Storage (for videos)

AI Integration
OpenAI GPT-4 (Content generation)

Whisper (Speech-to-text)

Stable Diffusion (Thumbnails/illustrations)

LangChain (for structured content creation)

Pinecone (Vector search for recommendations)

Getting Started 🏁
Prerequisites
Node.js 18+

Python 3.10+ (for AI services)

Vercel account (recommended for deployment)

OpenAI API key

Installation
Clone the repository:

bash
Copy
git clone https://github.com/mahdiisabry1/YouTube-Learn.git
cd YouTube-Learn
Install dependencies:

bash
Copy
npm install
Set up environment variables:

bash
Copy
cp .env.example .env.local
Fill in your credentials in .env.local

Run the development server:

bash
Copy
npm run dev
Project Structure (Next.js) 📂
Copy
YouTube-Learn/
├── app/
│   ├── (main)/               # Public routes
│   ├── (creator)/            # Creator dashboard routes
│   ├── api/                  # API routes
│   └── assets/               # Static assets
├── components/               # Reusable components
├── lib/                      # Utilities/helpers
├── prisma/                   # Database schema
├── styles/                   # Global styles
├── ai-services/              # Python microservices
└── public/                   # Static files
AI Workflows 🧠
Content Creation Process:
User submits topic/text prompt

AI generates:

Video script (GPT-4)

Voiceover (ElevenLabs)

Visual assets (Stable Diffusion)

Quiz questions (LangChain)

System assembles final video (FFmpeg)

Learning Recommendations:
Vector embeddings of video content

User behavior analysis

Knowledge gap identification