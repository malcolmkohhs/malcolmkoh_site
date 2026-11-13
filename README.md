# malcolmkoh.com — Version 2

A static personal academic/research website for Malcolm Koh.

## Files
- `index.html` — page content
- `styles.css` — visual design and responsive layout
- `script.js` — current year + subtle reveal animation

## Before publishing
1. Open `index.html` and replace `hello@malcolmkoh.com` if that alias is not active.
2. Add the publication/DOI link once you want it public.
3. Add GitHub only when you want to surface it.
4. Remove the small setup note in the Contact section once the email is final.

## Cloudflare Pages
### Option A — GitHub
1. Create a GitHub repository, e.g. `malcolmkoh.com`.
2. Upload these files to the repository root.
3. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository.
5. Framework preset: None.
6. Build command: leave blank.
7. Build output directory: `/`.
8. Deploy.
9. In the Pages project, add the custom domain `malcolmkoh.com`.

### Option B — Direct upload
Cloudflare Pages also supports direct upload of a static site. Upload the contents of this folder, then attach the custom domain.

No build step or package manager is required.
