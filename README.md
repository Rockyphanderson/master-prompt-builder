# Master Prompt Builder

A lightweight, responsive, static web app that helps users turn a short idea into a structured AI prompt.

## Features
- Structured prompt sections: Role, Task, Context, Reasoning, Stop Conditions, and Output
- Editable generated prompt
- Copy to clipboard and export to `.txt`
- QA checklist
- Responsive desktop and mobile layout

## Run locally
No build tools or dependencies are required. Open `index.html` in a modern browser.

## Deploy with GitHub Pages
1. Create a new repository on GitHub.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save.
5. Wait for publication. GitHub will show the public URL in the Pages settings.

## Important limitation
This version assembles prompts from a client-side template. It does not call an AI model or require an API key. The QA checklist checks structural completeness; it does not independently verify factual claims.

## QA before publishing
- [ ] Test prompt generation with a sample request.
- [ ] Edit the generated prompt.
- [ ] Test copy and `.txt` export.
- [ ] Confirm the QA checklist updates.
- [ ] Test on desktop and mobile.
- [ ] Open the published GitHub Pages URL.

## Project structure
```text
master-prompt-builder/
├── index.html
└── README.md
```
