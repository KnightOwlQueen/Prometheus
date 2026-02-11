# Prometheus

Prometheus is a high-fidelity, industrial-themed web interface designed for a private cluster deployment system. It utilizes a "Neural-Aesthetic" UI (Industrial Sci-Fi) characterized by monochromatic grids, high-contrast orange accents, and real-time operational feedback.

## 🏗 System Architecture

The project is structured as a progressive web flow that simulates the provisioning of a neural processing cluster:

1.  **Index (Landing/Cart):** Initial resource selection and authentication.
2.  **Checkout:** Secure credit/neural token processing.
3.  **Success/Init:** A simulated handshake and cluster initialization sequence.
4.  **Dashboard:** The central operational hub with real-time metrics and terminal access.



---

## 🚀 Core Features

### 1. Neural Command Terminal (Dashboard)
A functional command-line interface (CLI) that allows operators to interact with the Forge Core.
* **Commands:** `HELP`, `STATUS`, `DEPLOY`, `FLUSH`, `SYSTEM`, `CLEAR`.
* **Feedback:** Dynamic responses with simulated processing latency.

### 2. Real-Time Resource Monitoring
Visualizes the load on the allocated cluster using dynamic CSS-animated bars.
* **Metrics:** CPU Expansion, Synaptic Memory, and Inference Throughput.
* **Fluctuation:** Automated script-driven data variance to simulate live load.

### 3. Visual Identity & UX
* **Glassmorphism:** Layered UI elements with backdrop-blur and 1px borders.
* **Scanline Overlay:** CRT-style visual filters for terminal immersion.
* **Noise Texture:** Subtle grain overlay to reinforce the industrial aesthetic.

---

## 🛠 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Styling** | Tailwind CSS 3.0 |
| **Typography** | Outfit (Headings), Inter (UI), JetBrains Mono (Technical) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Icons/Assets** | Unsplash (Neural Map), Google Fonts |

---

## 📂 File Directory

* `index.html`: Product selection and entry point.
* `checkout.html`: Transaction simulation.
* `success.html`: The Neural Token generation and initialization sequence.
* `dashboard.html`: Main operational interface.
* `docs.html`: (Pending) Technical manual and API protocols.


---
