# HBJLabs website

Plain HTML pages (no build step): the home page, one privacy notice per app
(the links Google Play asks for) and a 404 page. Light and dark mode follow
the phone. Pages were generated once; edit the HTML directly from now on.

Placeholders to change when the details are known (search for them):
- `info@hbjlabs.co.za` (the contact email, used on every page)
- Registration number 2026/855949/07 (CIPC enterprise number K2026855949) is in every footer and notice
- "Coming soon to Google Play" (put the Play links once the apps are live)

## Hosting (GitHub Pages, free)
1. On GitHub create a **public** repository `hbjlabs-website` (no README).
2. Copy the contents of this folder into it (or let Claude do it once the
   repository exists), then Settings → Pages → Source: "Deploy from a branch",
   branch `main`, folder `/ (root)`.
3. The site appears at `https://henryjordaan8-arch.github.io/hbjlabs-website/`.
4. Own domain (e.g. hbjlabs.co.za): Settings → Pages → Custom domain, and at
   the domain seller add the DNS records GitHub shows (A records for the bare
   domain, CNAME `www` → `henryjordaan8-arch.github.io`). Tick "Enforce HTTPS".

Privacy links for the Play Console:
- WardCalc: `/privacy/wardcalc.html`
- WardBoard: `/privacy/wardboard.html`
- LabScan: `/privacy/labscan.html`
