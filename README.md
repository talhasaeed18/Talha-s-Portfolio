# Muhammad Talha Saeed | Portfolio

A LinkedIn-style personal portfolio and profile viewer. It is a single HTML file with no frameworks, no build step and no dependencies, so it opens in any browser and deploys anywhere.

**Live site:** https://talhasaeed18.github.io/Talha-s-Portfolio/

## About

Muhammad Talha Saeed is a Multan-based founder and creator. He is the CEO and Founder of [Delta Services](https://deltaservices.site), a digital agency for web development, AI automation and branding, and works as a YouTube editor, thumbnail and brand designer, and lead generator with 4+ years of experience.

## Features

- **Profile tab:** About, Experience, Education, Licenses and Certifications, Skills and Interests, in a LinkedIn-style layout with a cover banner and profile photo.
- **Websites tab:** the Delta Services project (with a live link), client website videos, businesses served and the Delta team.
- **Portfolio tab:** podcast and YouTube work, logos and brand design, website videos and college projects.
- **CV tab:** the full resume on the page, with a "Print or save as PDF" button.
- **Light and dark theme:** follows the device setting, with a manual toggle.
- **Fully responsive:** tested from 320px phones to 4K monitors, with no sideways scrolling.
- **Accessible:** keyboard-friendly tabs, visible focus states, large tap targets and reduced-motion support.
- **Single file:** the profile photo is embedded in the HTML, so there are no extra images to manage.

## Project structure

```
.
├── index.html                          # The portfolio website (rename of talha-portfolio.html)
├── Muhammad_Talha_Saeed_CV_2026.pdf    # Downloadable one-page CV
└── README.md
```

## Run locally

No installation is needed.

1. Download or clone the repository.
2. Open `index.html` in your browser.

To serve it locally instead:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages

1. Rename `talha-portfolio.html` to `index.html`.
2. Create a new repository on GitHub and upload `index.html`, the CV PDF and this `README.md`.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute, your site is live at `https://talhasaeed18.github.io/Talha-s-Portfolio/`.

It also works on Netlify, Vercel and Cloudflare Pages: drag and drop the folder or connect the repository.

## Customize

Everything is in `index.html`.

| What to change | Where to look |
| --- | --- |
| Colors and theme | The `:root` block at the top of the `<style>` section (CSS variables) |
| Profile photo | The `<img>` inside `id="avatar"`. Replace the `src` with your own image |
| About, Experience, Skills | The `id="profile"` panel |
| Websites and clients | The `id="websites"` panel |
| Portfolio cards | The `id="portfolio"` panel. Swap the text thumbnails for `<img>` tags to show real work |
| CV content | The `id="cv"` panel |
| Contact links | The header buttons and the sidebar `contact` section |

## Tech

- HTML5 and CSS3 (custom properties, grid, flexbox, media queries)
- Vanilla JavaScript for tabs and the theme toggle (about 25 lines)
- No frameworks, libraries or external requests

## Contact

- Email: talhasaeed.047.edu@gmail.com
- Phone: 03097101315
- Instagram: [@Talhasaeed005](https://instagram.com/Talhasaeed005)
- Website: [deltaservices.site](https://deltaservices.site)

## License

&copy; 2026 Muhammad Talha Saeed. All rights reserved. Please do not copy the personal content, photo or CV. If you want to reuse the layout, ask first or replace everything with your own information.
