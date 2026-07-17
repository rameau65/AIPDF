# Repository Structure

```text
AIPDF/
├── .github/
│   └── workflows/
│       ├── docs.yml
│       └── validate.yml
├── docs/
│   ├── en/
│   ├── ko/
│   └── reference/
├── references/
├── templates/
├── workflows/
├── mkdocs.yml
├── requirements-docs.txt
├── README.md
├── README_KR.md
└── SKILL.md
```

## Conventions

- English documentation lives in `docs/en/`.
- Korean documentation lives in `docs/ko/`.
- Shared project examples live in `docs/reference/`.
- Production workflows live in `workflows/`.
- Reusable checklists and prompts live in `templates/`.
- Framework-level source-of-truth documents live in `references/`.
- `SKILL.md` defines operational behavior and quality requirements.

## Versioning

Use semantic versioning for framework releases. Character-specific assets may use their own version sequence, but published deliverables must record the framework version and project version together.
