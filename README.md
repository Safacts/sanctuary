# Sanctuary 🌿

### *A High-Fidelity Digital Sanctuary for the Modern Professional*

Sanctuary is a premium, "no-build" mental wellness MVP designed to provide immediate nervous system regulation and grounding for corporate professionals. Built with a philosophy of **minimalism, accessibility, and sensory satisfaction**, Sanctuary eliminates the friction of complex installations, running entirely in the browser while maintaining the feel of a native high-end application.

---

## 🛠 Tech Stack & Architecture

To achieve zero-setup portability without sacrificing aesthetics, Sanctuary utilizes a modern "CDN-first" architecture:

-   **Frontend Engine**: React 18 (via UMD) for component-driven reactivity.
-   **Styling System**: Tailwind CSS (Play CDN) for a utility-first, responsive design system.
-   **Typography**: Outfit (Google Fonts) for a modern, approachable geometric sans-serif feel.
-   **Iconography**: Custom-tuned Inline SVGs for 100% runtime stability and zero external dependency lag.
-   **Audio Engine**: Web Audio API for procedurally generated, low-latency calming tones and tactile feedback.
-   **Deployment**: Optimized for Vercel Static Hosting.

---

## ✨ Key Features

### 1. Compassion Chat
An AI-driven, empathetic messaging interface designed for emotional venting. 
-   **Safety Guardrails**: Built-in detection for distress keywords with automatic resource redirection (e.g., 988 Lifeline).
-   **Mood Check-in**: Integrated biometric entry for tracking emotional energy.

### 2. The Unwind Room
A collection of grounding mini-games designed to pull users out of "thought loops."
-   **Digital Bubble Wrap**: A tactile sensory experience featuring procedurally generated "pop" sounds and satisfying visual feedback.
-   **Zen Garden**: A canvas-based mindfulness activity where users can rake digital sand, fostering focus and flow.

### 3. Biometric Reset
Scientifically backed nervous system regulation tools.
-   **Box Breathing (4-4-4-4)**: A guided visual and audio experience that uses rhythmic expansion and "OM" tones to lower heart rate and cortisol levels.

### 4. Premium UX Polish
-   **Adaptive Layout**: Seamless transition between a desktop sidebar and a mobile bottom navigation bar.
-   **Custom Cursor System**: A soft-following, reactive cursor that enhances the "premium" tactile feel on desktop.
-   **Glassmorphism 2.0**: Multi-layered blur effects and subtle borders for a modern, airy aesthetic.

---

## 🚀 Getting Started

### Prerequisites
None. Sanctuary is designed to be truly portable.

### Local Development
1.  Clone the repository:
    ```bash
    git clone https://github.com/Safacts/sanctuary.git
    ```
2.  Open `index.html` in any modern web browser.
    *No `npm install` or `build` steps are required.*

### Deployment
Sanctuary is configured for Vercel. Simply push to `master` and the `vercel.json` will handle clean URLs and static routing automatically.

---

## 📂 Project Structure

```text
sanctuary/
├── index.html        # Main Application Entry (React/Tailwind/Logic)
├── vercel.json       # Deployment configuration for Vercel
├── README.md         # Project Documentation
├── .gitignore        # Version control exclusions
└── css/
    └── style.css     # Supplementary global animations & custom UI overrides
```

---

## 🗺 Roadmap
- [ ] **Zen Garden v2**: Multiple rake patterns and interactive "stone" placement.
- [ ] **Ambient Soundscapes**: Continuous procedural background white noise (rain, forest).
- [ ] **Local Persistence**: `localStorage` integration for mood history and streaks.
- [ ] **PWA Support**: Offline capability and "Add to Home Screen" functionality.

---

## 📄 License
Internal / Private. Created as a Digital Sanctuary MVP.
