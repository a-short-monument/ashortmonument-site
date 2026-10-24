# AShortMonument.com

Static site for *A Short Monument To Stupidity*, served by GitHub Pages from this repo (branch `main`, root).
Every push to `main` publishes within a minute or two. No build step.

## Files
- `index.html` – the coming-soon page. **All switches live in the `window.SITE` block near the top.**
- `assets/site.css` – look: paper `#F4ECDC`, ink `#2B2621`, saffron `#E07A1F`, Patrick Hand (self-hosted).
- `assets/seal.svg` – the final main seal (Besley Bold, Min's art; logo part 6), in page ink on a clear background. Rebuild from `claude/logo/build_part6.py`.
- `assets/favicon.svg` – browser-tab icon: the seal's ring and horse only (the full seal blurs at 16 px).
- `assets/launch-video.mp4` – v13 square video (swap for v14 when it shows AShortMonument.com).
- `assets/poster.jpg` – video poster and link-preview image.
- `CNAME` – the custom domain. Don't delete it.
- `404.html` – lost-visitor page.

## Road updates (one short phone request each)
- **Patreon opens:** set `patreonOpen: true` and `patreonUrl` to the page's address.
- **Kit sign-up live:** set `kitFormId` to the form number from Kit (Forms → the form → the number in its URL).
- **Mailbox live:** set `email: "rider@ashortmonument.com"`.
- **New video:** replace `assets/launch-video.mp4` (and `poster.jpg` if the first frame changed).

## House rules for anything posted here (field manual, rule 8)
Show a place only after leaving it. No live location, no tonight's stop or tomorrow's route.
Route maps show only what's already ridden. Ask before photographing people; no staged danger.
Horse voice: the horse is the wise one; the rider is the fool.
