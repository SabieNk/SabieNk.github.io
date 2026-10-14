# SabeloNkosi3D

Portfolio site for **Sabelo Nkosi**, a 3D artist making product animation and CGI in Blender for tech and consumer products. Based in South Africa, working with clients in Johannesburg and Cape Town.

**Live site:** https://sabienk.github.io
**Contact:** [mr.s.nkosi.1999@gmail.com](mailto:mr.s.nkosi.1999@gmail.com)

## Work

| Project | Description | Shots |
| --- | --- | --- |
| Red espresso machine | Modelled in Blender from the Swan SEM8B, a retro-styled home espresso machine with a steel band, pressure gauge and steam wand. | 4 stills |
| JBL Authentic speaker | A black and gold smart speaker with a leather-grain body, treble and bass dials and a side woofer. | 5 stills |
| Teenage Engineering TP-7 | A field recorder with a round reel, a small display and transport buttons. | 3 stills |

All renders were made in Blender.

## About the site

The whole site is a single static file, `index.html`, with the CSS, JavaScript and images embedded in it. There is no build step and nothing to install.

- Hero reel that cycles through the featured projects
- Project sections coloured from each project's own renders
- Full-screen image viewer with keyboard arrows and Esc
- Responsive layout, with light and dark theme support
- Respects reduced-motion settings
- Font: [Archivo](https://fonts.google.com/specimen/Archivo) via Google Fonts

## Run it locally

Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/SabieNk/SabieNk.github.io.git
cd SabieNk.github.io
open index.html   # macOS; on Windows use: start index.html
```

## Deploy with GitHub Pages

1. Keep `index.html` in the root of the repository.
2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute or two the site is live at https://sabienk.github.io. Because the repo is named `SabieNk.github.io`, GitHub serves it from the root of that address.

To use your own domain, add it under **Settings → Pages → Custom domain** and set the DNS records GitHub shows you at your registrar.

## Editing the site

- **Text and layout:** edit the HTML and CSS in `index.html`.
- **Images:** they are embedded as base64 inside `index.html`. To swap one, replace its `data:image/jpeg;base64,...` string, or move the images into an `images/` folder and point each `<img src>` at the file.

## Copyright and trademarks

All renders and site content are © 2026 Sabelo Nkosi, all rights reserved. Please don't reuse the images without permission.

JBL, Teenage Engineering and Swan are trademarks of their respective owners. The renders are independent 3D work and are not affiliated with or endorsed by those companies.
