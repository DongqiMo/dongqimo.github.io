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

## Updating the CV
The CV page (`cv.html`) shows the resume as text, with a download button for `Dongqi_Mo_Resume.pdf`. To update: replace the PDF (same file name) and edit the text in `cv.html`.

## Preview locally
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000.
