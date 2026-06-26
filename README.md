# ⚡ DecodeLabs Task 03: Interactive Web Elements

A sleek, responsive, performance-driven training dashboard built as a milestone for the **DecodeLabs Industrial Training Track (Batch 2026)**. This project demonstrates a deep understanding of standard DOM manipulation, persistent state architectures, and professional frontend engineering principles[cite: 1].

🌐 **Live Deployment:** [View Live Website](https://manish93244-dotcom.github.io/Decodelabs-Task03/)

---

## 🚀 Core Engineering Standards

Following the strict enterprise guidelines outlined in **Frontend P3.pdf**, this interface is architected utilizing professional decoupling contracts instead of fragile styling hooks:

*   **`js-` Prefix Separation:** Used strictly for target selections inside the JavaScript logic layer (e.g., `.js-theme-toggle`, `.js-counter-output`). These are completely decoupled and are never utilized inside CSS files.
*   **`is-` Visual State Mutations:** Dynamic user interactions dynamically append state classes (like `.is-dark-mode`) directly to elements to shift the design language securely via modern CSS variables.
*   **Volatile Memory Architecture:** Built around the core standard that the standard browser DOM is a living, volatile map of nodes rebuilt smoothly upon page reloads.

---

## 🧠 The Architecture: The IPO Loop

This application acts as a clean client-side nervous system implementing the **Input-Process-Output (IPO)** loop rule across every single interaction element:

```text
  [INPUT: User Event] ──► [PROCESS: Business Logic] ──► [OUTPUT: DOM Mutation]
Input (The Event): Real-time monitoring of user click triggers on the sandboxed active modules.

Process (The Logic): Single-purpose javascript routines handle variable increments, catch boundary exceptions, and evaluate client theme profiles.

Output (The Mutation): Elements update explicitly using safe textContent injection properties to eliminate Cross-Site Scripting (XSS) code injection vulnerabilities entirely.

🛠️ Key Features Added
Persistent Dark Mode Module: A beautiful, responsive light/dark theme toggle utilizing standard localStorage APIs so the environment layout automatically persists across user browser sessions.

Live Interactive Tracker Sandbox: A state-driven counter showcasing live state variables driving text nodes on the volatile UI memory tree.

Modern CSS Grid Layout: A responsive presentation scheme adapting fluidly for standard widescreen monitors down to small mobile views.

📂 Project Structure
├── index.html     # Semantic structure and structural scaffolding (The Bones)
│                  # Embedded Presentation rules and variables (The Skin)
│                  # Clean single-purpose Input-Process-Output modules (The Nervous System)
└── README.md      # Documentation and engineering architectural guidelines

📋 Technology Spectrum Used
Semantic HTML5

Modern CSS3 Layouts (Variables, Custom Grid, Transitions)

Vanilla Imperative JavaScript (ES6+)
Project Authorized Portfolio Piece · Powered by DecodeLabs India[cite: 1]
