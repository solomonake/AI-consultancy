# Riipen — Team 22 AI Workflow Project

This folder contains everything for the Riipen AI-assisted educator update workflow built by Team 22 (AI for Virginia, Summer 2026).

## What's here

```
riipen/
├── index.html          ← Jen's interactive Q&A intake page (deployed on Netlify)
└── README.md           ← This file
```

## How the memory system works

1. **Jen fills out the Q&A page** at the Netlify URL
2. When she clicks **Submit**, it opens a pre-filled GitHub Issue in this repo
3. She clicks **Submit new issue** — that's it
4. The issue is tagged `jen-input` and `riipen`
5. Team 22 reads the issue and updates:
   - Risk thresholds in the analytics framework
   - Prompt library language and structure
   - Educator update template format

## Issue labels

| Label | Meaning |
|-------|---------|
| `jen-input` | Comes from Jen's Q&A form |
| `riipen` | All Riipen project issues |
| `threshold-update` | Changes to risk detection logic |
| `prompt-update` | Changes to the prompt library |

## Viewing all of Jen's responses

Go to: `https://github.com/solomonake/AI-consultancy/issues?q=label:jen-input`

## Deployed URLs

- **Jen's Q&A page:** `https://[your-site].netlify.app/riipen`
- **Main demo:** `https://[your-site].netlify.app`

## Team

| Name | Role |
|------|------|
| Rachael DelNegro | Project Manager |
| Solomon Muwanguzi | Prompt Engineer |
| Miu Patrathiranond | Handoff Lead |
| Sarah Zhu | Threshold Lead |
| Daniel Manurung | AI Research Lead |
