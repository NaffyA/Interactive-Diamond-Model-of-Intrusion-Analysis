# Interactive Diamond Model for Cyber Threat Intelligence

An interactive web-based implementation of the Diamond Model of Intrusion Analysis, designed for analysts, students, and cybersecurity enthusiasts. This project builds on the concepts taught in **SANS FOR589 - Cyber Threat Intelligence** but brings the model to life in a browser with interactivity and visual clarity.

---

## Features

- **Diamond layout per Kill Chain phase:** Adversary, Capability, Infrastructure, and Victim nodes arranged in a true diamond shape.
- **Always-visible axiom details:** Each node displays its full details without requiring clicks or pop-ups.
- **Kill Chain navigation:** Step through each phase of the intrusion (Delivery, Exploitation, Command & Control, Actions on Objectives).
- **CSV/STIX import (planned):** Import multiple intrusions to automatically generate diamonds.
- **Timeline view:** Navigate multiple intrusions over time for correlation and analysis.
- **Color-coded axioms:** Quickly identify Adversary, Capability, Infrastructure, and Victim nodes.
- **Exportable output:** Save diagrams as PDF/PNG for reporting or presentation purposes.

---

## Why This Project Is Unique

While the Diamond Model is widely taught (SANS FOR589/FOR578) and used in spreadsheets for analysis, very few interactive, browser-based implementations exist. Existing open-source tools are usually:

- Graph-based, STIX/STIX2-oriented visualizations.
- Focused on pivoting between objects rather than showing a clear, per-kill-chain diamond view.

This project is unique because it:

- Provides a **visual diamond per kill-chain phase** with fixed detail boxes.
- Positions **Infrastructure on the left** and **Adversary on the right** to follow common analytic conventions.
- Allows potential **import of multiple intrusions**, automatically generating diamonds for a full timeline analysis.
- Serves as a **bridge between Excel/manual reporting and interactive web analysis**.

---

## Getting Started

### Requirements

- Modern web browser (Chrome, Firefox, Edge)
- No backend required (purely HTML/JS/D3.js)

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

## Future Enhancements

1. **CSV/STIX import:** Automatically populate diamonds from structured threat intel data.
2. **Multiple intrusion timeline view:** Display multiple diamonds along a timeline to compare intrusions.
3. **Export/Print functionality:** Save diagrams for reports or briefings.
4. **Enhanced interactivity:** Zoom, pan, and filter nodes for deeper analysis.
5. **Integration with TIPs/SIEMs:** Map diamonds to STIX 2.1 observables for automated workflows.

---

## References

- Caltagirone, K., Pendergast, A., & Betz, C. (2013). *The Diamond Model of Intrusion Analysis.*
- SANS FOR589 - Cyber Threat Intelligence Course Material
- Open-source D3.js visualizations of STIX-based threat graphs
- Excel-based Diamond Model templates (common in CTI labs)

---

## Contributing

Contributions are welcome! Ideas include:
- Adding CSV/STIX import functionality
- Styling improvements for better readability
- Timeline and multi-intrusion support
- Export functionality (PDF/PNG)

---

![alt text](https://github.com/NaffyA/Interactive-Diamond-Model-of-Intrusion-Analysis/blob/c274c2544b54c786da1fbbcd06883c3e3dd1a9ad/Sample%2001.png) 

**This project bridges the gap between academic exercises (Excel) and practical, interactive analysis for real-world CTI workflows.**
