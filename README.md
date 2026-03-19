<p align="center">
  <img src="https://i.ibb.co/Zm8s0hG/craftconnect-banner.png" alt="CraftConnect Banner" width="800"/>
</p>

<h1 align="center">🎨 CraftConnect - AI-Powered Artisan Marketplace</h1>

<p align="center">
  <a href="https://github.com/sandeepbehera21/CraftConnect"><img src="https://img.shields.io/github/repo-size/sandeepbehera21/CraftConnect?color=blue" alt="Repo Size"></a>
  <a href="https://github.com/sandeepbehera21/CraftConnect/issues"><img src="https://img.shields.io/github/issues/sandeepbehera21/CraftConnect" alt="Issues"></a>
  <a href="https://github.com/sandeepbehera21/CraftConnect/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green" alt="License"></a>
  <a href="https://craftconnect-hackathon-2025.uc.r.appspot.com"><img src="https://img.shields.io/badge/Live%20Demo-Click%20Here-blueviolet" alt="Live Demo"></a>
</p>

---

## 🚀 Project Overview
**CraftConnect** connects traditional artisans with global customers using **AI-powered storytelling** and **cloud-native tools**.

- **AI Story Generator** – Transform crafts into engaging narratives.
- **Smart Dashboard** – Manage products, orders, and revenue.
- **Global Marketplace** – Showcase products worldwide.
- **Cultural Heritage Preservation** – Keep artisan traditions alive.
- **Social Sharing** – One-click sharing with UTM tracking.

---

## 🎨 Technology Stack

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini_API-FF9900?style=for-the-badge&logo=google&logoColor=white"/>
</p>

---

## 🎯 Core Features

| Artisans | Customers | Technical |
|----------|-----------|-----------|
| ✅ AI Product Story Generator | ✅ Global Product Discovery | ✅ Responsive Design |
| ✅ Smart Dashboard | ✅ Advanced Search & Filtering | ✅ Real-time Updates |
| ✅ AI Chatbot Assistant | ✅ Cultural Stories | ✅ Pagination & Performance |
| ✅ Social Media Integration | ✅ Secure Authentication | ✅ Error Handling & Security |
| ✅ Image Upload & Management | ✅ Shopping Cart | ✅ Optimized Loading |

---

## 🔄 Process Flow

```text
Artisan Onboarding: Register → Upload Product → AI Content Generation → Publish
Customer Journey: Discover → Browse → Learn Story → Purchase → Share
AI Content Generation: Image Upload → Gemini Analysis → Story Creation → Optimization
🏗️ Architecture Diagram
scss
Copy code
Frontend (React + Tailwind + Context API)
       │
       ▼
Backend (Node.js + Express + JWT + File Upload)
       │
       ▼
Database (MongoDB Atlas)
       │
       ▼
AI (Google Gemini API)
Benefits: Microservices, scalable, secure, auto-scaling, high availability.

💰 Cost & ROI (INR)
One-time Dev: ₹17.6L – ₹29.6L
Monthly Operations: ₹8.4k – ₹37.6k
Scaling (1000+ users): ₹32k – ₹96k

ROI:

Break-even: 6–12 months

Revenue per artisan: ₹4k – ₹16k/month

Commission: 5–10%

Projected annual revenue: ₹40L – ₹1.6Cr

🏆 Hackathon Compliance & Highlights
Compliance: ☁️ Cloud Integration | 🤖 AI (Gemini) | 🌐 Full-Stack | 💡 Innovation | 👩‍🎨 Social Impact | ⚡ Scalability

Social Impact: Artisan empowerment | Cultural preservation | Economic development | Global reach

Innovation: AI Story Generator | Smart Analytics | UTM Sharing | Mobile-first

Technical: Microservices | Real-time AI | Security best practices | Performance optimization

Future: Payment integration | Mobile app | Multi-language | Advanced analytics

## 🚀 Quick Start & Deployment

### Local Development
```bash
# Clone repository
git clone https://github.com/sandeepbehera21/CraftConnect.git
cd CraftConnect

# Setup Backend
cd backend
cp .env.example .env
# Edit .env with your credentials
npm install
npm run dev

# Setup Frontend (new terminal)
cd ..
npm install
npm run dev
```

### Production Deployment (Google Cloud)

**IMPORTANT: Story Generation Fix Applied!**

The story generation feature now works properly in production. Here's what was fixed:

1. **Environment Variables**: Added proper `app.yaml` configuration
2. **Health Check**: Added `/api/health` endpoint
3. **Error Handling**: Improved AI service error messages

```bash
# Deploy Backend
cd backend
# Update app.yaml with your environment variables
gcloud app deploy app.yaml

# Deploy Frontend
cd ..
npm run build
gcloud app deploy frontend-app.yaml
```

### Required Environment Variables

**Backend (.env)**:
- `GEMINI_API_KEY`: Get from [Google AI Studio](https://makersuite.google.com/app/apikey)
- `MONGO_URI`: MongoDB connection string
- `JWT_SECRET`: Secure random string
- `FRONTEND_ORIGIN`: Your frontend URL

**Frontend (.env)** (optional):
- `VITE_API_BASE_URL`: Backend URL (defaults handled in config.js)

### Testing Story Generation

After deployment:
1. Visit your deployed app
2. Register/Login as artisan
3. Go to Dashboard
4. Enter product name → Click "Generate Story"
5. Verify AI content appears

### Health Check
Visit: `https://your-backend-url/api/health` to verify Gemini API is configured.

---

## 📜 License
MIT License

<p align="center"> Made with ❤️ by Sandeep Behera for Hackathon 2025 
