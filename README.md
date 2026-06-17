# 🤖 ProBugAI v3.2 - Ultimate Resilience Edition

ProBugAI v3.2 is a high-performance, resilient dashboard built for bug bounty hunters and cybersecurity researchers. It streamlines the vulnerability reporting process by combining local template generation with smart, failover-ready Google Gemini AI integration[cite: 1].

## 🚀 Key Features

*   **Smart Routing Engine:** Automatically detects API status and implements sequential fallback models if the primary model is busy (503 error handling)[cite: 1].
*   **Dual-Mode Operation:** 
    *   **Local Mode:** Perfect for offline reporting with built-in templates. No API key is required for this mode[cite: 1].
    *   **AI Mode:** Activates the "Gemini AI Live Engine" when an API key is provided for deep-dive analysis[cite: 1].
*   **Production-Ready Reports:** Converts raw findings into structured, professional, and high-priority Markdown vulnerability reports[cite: 1].
*   **Real-Time Logging:** Integrated terminal-style console for monitoring background routing processes[cite: 1].

## 🛠 How to Use

1.  **Access:** Open the `probugai_v3_2_dashboard.html` file in any modern web browser[cite: 1].
2.  **Configure (Optional):** Enter your Google Gemini API Key in the settings box to unlock advanced AI reporting. If you do not have a key, the tool automatically works in "Local Mode" using built-in templates[cite: 1].
3.  **Input:** Enter the vulnerability details (Bug Name, Target URL, Severity, Payload, and Steps)[cite: 1].
4.  **Generate:** Click the **"Generate Report"** button to compile your findings[cite: 1].
5.  **Export:** Copy the output to your clipboard or download the report as a `.md` file[cite: 1].

## 🛡️ Resilience Configuration
This "Resilience Edition" is built with high-demand environments in mind[cite: 1]. If Google AI Studio encounters regional spikes or rate limits, the system automatically cycles through backup models (`gemini-2.5-flash`, `gemini-2.5-pro`, `gemini-1.5-pro`, `gemini-1.5-flash`) to ensure your report generation is never interrupted[cite: 1].

---

## 📝 License
This project is open-source and intended for ethical security research and bug bounty reporting purposes[cite: 1].

---
*Created for efficient, professional security triaging.*
