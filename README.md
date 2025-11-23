# 🚀 AI Saas Platform

**QuickAI** is an all-in-one AI-powered content creation platform designed for creators, marketers, and professionals. It offers powerful tools to generate articles, design and edit images, and review resumes—all in one seamless experience.

---

## ✨ Features

- **📝 AI Article Writer**  
  Generate high-quality, human-like articles on any topic within seconds.

- **🏷️ Blog Title Generator**  
  Instantly suggest catchy, SEO-friendly blog titles to boost your content's visibility.

- **🎨 AI Image Generator**  
  Create visuals in styles like Anime, 3D, and more using AI prompts.

- **🧽 Background/Object Removal**  
  Edit images effortlessly—remove backgrounds or unwanted elements with a single click.

- **📄 Resume Reviewer**  
  Get instant, AI-powered feedback to improve the structure and quality of your resume.

---

## 🛠️ Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| Frontend     | React.js             |
| Backend      | Node.js, Express.js  |
| Database     | MongoDB              |
| Authentication | Clerk              |
| AI Services  | LLM APIs (e.g., OpenAI), Image Processing APIs |


## 📦 Installation

git clone <repo-url>

cd server

npm install

# ⚙️ Environment Variables

Create .env:

PORT=5000

# Clerk

CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

# Neon

DATABASE_URL=

# Cloudinary

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

# OpenAI

OPENAI_API_KEY=

▶️ Running the Server

Development:

npm run dev

Runs at:

http://localhost:5000


## Frontend

cd client

npm install
# ⚙️ Environment Variables

Create .env in the root:

VITE_CLERK_PUBLISHABLE_KEY=

VITE_API_URL=http://localhost:5000
# ▶️ Development

npm run dev

App runs at:

http://localhost:5173


## Screenshots

