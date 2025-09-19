# Interactive Diamond Model for Cyber Threat Intelligence

An interactive web-based implementation of the Diamond Model of Intrusion Analysis, designed for analysts, students, and cybersecurity enthusiasts. This project builds on the concepts taught in **SANS FOR589 - Cyber Threat Intelligence** but brings the model to life in a browser with interactivity and visual clarity.

---

## Features

- **Diamond layout per Kill Chain phase:** Adversary, Capability, Infrastructure, and Victim nodes arranged in a true diamond shape.
- **Always-visible axiom details:** Each node displays its full details without requiring clicks or pop-ups.
- **Kill Chain navigation:** Step through each phase of the intrusion (Delivery, Exploitation, Command & Control, Actions on Objectives).
- **Color-coded axioms:** Quickly identify Adversary, Capability, Infrastructure, and Victim nodes.
- **Exportable output:** Save diagrams as PDF/PNG for reporting or presentation purposes.

---

## Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/interactive_diamond_model.git
```
2. Open `index.html` in your browser.

### Usage

- Use the **sidebar** to select a Kill Chain phase.
- Navigate using **Previous/Next buttons**.
- Node boxes show all relevant axiom details.
- (Future) Upload a CSV to auto-generate diamonds for multiple intrusions.

---

## References

- Caltagirone, K., Pendergast, A., & Betz, C. (2013). *The Diamond Model of Intrusion Analysis.*
- SANS FOR589 - Cyber Threat Intelligence Course Material

---

![alt text](https://github.com/NaffyA/Interactive-Diamond-Model-of-Intrusion-Analysis/blob/c274c2544b54c786da1fbbcd06883c3e3dd1a9ad/Sample%2001.png) 

**This project bridges the gap between academic exercises (Excel) and practical, interactive analysis for real-world CTI workflows.**
