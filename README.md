# Malcolm Koh — Personal Site

A simple static personal/research website for malcolmkoh.com.

## Files
- `index.html` — page content
- `styles.css` — layout and visual design
- `script.js` — tiny script for the footer year

## Before publishing
1. Replace `hello@malcolmkoh.com` in `index.html` if you do not use that email alias.
2. Add your GitHub, CV, ORCID, or publication links when ready.
3. Optionally add a PDF CV and link it from the navigation.

## Deploy on Cloudflare Pages

### Simplest route: GitHub
1. Create a new GitHub repository, e.g. `malcolmkoh-site`.
2. Upload these files to the repository root.
3. In Cloudflare, go to **Workers & Pages → Create → Pages → Connect to Git**.
4. Choose the repository.
5. Because this is a static site, use no build command. Set the output directory to `/` if Cloudflare asks.
6. Deploy.
7. In the Pages project, open **Custom domains** and add `malcolmkoh.com`.

Cloudflare will guide the DNS setup because your domain is already on Cloudflare.

## Good next upgrades
- `/cv` page or downloadable CV
- `/research` page with publication DOI/link
- `/projects` page for technical work
- GitHub + ORCID links
- small `now` page showing what you are currently learning or building
