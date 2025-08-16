# 🧠 LeetCode Frontend with Judge0 Integration

A frontend web app that replicates the LeetCode problem-solving experience, enhanced with live code execution using the [Judge0 API](https://judge0.com/). This project supports real-time code compilation, problem filtering, and a responsive UI optimized for coding.

---

## 🚀 Features

- 🧑‍💻 Built-in code editor (Monaco)
- 🛠️ Real-time code execution via **Judge0**
- 📚 LeetCode-style problems with test cases
- 🎯 Difficulty filter and search
- 🌙 Dark/Light mode toggle
- ⚡ Fast, responsive, and mobile-friendly UI

---


## 🛠️ Tech Stack

- **React.js** – Frontend framework
- **TypeScript** – Type-safe development
- **Tailwind CSS** – Utility-first styling
- **Monaco Editor** – Embedded code editor
- **Axios** – API requests to Judge0
- **React Router** – Routing

---


## 🔗 Judge0 Setup

This project uses [Judge0 API (RapidAPI or self-hosted)] for compiling and running code.

### 🧾 Required Setup

1. Get your Judge0 API key (via [RapidAPI](https://rapidapi.com/judge0-official/api/judge0-ce/))  
2. Add the following to your `.env` file:


```env
VITE_JUDGE0_API_URL=https://judge0-ce.p.rapidapi.com
VITE_JUDGE0_API_KEY=your_rapidapi_key
