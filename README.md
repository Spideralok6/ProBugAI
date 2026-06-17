# 🤖 ProBugAI v3.2 - Ultimate Resilience Edition

ProBugAI v3.2 is a high-performance, resilient dashboard built for bug bounty hunters and cybersecurity researchers. It streamlines the vulnerability reporting process by combining local template generation with smart, failover-ready Google Gemini AI integration.

## 🚀 Key Features

*   **Smart Routing Engine:** Automatically detects API status and implements sequential fallback models if the primary model is busy (503 error handling).
*   **Dual-Mode Operation:** 
    *   **Local Mode:** Perfect for offline reporting with built-in templates.
    *   **AI Mode:** Activates the "Gemini AI Live Engine" when an API key is provided for deep-dive analysis.
*   **Production-Ready Reports:** Converts raw findings into structured, professional, and high-priority Markdown vulnerability reports.
*   **Real-Time Logging:** Integrated terminal-style console for monitoring background routing processes.

## 🛠 How to Use

1.  **Access:** Open the `probugai_v3_2_dashboard.html` file in any modern web browser.
2.  **Configure:** (Optional) Enter your Google Gemini API Key in the settings box to unlock advanced AI reporting.
3.  **Input:** Enter the vulnerability details (Bug Name, Target URL, Severity, Payload, and Steps).
4.  **Generate:** Click the **"Generate Report"** button to compile your findings.
5.  **Export:** Copy the output to your clipboard or download the report as a `.md` file.

## 🛡️ Resilience Configuration
This "Resilience Edition" is built with high-demand environments in mind. If Google AI Studio encounters regional spikes or rate limits, the system automatically cycles through backup models (`gemini-2.5-flash`, `gemini-2.5-pro`, `gemini-1.5-pro`, `gemini-1.5-flash`) to ensure your report generation is never interrupted.

---

## 📝 License
This project is open-source and intended for ethical security research and bug bounty reporting purposes.

---
*Created for efficient, professional security triaging.*
