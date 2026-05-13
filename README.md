# Nexus-WA (Web Assembly) 
### **The Next-Generation Declarative Web Engine.**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Version](https://img.shields.io/badge/Version-2.0--ULTRA-cyan.svg)](https://github.com/tiwut/Nexus-the-programming-language)
[![Backend](https://img.shields.io/badge/Backend-Nexus--Titan-blueviolet.svg)](https://tiwut.org/nexus)

**Nexus-WA** is a revolutionary web framework that eliminates the need for traditional HTML, CSS boilerplate, and complex JavaScript. It uses a clean, nested configuration syntax interpreted in real-time by a high-performance engine. 

Designed for the **2026 High-End Web Experience**, Nexus-WA provides direct access to over **12,000 native browser APIs** while maintaining a 100% declarative workflow.

---

## Key Features

*   **Zero-HTML/JS Boilerplate:** Build entire high-end applications using only `.nxwa` configuration files.
*   **12,000+ Native APIs:** The engine maps directly to the browser's CSSOM and DOM API. If the browser supports it, Nexus-WA supports it natively.
*   **Advanced Logic Engine:** Handle complex interactions like Mouse-Tracking (Glassmorphism Glow), smooth scrolling, and media control via `work.nxwa`—without writing JavaScript.
*   **Native Media Integration:** Seamlessly embed and control `<video>`, `<iframe>`, and `<canvas>` objects.
*   **Ultra-Modern Design:** Built-in support for 2026 design trends: Deep Dark Mode, Glassmorphism, and Fluid Typography.
*   **Nexus-Titan Ready:** Fully compatible with the **Nexus-Titan (Python)** interpreter for powerful full-stack backend integration.

---

## Quick Start

Nexus-WA runs as a client-side engine. Because it fetches configuration files, you need to run it via a local web server.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Nexus-Titan/NEXUS-WA-DOM-engine.git
    cd NEXUS-WA-DOM-engine
    ```

2.  **Start a Local Server:**
    Using Python (pre-installed on most systems):
    ```bash
    python3 -m http.server 8000
    ```

3.  **Open in Browser:**
    Navigate to `http://localhost:8000`.

---

## File Structure

| File | Description |
| :--- | :--- |
| `index.html` | **The Core Engine.** Interprets NXWA files and renders the DOM. |
| `meta.nxwa` | **Head & SEO.** Defines title, fonts, external scripts (CDN), and meta tags. |
| `sys.nxwa` | **System/Structure.** Defines the "Virtual Tree" (The UI components). |
| `theme.nxwa` | **Styling.** High-end CSS mapping including Pseudo-classes and Keyframes. |
| `work.nxwa` | **Logic.** Defines events (clicks, movement, scrolls) and state changes. |

---

## The NXWA Syntax

Nexus-WA uses the **Virtual Tree** pattern. It is cleaner than HTML and more powerful than JSON.

### Building a UI (`sys.nxwa`)
```text
app = (
    nav = (
        a = txt"NEXUS-WA" url"#" theme"nav-logo"
    ) theme"navbar"

    header = (
        h1 = txt"The Future is Declarative" theme"hero-title"
        button = txt"Get Started" theme"btn-glow" work"scroll-action"
    ) theme"hero-container"
) theme"global-bg"
```

### Adding Interaction (`work.nxwa`)
```text
# No JavaScript needed for modern effects
scroll-action = trigger"click" action"scroll" target"#features"
glow-effect = trigger"mousemove" action"track-mouse"
```

---

## Future Vision: Nexus-Titan Integration

Nexus-WA is built to be the frontend for **Nexus-Titan**. While the `.nxwa` engine handles the high-end rendering in the browser, the **Nexus-Titan (Python)** interpreter works on the server side to inject dynamic data, handle database queries, and manage authentication.

---

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. 

**What this means:**
*   You **can** use this framework for free.
*   If you modify the engine or build a web service using it, you **must** share your source code under the same license.
*   You **must** keep the original author's copyright notice.

*Copyright © 2026 Tiwut Nexus Web Assembly Project. All rights reserved.*

---

**Join the revolution of the declarative web.** 
[Visit tiwut.org/nexus for more info.](https://tiwut.org/nexus)
