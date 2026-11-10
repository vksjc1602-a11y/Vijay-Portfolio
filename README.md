# Vijay Kashyap C — Personal Portfolio

A responsive personal portfolio website presenting my background, education, skills, projects, achievements, and contact details.

## Live website

https://vijaykashyapc.netlify.app

## Project structure

```text
Vijay-Portfolio/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── vijay-profile.jpg
    └── Vijay-Kashyap-Resume.pdf
```

## Run locally

No build step is required. Keep `index.html` and the `assets/` directory together, then open `index.html` in a browser.

Alternatively, from this directory run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

This is a static website and can be deployed with Netlify, GitHub Pages, or another static host. The site uses `index.html` as its entry point.

## Security

Do not commit API keys, access tokens, passwords, private keys, or real `.env` files. The `.gitignore` excludes common secret and local-development files. The résumé PDF and profile image are intentionally included as requested and will be publicly accessible in this public repository.

## Project status

Some listed projects may be works in progress or concepts. Refer to the labels on the website for their current status.