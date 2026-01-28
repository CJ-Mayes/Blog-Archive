# CJ Mayes Blog

Static blog site hosted on GitHub Pages.

## About

This is a static HTML version of the CJ Mayes blog, converted from WordPress and hosted on GitHub Pages.

## Repository Structure

```
.
├── .nojekyll          # GitHub Pages configuration (disables Jekyll)
├── index.html         # Homepage
├── blog.html          # Blog listing page
├── blog/              # Individual blog posts (125 posts)
├── css/               # Stylesheets
├── js/                # JavaScript files
├── images/            # Theme images
├── uploads/           # Blog post images and media
└── README.md          # This file
```

## Features

- **125 blog posts** covering data visualization, analytics, and Tableau
- Clean, minimal design matching the CV repository style
- Fully responsive layout
- Optimized for GitHub Pages

## Local Development

To preview the site locally:

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## GitHub Pages

This site is configured for GitHub Pages:

1. The `.nojekyll` file tells GitHub Pages not to process the site with Jekyll
2. All files are in the root directory
3. Enable GitHub Pages in repository Settings → Pages
4. Select your branch and `/ (root)` folder

Your site will be live at: `https://[username].github.io/[repository-name]`

## Design

The site uses:
- **Font**: Plus Jakarta Sans (Google Fonts)
- **Color Scheme**: Minimal design with #212529 text and #6c757d accents
- **Layout**: Clean, responsive design matching the CV repository

## License

All content © 2025 CJ Mayes. All rights reserved.
