# 🧠 FlashLearn AI – Personalized AI-Powered Learning Assistant

FlashLearn AI is an AI-powered tool that generates **personalized learning experiences** in just minutes. Whether you're coming home from a tough class or prepping for an exam, type what you want to learn (e.g. "Teach me basic Data Structures") and get a **10-minute crash course**, complete with flashcards, summaries, and conversations.

---

## 🚀 Features

- 🔥 **10-Minute Course Generator**: Automatically builds a full course on any topic you type, like "Chemistry basics" or "Learn Recursion".
- 💬 **Conversational AI Tutor**: Learn by chatting — ask questions, explore follow-ups, or even quiz yourself mid-lesson.
- 🗂 **Flashcards & Summaries**: Converts knowledge into flashcards, summaries, and article-style explanations.
- 🧩 **Multiple Output Formats**: Courses can be delivered as:
  - Chat conversations
  - Articles
  - Flashcards
  - Mini-quizzes
- 🎯 **Time-Aware Learning**: Only have 10 minutes? Get a micro-lesson. Got more? Extend the course duration.

---

## 🌍 Who This is For

- 📚 High school & uni students
- 🧑‍💻 Self-taught devs (e.g. learning DSA or systems design)
- 🔁 Lifelong learners who want **fast**, **personal**, and **interactive** content

---

## 🥊 Competition Landscape

| Product | Description | Weakness |
|--------|-------------|----------|
| **Khanmigo (Khan Academy)** | AI tutor with GPT-4 integration | Locked to their curriculum |
| **Socratic (Google)** | Visual answers for high school topics | No full-course generation |
| **Duolingo Max** | GPT-4 powered language tutor | Language-only |
| **Quizlet AI** | Flashcard generator | No learning path, no chat |
| **LeetCode / NeetCode** | Practice-focused DSA platforms | No AI tutor or course builder |
| **Notion AI / Poe / ChatGPT** | General-purpose LLM tools | Not tailored to learners |

---

## 🌟 How We're Different

- 💡 **Topic-to-Course** in minutes (chemistry, coding, history—you name it)
- ⏱ **Time-sensitive** learning (Tell the AI how long you want to study)
- 🎮 Interactive formats (chat, quizzes, cards—not just text)
- 🧠 Multimodal input (text, articles, slides, or even voice)
- 💬 Gen Z-friendly tutor experience (fun, meme-y, chill vibes)

---

## 📦 Stack (Planned)

- **Frontend**: Next.js + Tailwind
- **Backend**: FastAPI (or Node.js w/ Express)
- **LLM**: OpenAI GPT-4 / fine-tuned model (future)
- **Flashcard Generation**: Custom prompt templates
- **Quiz Generation**: Few-shot learning w/ example formatting
- **Optional Add-ons**:
  - User auth (Supabase or Firebase)
  - Storage (PostgreSQL or DynamoDB)
  - Real-time learning sessions (WebSockets or LiveKit)

---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/flashlearn-ai.git

# Install dependencies
cd flashlearn-ai
npm install

# Run dev server
npm run dev
