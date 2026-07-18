# rishabhinai.github.io

Personal professional website for Rishabh Agrawal — CA, CFE, Lead Investigator, AI Tool Builder.

## Setup (5 minutes)

1. Create a GitHub repo named exactly `rishabhinai.github.io`
2. Upload all files from this folder (keeping the same structure)
3. Go to repo Settings → Pages → Source: Deploy from branch → Branch: main → Folder: / (root)
4. Your site will be live at `https://rishabhinai.github.io` within 2–3 minutes

## File Structure

```
rishabhinai.github.io/
├── index.html          → Home page
├── portfolio.html      → Career, credentials, skills
├── investigation.html  → Fraud typologies, AML framework
├── tools.html          → All tools (forensic + trading)
├── markets.html        → AlphaRadar, CARA, trading strategies
├── blogs.html          → 3 thought leadership posts
├── contact.html        → Contact + site map
├── style.css           → Shared stylesheet
└── assets/
    └── photo.jpg       → Add your photo here (recommended: 400x480px, face-forward)
```

## Adding Your Photo

The hero section currently shows a navy/gold "RA" monogram card instead of a photo placeholder. To swap in a real photo later:

1. Add a professional headshot to `assets/photo.jpg`
2. In `index.html`, replace the monogram div:
   ```html
   <!-- Replace this: -->
   <div class="hero-photo-wrap" id="photoWrap">
     <div class="monogram">RA</div>
     <div class="monogram-sub">Rishabh Agrawal</div>
   </div>

   <!-- With this: -->
   <div class="hero-photo-wrap" id="photoWrap">
     <img src="assets/photo.jpg" alt="Rishabh Agrawal" />
   </div>
   ```

## Customisation Notes

- **LinkedIn URL**: Set to `https://www.linkedin.com/in/rishabh-agrawal-ca/` in contact.html and index.html — update if the slug changes.
- **Tool links**: Live Streamlit app URLs are already filled in (alpharadar, cara, nsescanner, resultsedge, iposhare, tradeos). Update if URLs change.
- **AML Hub link**: Update `#` in tools.html with your Netlify deployment URL
- **Yes Bank timeline**: Update exact years in portfolio.html if they differ from 2018–2022

## Design Choices

- **Palette**: Navy (#0F1B2D) + Gold (#C8952A) + Warm white (#F8F7F4)
- **Fonts**: DM Serif Display (headings) + Inter (body) — loaded from Google Fonts
- **Signature**: Diagonal ledger-rule pattern on hero background (CA/auditor reference)
- **Theme**: Light, institutional, professional — no dark backgrounds

## No Framework Needed

Pure HTML + CSS + vanilla JS. No build step, no npm, no dependencies.
Google Fonts loaded via CDN. Works offline after first load.
