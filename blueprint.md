# NISO TECHNOLOGY HUB BLUEPRINT

## Overview
The NISO Technology Hub is a high-performance, visual-first landing page and management portal designed to showcase the core pillars of NISO Technology while providing a streamlined interface for project and asset tracking.

## Core Architecture
Strictly **Vanilla Stack** to ensure maximum performance and portability:
- **Frontend:** Semantic HTML5, CSS3 (Grid & Flexbox), Vanilla JavaScript.
- **Data Management (Conceptual):** Local-first or REST-ready structures for Projects, Files, and Users.

## Project Structure
```
niso-tech/
├── index.html          # Main hub and dashboard landing
├── css/
│   └── style.css       # Custom styles (Dark theme, Cyan accents)
├── js/
│   └── main.js        # Dashboard logic and interactivity
├── assets/             # Media and static resources
└── README.md           # Project documentation
```

## Functional Pillars
1. **Autonomous AI Agents:** Logic-driven automation models.
2. **Algorithmic Logic:** High-stability data processing systems.
3. **NISO Art Gallery:** High-fidelity digital art and creative technology.

## Dashboard Features (Integrated from V1)
- **Projects Overview:** Track active development cycles (e.g., "12 Active Projects").
- **Asset Management:** Monitor stored digital assets and files (e.g., "348 Stored Files").
- **Connectivity:** Manage integrated applications (e.g., "7 Connected Apps").

## Data Schema (Roadmap)
- **Users:** id, username, email, password_hash.
- **Projects:** id, name, owner_id, status.
- **Files:** id, filename, owner_id, type.

## Design Specifications
- **Theme:** Dark Mode (Background: #0A0A0A)
- **Accents:** Cyan / Neon Blue (#00E5FF)
- **Layout:** Responsive Card-based Grid (Dashboard Style)
- **Typography:** Clean, Sans-serif
