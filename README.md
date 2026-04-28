# TraceIt — Sports Content Piracy Detection Platform

## 🚀 Live Demo
https://traceit-protect-your-content-create-and-test.vercel.app/

---

## 🔗 Repositories
### Frontend  
https://github.com/mohitttt06/imaginecup-traceit-frontend  

### Backend  
https://github.com/mohitttt06/imaginecup-traceit-backend  

---

## 📌 Overview
TraceIt is an AI-powered platform that detects unauthorized usage of sports media across Reddit.  

It uses perceptual hashing (pHash) to identify visually similar images — even if they are resized, cropped, or slightly modified.

---

## ⚙️ Tech Stack
- **Frontend:** Next.js (TypeScript), Tailwind CSS  
- **Backend:** Python Flask (REST API)  
- **Database:** Supabase (PostgreSQL)  
- **Storage:** Supabase Storage  
- **Image Processing:** Pillow + ImageHash (pHash)  
- **Deployment:** Vercel (Frontend), Render (Backend)  

---

## 🧠 How It Works
1. User uploads original content  
2. System generates a perceptual hash (pHash)  
3. Backend scans Reddit posts (multiple subreddits)  
4. Extracts and hashes images from posts  
5. Compares hashes using Hamming distance  
6. Flags matches and displays results in dashboard  

---

## 🔍 Key Features
- Detects near-duplicate images (not just exact matches)  
- Automated Reddit scanning (no API key required)  
- Match scoring using similarity thresholds  
- Flagged content dashboard with source links  
- Real-time detection workflow  

---

## 🎯 Impact
TraceIt reduces content piracy detection time from hours to seconds, helping sports organizations and creators protect their digital assets at scale.

---
