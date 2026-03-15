<div align="center">

# 🌿 EntheoGen Mixed Modality Guide

**Ceremonial Psychedelic Interaction Guidance**

*Evidence-grounded risk engine and strict safety posture for pre-reflective exploration*

**Live demo:** 
[www.entheogen.newpsychonaut.com](https://www.entheogen.newpsychonaut.com/) 
· 
[entheogen.azurewebsites.net](https://entheogen.azurewebsites.net)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

<img src="entheogen-asset-beta-0.1.gif" width="600" alt="EntheoGen release demo" />

</div>

---

## Please note:

EntheoGen is currently in beta and is not intended to provide clinical, medical advice. Consult your doctor for advice on mixing substances.

## What is EntheoGen?

EntheoGen is a substance interaction guidance app focussed on intentional use of psychedelics. 

The web application estimates the effects of mixing the two substances entered into the drop-down menus. 

Data is personal and not stored remotely (i.e., not recorded or held by us).

EntheoGen's data model is mapped specifically to sacramental substances often used in psychedelic ceremonies, medication classes, and commonly used consciousness-altering substances.

## We need YOUR entheogenic knowledge

Unlike purely generative AI tools, the interaction output here is intended to strictly evidence-grounded and rule-based. 

EntheoGen is trained on peer-reviewed academic literature. 

However, study is light especially in areas such as interactions between less commonly used entheogenic substances.

# Beta test EntheoGen and leave your comments in our [<Discussions>](https://github.com/chaosste/EntheoGen/discussions/1)!

It attempts to offer explicit confidence ratings and transparent source traceability, (although it can currently refer directly to source note pdfs we compiled, and requires tweaking). 

If pharmacological evidence is missing, the engine should return `Unknown` rather than generating speculative predictions. 

# Recent Updates

EntheoGen sometimes now defers to expertise if academic literature is unavailable.

Extended explanations provide database detail for beta test analysis.

## Why it is different

- ⚙️ **Evidence-Grounded Risk Engine** — deterministic output based on curated pharmacological rules
- 🛡️ **Strict Safety Posture** — missing-data pairs explicitly resolve to `UNK` (Unknown) rather than guessing
- 🔍 **Source Traceability** — readouts expose confidence and evidentiary source metadata
- 💾 **Privacy Focused** — favorites are stored in local browser storage; hosting/CDN logs may still exist
- 🖤 **Minimalist & Accessible** — clean UI with distinguishable risk levels and non-prescriptive language

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + TypeScript + Vite |
| Risk Engine | Deterministic rule-based assessor |
| Design | Tailwind CSS, Lucide Icons |
| Deployment | Azure App Service (Linux) |

## Quickstart

```bash
# Clone the repository
git clone https://github.com/chaosste/EntheoGen.git
cd EntheoGen

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Related Projects

- [SeshGuard](https://github.com/chaosste/SeshGuard) — broader interaction safety checker
- [NeuroPhenom-AI](https://github.com/chaosste/NeuroPhenom-AI) — high-fidelity clinical interface for diachronic slicing and subjective reporting
- [Anubis](https://github.com/chaosste/Anubis) — psychedelic trip-report interview system

## Safety Posture & Disclaimer

EntheoGen provides educational harm-reduction guidance only. It is **not** a substitute for professional medical, psychological, or therapeutic advice. If there is no explicit evidence for an interaction combination, EntheoGen classifies it as `Unknown/Insufficient Data`.

In moments of clinical emergency, seek urgent professional medical help.

---

<div align="center">

**Built by [Steve Beale](https://newpsychonaut.com)**

[newpsychonaut.com](https://newpsychonaut.com)

© 2026 Stephen Beale. MIT License.

</div>
