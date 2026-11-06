# Formal Portfolio Template

A one-page portfolio for a professional in any field: your name and role, a short profile, work history and education, three selected projects and a way to email you. It is plain HTML and CSS, with no build step.

Every piece of sample text is a placeholder ("Your Name", "Job title", "Company name") for you to overwrite. Nothing on the page is invented, so there are no made-up clients, numbers or testimonials to delete.

## Preview it

The page loads its scripts as ES modules, and browsers block those on `file://`. Serve the folder over HTTP instead:

```bash
npx serve .
# or
python -m http.server 8000
```

Then open the address it prints (for example `http://localhost:8000`).
