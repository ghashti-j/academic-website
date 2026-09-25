# Jesse Ghashti — Academic Website

A static personal academic website built with plain HTML & CSS, designed for deployment on Cloudflare Pages.

## Local Preview

Open `index.html` in your browser. No build step needed.

## Customization

1. Replace `images/portrait.png` with your headshot
2. Replace `images/background.png` with your geometric background image
3. Replace the icon PNGs (`icon-location.png`, `icon-linkedin.png`, etc.) with your custom icons
4. Update the URLs in `index.html` (LinkedIn, Google Scholar, ORCID, GitHub)
5. Edit page content as needed

## Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. In Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git
3. Select the repo, set **Build output directory** to `/` (root) — no build command needed
4. Add your custom domain in the Pages project settings

## Structure

```
├── index.html          # Homepage / Biography
├── style.css           # Global stylesheet
├── images/
│   ├── background.png  # Fixed background
│   ├── portrait.png    # Your headshot
│   └── icon-*.png      # Sidebar icons
└── pages/
    ├── research.html
    ├── publications.html
    ├── teaching.html
    ├── blog.html
    └── contact.html
```
