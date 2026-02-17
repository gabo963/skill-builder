This file explains how a skill folder should be structured.

```
your-skill-name/
├── SKILL.md              # Required - main skill file
├── scripts/              # Optional - executable code
│   ├── process_data.py   # Example
│   └── validate.sh       # Example
├── references/           # Optional - documentation
│   ├── api-guide.md      # Example
│   └── examples/         # Example
└── assets/               # Optional - templates, etc.
    └── report-template.md # Example
```

## SKILL.md Naming

- Must be exactly SKILL.md (case-sensitive)
- No variations accepted (SKILL.MD, skill.md, etc.)

## Skill Folder Naming

- Use kebab-case: `notion-project-setup` (good)
- No spaces: `Notion Project Setup` (bad)
- No underscores: `notion_project_setup` (bad)
- No capitals: `NotionProjectSetup` (bad)

## No README.md

- Don't include README.md inside your skill folder
- All documentation goes in SKILL.md or references/
- Note: when distributing via GitHub, you'll still want a repo-level README for human users — see Distribution and Sharing.
