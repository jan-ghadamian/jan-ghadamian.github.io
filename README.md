# jan-ghadamian.github.io

Personal academic website for Jan Ghadamian, doctoral student at ETH Zürich.

## Repository Structure

```
jan-ghadamian.github.io/
├── index.html          ← Main site file (all pages in one)
├── assets/
│   ├── css/
│   │   └── style.css   ← All styles
│   └── img/
│       └── DSCF5021.jpg ← Your portrait photo (add this!)
│   └── cv-jan-ghadamian.pdf  ← Your CV (add this!)
└── README.md
```

## Getting Started

1. **Upload your photo**
   Place your photo at `assets/img/DSCF5021.jpg`.
   The site will automatically detect and display it instead of the placeholder.

2. **Upload your CV**
   Place your PDF at `assets/cv-jan-ghadamian.pdf`.
   The download button on the CV page will link to it.

3. **Update your content** — open `index.html` and search for:
   - `<!-- ── Add your real publications below. Template: ── -->` → add your papers
   - `<!-- ── Add your real courses below. Template: ── -->` → add your courses
   - `<!-- Add your master's degree -->` etc. → fill in your education details
   - Email address: replace `jan.ghadamian@ethz.ch` if different
   - LinkedIn/ORCID links in the Contact section

4. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial site"
   git push origin main
   ```
   Your site will be live at **https://jan-ghadamian.github.io** within a few minutes.

## Pages

| Page | Content |
|------|---------|
| Home | Portrait, intro, affiliation, research interests |
| Research | Publications, research overview, education timeline |
| Teaching | Courses with code, name, semester, description |
| CV | Downloadable PDF + inline summary |
| Contact | Email, office, LinkedIn, ORCID + contact form |

## Customisation Tips

- **Colours**: Edit CSS variables at the top of `style.css` (`:root` block).
- **Fonts**: The site uses *Crimson Pro* (serif) + *DM Sans* (sans-serif) from Google Fonts.
- **Adding publications**: Duplicate any `.card` block inside the Research section.
- **Adding courses**: Duplicate any `.course-item` list item in the Teaching section.
- **Adding timeline entries**: Duplicate any `.timeline-item` in the CV section.

## GitHub Pages Setup

If not already configured:
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `(root)`
4. Save — your site is live in ~60 seconds.
