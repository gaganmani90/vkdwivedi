# Dr. Vipin Kumar Dwivedi

Personal academic website for Dr. Vipin Kumar Dwivedi, retired Professor of Genetics & Plant Breeding, Janta Vedic College, Baraut.

A plain static site: `index.html`, `styles.css` and `favicon.svg`. No build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on Vercel

1. Push this repo to GitHub.
2. On vercel.com choose **Add New → Project** and import the repo.
3. Leave the framework preset as **Other**, with no build command and no output directory.
4. Deploy. Every push to `main` redeploys automatically.

## Updating content

All content lives in `index.html`. To add a publication, copy an `<article>` block inside the right year in the Publications section, or add a new `<li>` for a new year at the top of the list.
