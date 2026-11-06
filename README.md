# Dongqi Mo — Portfolio

UI/UX designer and XR researcher (MFA in Design, UC Davis). This is a static rebuild of my Wix portfolio, hosted on GitHub Pages.

## Structure

```
index.html                 Home — intro + research projects
industry-projects.html     Industry Projects
mentorship-showcase.html   Mentorship Showcase (student work)
cv.html                    CV
about.html                 Contact
projects/                  Case-study pages (safe-ski, officonnect, family, comb, comb-community)
css/style.css              All styling
images/                    Images and videos
```

Plain HTML/CSS — no build step. Edit any `.html` file directly and push; GitHub Pages redeploys automatically.

## Adding a CV
Put your PDF at `cv.pdf` in the repo root, then uncomment the `<iframe>` block in `cv.html`.

## Preview locally
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000.
