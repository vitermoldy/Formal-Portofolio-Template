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

### Files to replace

| File | What to put there |
|---|---|
| `assets/cv.pdf` | Your CV as a PDF. Keep the file name so every "Download CV" link keeps working. |
| `assets/img/portrait.svg` | Your portrait, 4:5, for example `portrait.jpg` at 800 x 1000. Update the `src` in the About section. |
| `assets/img/work-1.svg` to `work-3.svg` | One image per project, 4:3, for example 1200 x 900: a photograph of the work, a report cover, a chart of the result. Update each `src` and `alt`. |
| `assets/img/favicon.svg` | Change the letter to your own initial. |

Compress photographs before you add them (under about 200 KB each). The pictures crop to fill their frames, so keep the subject near the centre.

### Optional

- **Social links:** the footer has an empty `.socials` block with a commented LinkedIn example. Add only accounts you actually use.
- **Colours:** change the `--p-*` values in the first `<style>` block in `index.html`. Keep body text at a 7:1 contrast ratio or better against the background, and the button colour at 4.5:1 or better against white.
- **Font:** the page uses Albert Sans from Google Fonts. To change it, replace the Google Fonts link and the two `--font-*` values.

## Keep it working

- Keep each line of the headline under about 18 characters (name on line one, role on line two), so it stays on two lines on every screen.
- Every section is sized to fill exactly one screen (two on a phone for Experience and Work). If you add much more text to a section, check it on a phone and a tablet. Move longer detail into your CV.
- Only show numbers, clients and quotes you can back up. If you add a recommendation, use a real quote, with the person's permission.
- Every link must go somewhere real: a section on the page, your email address or a file in the repo.
