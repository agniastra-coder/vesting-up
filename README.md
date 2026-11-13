# 📈 Vesting UP

**A gamified stock market education and paper-trading platform designed to take beginners from zero to confident market participants.**

🔗 **Live Demo:** [frontend-blue-tau-60.vercel.app](https://frontend-blue-tau-60.vercel.app)

---

### 🎯 The Problem
Most retail beginners enter the stock market without understanding risk management, market mechanics, or fundamental valuation—leading to avoidable losses. Existing learning platforms are either overly dry textbooks or unstructured video playlists with zero hands-on practice.

### 💡 The Solution
**Vesting UP** combines structured, bite-sized financial education with risk-free simulated trading:
* **8-Level Progressive Curriculum:** Structured modules covering market basics, order types, risk management, candlestick patterns, and portfolio diversification.
* **Simulated Trading Quests (UPBucks):** Virtual currency sandbox allowing users to execute simulated trades and complete scenario-based challenges without financial risk.
* **Atlas (AI Mentor):** Context-aware AI assistant that answers finance questions, explains market terminology in plain language, and guides users through quests.
* **Gamified Progression:** XP, level unlocks, and interactive checkpoints to sustain user retention.

---

### 🛠️ Tech Stack
* **Frontend:** React / Next.js, Tailwind CSS, JavaScript (ES6+)
* **Backend & Auth:** Node.js / Express 
* **AI Integration:** LLM API powering the *Atlas* mentor workflow
* **Deployment:** Vercel

---

### ⚙️ Architecture & Key Engineering Highlights
* **Modular State & Progression Engine:** Tracks user XP, level completion gates, and virtual portfolio balances (`UPBucks`) across sessions.
* **Real-Time Trade Execution Logic:** Calculates virtual buy/sell positions, average cost basis, and unrealized P&L dynamically.
* **Responsive UI/UX:** Built mobile-first for seamless usage across desktop and mobile browsers.

---

### 🚀 Running Locally

1. **Clone the repository**
 git clone https://github.com/agniastra-coder/vesting-up.git
