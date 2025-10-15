# Auto-generated README (Round 1)

**Project brief:** Publish a Bootstrap page with form id="github-user-" that fetches a GitHub username, optionally uses ?token=, and displays the account creation date in YYYY-MM-DD UTC inside #github-created-at.

**Attachments:**


**Checks to meet:**
document.querySelector('#github-user-').tagName === 'FORM'\ndocument.querySelector('#github-created-at').textContent.includes('20')\n!!document.querySelector('script').textContent.includes('https://api.github.com/users/')

## Setup
1. Open `index.html` in a browser.
2. No build steps required.

## Notes
This README was generated as a fallback (OpenAI or AI Pipe failed).