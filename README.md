# mcgowan.com — static site

A plain HTML/CSS rebuild of the Google Sites page that was hosted under the `tcd.ie` account.
No build step, no dependencies. Three files do the whole job:

```
index.html      Home
research.html   Research
style.css       All styling
assets/         Put portrait.jpg and cv.pdf here
```

---

## Publish it on GitHub Pages

1. **Create a GitHub account** at github.com if you don't have one. Use a personal email
   address you'll keep — not an institutional one. That's the whole point of this move.

2. **Create a new repository.** Click **+** → **New repository**.
   - If you want the address `yourusername.github.io`, name the repo exactly that.
   - If you're pointing your own domain at it (see below), any name works — `website` is fine.
   - Set it to **Public**. Private repos can't use free Pages.
   - Don't tick "Add a README" — you're uploading one.

3. **Upload the files.** On the empty repo page, click **uploading an existing file**.
   Drag in `index.html`, `research.html`, `style.css`, `README.md`, and the `assets` folder.
   Click **Commit changes**.

4. **Turn on Pages.** Repo → **Settings** → **Pages** (left sidebar).
   Under *Source* choose **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.

5. Wait a minute or two, then reload the Settings → Pages screen. It shows your live URL.

Any later edit — click a file, the pencil icon, edit, commit — republishes within a minute.

---

## Before you announce the new address

**The portrait.** The photo on the old site is served from Google's servers and is tied to
the Google Site itself. Save a copy while the old page is still up (right-click → Save image),
name it `portrait.jpg`, and put it in `assets/`. If the file isn't there, the page simply
drops the photo rather than showing a broken image, so nothing looks wrong in the meantime.

**The CV.** The site links to a Google Drive file. Open that link in a private browsing
window — if it doesn't load, the file lives in the lost `tcd.ie` Drive and the link is dead
for everyone. Better long term: put `cv.pdf` in `assets/` and change the three CV links to
`assets/cv.pdf`. Then it's never anyone else's to take away.

**The Drive folder embed.** The old home page embedded a Drive folder listing. I've left it
out, since it almost certainly points at the same inaccessible account. Tell me what was in
it and I'll add the contents properly.

**Publications.** The Research page lists the two papers that were on the old site, both
from 2023. If you've published since, send me the titles and journals and I'll add them.

---

## About the domain

The old site was *titled* `mcgowan.com` but lived at a `sites.google.com` address. Two cases:

- **You own mcgowan.com.** Log in to the registrar, point it at GitHub Pages, then add the
  domain under Settings → Pages → Custom domain. GitHub's instructions for the exact DNS
  records are at docs.github.com → Pages → Configuring a custom domain.
- **You don't.** Then `yourusername.github.io` is your address. Registering `mcgowan.com`
  or similar is roughly €10–15/year if you want it, and you can add it later without redoing
  anything.

---

## Worth trying in parallel

Ask Trinity IT whether the `tcd.ie` account still exists in a suspended state. If it does,
an administrator can often transfer ownership of a Google Site to another account, or at
least re-export the Drive files. Accounts are usually purgeable after a set period, so this
is worth an email sooner rather than later — but don't wait on it, since the site above
already stands on its own.
