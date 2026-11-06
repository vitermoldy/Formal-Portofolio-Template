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

## Make it yours

Search `index.html` for each placeholder and replace it:

| Placeholder | Where it appears |
|---|---|
| `Your Name` | Title, nav, headline, About heading, footer, copyright, portrait `alt` |
| `Y` (one letter) | The initial mark in the nav and footer |
| `job title` | The underlined second line of the headline |
| `Job title, Company name` | Hero facts and the three work history rows |
| `City, Country` | Title, description, hero facts, footer |
| `Year`, `Year to present` | Work history, education and certifications |
| `Degree, Institution`, `Certification, Issuing body` | Education and certifications |
| `Project title`, `Your role, Organisation name, Year` | The three project tiles |
| `you@yourname.example` | All four "Email me" links |

The paragraphs under each heading are written as instructions ("Write two sentences here..."). Replace them with your own words.
