# Blog Post Styling Conventions

## HTML Elements
- `<h1 id=post-title>` is for post title
- `<p id=post-date>` is for post date (smaller and lighter)
- `<h3>` is for section titles
- What to style as code:
    - Usernames
    - Scripts
    - Filenames
    - Exit codes
    - Domains and SMB shares

## highlight.js

- Usage: https://highlightjs.org/usage/
- Supported languages: https://github.com/highlightjs/highlight.js/blob/main/SUPPORTED_LANGUAGES.md
- Demo: https://highlightjs.org/static/demo/
### Nmap
- If terminal is included, style as `language-shell`
- If terminal is not include, style as `language-markdown`

## Pre-publishing Checklist
- Replace funky `kali*kali` terminal character with `@`
- Ensure that all code blocks are assigned a `highlight.js` class
- Run post through Grammarly for typos or poorly-worded sentences
- Replace the following characters with their HTML-encoded equivalents in code blocks:
    - \& --\> \&amp;
    - \< --\> \&lt;
    - \> --\> \&gt;
    - \' --\> \&apos;
    - \" --\> \&quot;
- Add blog post title to `blog.html`
- Update publishing date 