# CV Interactive — Cyclic Voltammetry Schematic

An interactive browser-based visualisation of **Cyclic Voltammetry (CV)**, built with Chart.js and vanilla JavaScript. Designed as an educational tool and LinkedIn post companion for a series on electrochemical characterisation techniques in energy storage research.

🔗 **[Live demo](https://MJElectrochemist.github.io/cv-interactive)**

---

## What it does

Drag the sliders and watch a physically accurate voltammogram update in real time:

- **Scan rate (ν)** — peak current scales with √ν per the Randles-Ševčík equation
- **Reversibility** — peak separation ΔEp widens as the system moves from reversible → quasi-reversible → irreversible
- **Number of electrons (n)** — peaks sharpen and shift inward as n increases

Live metric cards update continuously:
| Parameter | Meaning |
|---|---|
| Epa | Anodic peak potential |
| Epc | Cathodic peak potential |
| ΔEp | Peak separation (59/n mV for ideal reversible) |
| \|Ipa/Ipc\| | Peak current ratio (≈ 1.00 for reversible) |

---

## Key equation
