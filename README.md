# montveritas.com

Static one-page site for Montveritas. No framework, no build step — just open
`index.html` in a browser to preview, edit the text right in the file.

## Before going live — fill in these 2 placeholders

Both are marked with `TODO` comments in `index.html`:

1. **GitHub repo URL** — search `https://github.com/Montveritas-Partners/odoo-modules-core`, replace with the real
   link to the `odoo-modules-core` repo (the "View odoo-modules-core →" button).
2. **LinkedIn URL** — search `https://www.linkedin.com/in/holmes-michael/`, replace with your LinkedIn
   profile link.

Email (`michael@montveritas.com`) is already wired in.

## Editing

- All page text lives in `index.html`, in plain sentences between the tags.
- Colors / fonts / spacing live at the top of `style.css` (the `:root` block).
- The "Who you're working with" family/EU-US section is optional — delete that
  whole `<section>` in `index.html` to remove it.

## Hosting (GitHub Pages)

1. Push this folder to a GitHub repo.
2. Repo → **Settings → Pages** → Source: `main` branch, `/ (root)`.
3. Set the custom domain to `montveritas.com` (the `CNAME` file is already here).
4. Point DNS for `montveritas.com` at GitHub Pages (separate step, later).

Until DNS is configured the site is reachable at the
`https://<user>.github.io/<repo>/` URL Pages gives you.
