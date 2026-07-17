# AI Character IP Development Framework (AIPDF)

AIPDF is an end-to-end framework for building character intellectual property with AI—from character identity and worldbuilding to brand systems, product visualization, licensing, investment, and publishing.

[한국어 README](README_KR.md) · [Documentation](docs/en/index.md) · [한국어 문서](docs/ko/index.md)

## Phase 1 — Framework Core

- GitHub repository architecture
- MkDocs Material documentation site
- Korean and English documentation
- Core `SKILL.md`
- Character, brand, worldbuilding, product, licensing, and publishing guides
- GitHub Actions validation and GitHub Pages deployment

## Framework Layers

1. **Character Core** — Character DNA, silhouette, face consistency, pose and expression systems
2. **World & Emotion** — Emotion Bloom™, worldbuilding, relationships, story loops
3. **Brand System** — Visual language, color, typography, diagram and content systems
4. **Product System** — Art toys, packaging, merchandise, retail and exhibition
5. **Business System** — Licensing, commercialization, investment and revenue architecture
6. **Publishing System** — PPTX, PDF, DOCX and documentation delivery

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements-docs.txt
mkdocs serve
```

Open `http://127.0.0.1:8000`.

## Repository Structure

```text
AIPDF/
├── .github/workflows/
├── docs/
│   ├── en/
│   └── ko/
├── references/
├── templates/
├── workflows/
├── mkdocs.yml
├── requirements-docs.txt
├── README.md
├── README_KR.md
└── SKILL.md
```

## Reference IP

SINDAENG is the initial reference implementation. The framework itself is reusable for other character IPs by replacing the project profile and maintaining the same quality gates.

## Rights and License

Framework documentation and configuration are released under the repository license. Character artwork, trademarks, and SINDAENG-specific assets remain subject to the rights holder’s terms unless explicitly licensed otherwise.
