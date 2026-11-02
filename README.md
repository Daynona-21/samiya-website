# House of Samiya website

Responsive HTML, CSS, and JavaScript design prototype for cleaning and property care.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.
No installation, API keys, or environment variables are required.

## Included

- Homepage, service directory and service detail views
- About and contact placeholders
- Three-step estimate preview with browser validation
- Responsive navigation and expandable FAQs

The estimate form is a preview: it does not send requests or store customer records. Photos, service areas, contact details, and exact service inclusions await owner approval.

## File guide

- `index.html`: page shell and navigation
- `style.css`: visual styles and responsive layout
- `app.js`: content, hash navigation, and form interaction
- `.gitignore`: exclusions for secrets and local files

## Keeping secrets out of Git

Never put passwords or private API keys in HTML, CSS, or browser JavaScript. Browser source is visible to visitors even when the Git repository is private. Future private keys belong on a server or in hosting secret settings.

Use `.env.example` only for empty placeholders. `.gitignore` does not protect secrets placed in source code and does not remove files already tracked by Git. Review staged changes before each push. If a real credential is committed, revoke or rotate it; deleting the file alone does not remove it from history.

## Export review

This export contains only the three website source files, this README, and `.gitignore`. The original hosting configuration, Git history, build archive, planning PDF, and local test data are excluded. Source review and pattern checks found no passwords, API keys, private keys, or personal contact details in this snapshot. This is not a guarantee against secrets being added in future edits.
