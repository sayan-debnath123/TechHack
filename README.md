## 🚀 Overview

**TechHack** is a comprehensive autonomous engineering pipeline designed to bridge the gap between architectural concept and structural reality. By uploading standard blueprint images, our neural reasoning engine autonomously extracts geometric data, evaluates structural integrity, and recommends optimal building materials—balancing cost constraints with load-bearing safety compliances.

## ✨ Core Features

* **Real-time Pipeline Parsing**: Drop a 2D floorplan (PNG/JPG) into the engine and watch the structural logic generate live.
* **Automated BIM Extraction**: Instantly converts detected floor plans into interactive **Three.js** 3D projections, complete with load-path tracing and issue highlighting.
* **Material Intelligence Dashboard**: Maps specific wall segments against a dynamic database of materials (from AAC Blocks to Precast Concrete), generating confidence scores for durability and localized supply efficiency.
* **Interactive Cost Controller**: Seamlessly integrates the material pipeline into an interactive procurement table, updating estimated project costs in real-time.
* **Multi-Page Architecture (MPA)**: Highly modular frontend natively leveraging browser `localStorage` to transition massive 3D data states seamlessly between Landing, Demo, Dashboard, Docs, and Cost pages.

---

## 📂 Project Structure
```text
ps2/
├── backend/
│   ├── app.py             # Main Flask server
│   └── analyzer.py        # Core structural logic, geometry, and image parsing
├── frontend/
│   ├── home.html          # Entry-point Landing Engine
│   ├── demo.html          # Drag-and-drop Workflow Pipeline
│   ├── dashboard.html     # Real-time 2D/3D model canvases & AI explanations
│   ├── cost.html          # Standardized Material DB & interactive calculator
│   ├── doc.html           # Project knowledge base 
│   ├── app.js             # Client-side router & pipeline state management
│   ├── viewer2d.js        # HTMLCanvas overlay projection engine
│   └── viewer3d.js        # Three.js generation engine
└── run_server.bat         # Developer startup script
```

---
