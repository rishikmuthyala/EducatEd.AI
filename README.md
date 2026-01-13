# 🎓 FrameShift - Real-Time AI Tutoring Platform

> The first platform to generate personalized AI explanation videos in real-time when students pause on confusing concepts.

[![Demo](https://img.shields.io/badge/▶️_Watch_Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=3zOFGK7cXj8)
[![Status](https://img.shields.io/badge/Status-Beta_Live-00C853?style=for-the-badge)]()

---

## 🎬 See It In Action

[![Screenshot 2026-01-12 at 7 54 05 PM](https://github.com/user-attachments/assets/b487d746-ffb6-4bfd-8d15-f3a3819cfd9b)](https://www.youtube.com/watch?v=3zOFGK7cXj8)

**[→ Watch Full Demo Video](https://www.youtube.com/watch?v=3zOFGK7cXj8)**

---

## 💡 The Problem

**78% of students abandon online courses when they encounter one confusing concept.**

Current solutions fall short:
- **YouTube/Coursera**: Rewind 5+ times, still confused
- **ChatGPT**: Text-only, not visual or engaging
- **Q&A Forums**: Wait hours/days for response

**No platform generates personalized video explanations in real-time.**

---

## ✨ The Solution

**FrameShift detects when you're stuck and generates a custom 30-second explanation video—automatically.**

### How It Works
```
1. Watch → Play any educational video from your library

2. Pause → Get stuck? Pause for 3 seconds

3. AI Explains → 35-second custom video generates with:
   • Diagrams (DALL-E 3)
   • Narration (ElevenLabs) 
   • Tailored to YOUR confusion point

4. Resume → Return to video seamlessly

5. Organize → Videos auto-categorize by subject
```

**Never leave the video. Never lose context. Just learn.**

---

## 🚀 Key Features

### ⚡ Real-Time AI Video Generation
Generate personalized 30-second explanation videos in **35 seconds** from pause to playback
- **95% success rate** across 150+ educational videos
- **Multi-modal**: Diagrams + narration + composition

### 🎯 Intelligent Pause Detection
Automatically detects confusion when you pause for **3+ seconds**
- Analyzes video transcript for context
- Extracts the exact concept you're stuck on

### 📚 Auto-Organizing Library
Upload videos and AI categorizes them instantly
- **94% accuracy** using Claude API
- Organized by: Math, Physics, CS, Chemistry, Biology
- Personal dashboard tracks your learning

### 🎨 Seamless Overlay UX
Explanations appear as smooth overlays—main video always visible
- **<100ms UI transitions**
- Auto-resume or manual control
- Never navigate away from learning

---

## 🛠️ Tech Stack

**AI Pipeline** (5 Models Working Together):
- **Whisper** - Transcribe video context
- **Claude-3.5** - Extract confused concept
- **DALL-E 3** - Generate explanation diagrams
- **ElevenLabs** - Create narration
- **MoviePy** - Compose final video

**Backend**:
- FastAPI with async orchestration
- Redis caching for performance
- Event-driven architecture
- Handles 50+ concurrent requests

**Frontend**:
- Next.js 14 + React + TypeScript
- WebSocket for real-time updates
- TailwindCSS for styling

**Data**:
- PostgreSQL for metadata
- Cloud storage for videos

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| **Generation Time** | 35 seconds average |
| **Success Rate** | 95% across 150+ videos |
| **Latency Improvement** | 61% faster (optimized from 90s) |
| **Categorization Accuracy** | 94% with Claude API |
| **Concurrent Requests** | 50+ handled simultaneously |
| **UI Response** | <100ms transitions |
| **Beta Users** | 200+ active students |

---

## 🎯 Use Cases

**For Students**:
- Pause on hard concepts → instant visual explanation
- Build personal library of explained topics
- Review for exams with AI-generated content

**Future Vision**:
- **Chrome Extension**: Works on YouTube, Coursera, Khan Academy
- **Universities**: Analytics dashboard showing where students struggle
- **Enterprise**: Corporate training with AI tutoring

---

## 🚀 Roadmap

**✅ Completed (MVP)**
- Real-time AI video generation
- Pause detection system
- Auto-categorization
- Personal video library

**🚧 In Progress**
- Chrome extension for YouTube/Coursera
- Learning graph (track what you know)
- Preemptive explanations (before you get stuck)

**🔮 Future**
- LMS integration (Canvas, Blackboard)
- Mobile apps
- Professor analytics dashboard
- Enterprise solutions

---

## 📈 Market Opportunity

**$88 Billion Global EdTech Market**

**Our Position**:
- Replace Chegg ($20/mo) with better AI at $14.99/mo
- First real-time video explanation platform
- Clear path: Students → Universities → Enterprise

---

## 📄 License

**Proprietary** - Commercial product under development. Code not open source.

---

<div align="center">

### FrameShift - Making confusion optional in education

**Built with ❤️ and 5 AI models**

⭐ Star this repo if you're interested in AI-powered education

</div>

---

**Note:** This repository showcases the project. Source code is proprietary as EducatEd.AI is being developed as a commercial product.
