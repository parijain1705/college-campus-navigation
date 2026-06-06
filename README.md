# 🗺️ Jain College Campus Navigator

An interactive, responsive single-page web application designed to help students, faculty, and visitors seamlessly navigate the Jain College campus. The tool replaces static images and complex signs with an elegant, smart campus guide containing detailed building information, a keyword-based pathfinding route generator, and a live SVG-driven interactive map.

---

## ✨ Features

### 1. 🏠 Welcoming & Campus Flow
* **Smart Onboarding:** Provides a high-level overview of the campus structure starting from the main Entrance Gate.
* **Sequential Timeline:** Highlights the academic block flow (`B.Sc` ➔ `Mathematics` ➔ `Biology` ➔ `BBA` ➔ `BCom` ➔ `Arts` ➔ `Masters` ➔ `PhD`) to help users build a mental model of the campus grid.

### 2. 🏢 About Buildings & Smart Search
* **Dynamic Information Cards:** Users can browse cards for each sector of the college to see a breakdown of what rooms, cabins, or fields are located inside.
* **Contextual Route Finder:** Includes a pathfinding engine. Select your current location, type what or who you are looking for (e.g., `Dean`, `Football Ground`, `PhD`), and the system will instantly parse your query and write step-by-step walking instructions.
* **Keyword Matching System:** Built with an internal alias library, allowing search strings like `maths` or `hod` to map reliably to their respective structural blocks.

### 3. 🗺️ Interactive Campus Map
* **Vector-Graphic Accuracy:** Built entirely using native SVG nodes, scaling smoothly across both mobile displays and wide desktop configurations.
* **Hover UI Tooltips:** Provides immediate feedback by showing quick-summary tooltips when hovering over campus regions.
* **Cross-Tab Synchronization:** Clicking an area on the interactive map automatically shifts focus, opens up the details tab, and dynamically highlights the target building's full asset directory.

---

## 🛠️ Architecture & Technology Stack

The application is written strictly in native web technologies, requiring no external packages, build steps, or external dependencies:

* **HTML5:** Semantic architecture utilizing standalone section templates and structured SVG paths.
* **CSS3:** Custom linear/radial gradients, glassmorphism (`backdrop-filter`), CSS grid layouts, responsive media queries (`@media`), and hardware-accelerated entry animations (`@keyframes`).
* **Vanilla JavaScript (ES6+):** Complete client-side state management mapping multi-node data profiles, search index parsing, event-driven DOM updates, and path script generation.

---

## 📂 File Structure

```text
college-campus-navigation/
│
├── index.html       # Combined markup, presentation styles, and structural data
└── README.md        # Documentation and system manual
