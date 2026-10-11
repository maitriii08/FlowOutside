<div align="center">

# 🌿 FlowOutside

> **An AI-powered anti-burnout productivity workbench merging Pomodoro deep work discipline with intelligent outdoor movement pacing.**

[![Hacktoberfest 2026](https://img.shields.io/badge/Hacktoberfest-2026-orange.svg)](https://hacktoberfest.com)
[![Best Use of Gemma](https://img.shields.io/badge/Category-Best%20Use%20of%20Gemma-blueviolet.svg)](https://ai.google.dev/)


</div>



## 💡 The Inspiration
We spend way too much time staring at screens. Between coding, debugging, and starting new digital projects, staying indoors is far too easy. 

**FlowOutside** was built for the **Hacktoberfest Touch Grass Challenge** with one simple goal and serious utility: *using an open-weight local model to save you from screen burnout and naturally encourage you to step outside.*

Instead of keeping you chained to a traditional productivity dashboard, FlowOutside takes a messy, unorganized to-do list and transforms it into a structured, alternating schedule—interleaving indoor focus sprints with optimized real-world outdoor errands and nature breaks.



## ⚡ How It Works
1. **Task Ingestion:** Paste your daily to-do list (e.g., *buy oven, buy vegetables, write journal, learn guitar, study maths*).
2. **Local AI Engine:** Click **"Wake Gemma"** to initialize Google's open-weight **Gemma 4** model directly in your browser memory using **WebGPU** and **Transformers.js**.
3. **Alternating Pacing Engine:** The app parses your tasks and structures them into a clean, alternating cadence:
   * `[Indoor Task A]` ➔ `[Outdoor Errand B]` ➔ `[Indoor Task C]` ➔ `[Outdoor Errand D]`
   * If zero outdoor tasks are detected, it intelligently schedules a refreshing 15-minute sunlight and stretching break to combat screen fatigue.



## 🛠️ Technical Architecture & Tech Stack
FlowOutside is engineered as a high-performance, single-page application utilizing modern browser-native compute capabilities:

* **Frontend & UI/UX:** HTML5, modern CSS with custom 3D tactile paper UI, dot-grid textures, and a dark topographic forest theme powered by Tailwind CSS.
* **Typography:** *Bricolage Grotesque* for striking headings, *Geist* for clean prose, and *JetBrains Mono* for telemetry logs.
* **AI & Machine Learning Runtime:** Google's open-weight **Gemma 4 (ONNX quantized 4-bit model)** executed entirely client-side via **Hugging Face Transformers.js** and hardware-accelerated **WebGPU**.
* **Telemetry & State Management:** Built-in real-time frontend-to-backend console worker logs mirroring local model tensor allocation and task routing.
* **Licensing:** Open-source under the permissive Apache 2.0 License.



## 🛡️ Privacy First (Zero Telemetry)
Because Gemma runs locally in your browser workspace via WebGPU, your daily to-do lists, routines, and schedules never leave your machine. No telemetry, no external server tracking, and zero API costs. 



## 📦 Running Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/maitriii08/FlowOutside-.git](https://github.com/maitriii08/FlowOutside-.git)
   cd FlowOutside-
