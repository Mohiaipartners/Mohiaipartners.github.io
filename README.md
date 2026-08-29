# Mohi AI Partners — Website

A free, static website for Mohi AI Partners, ready to publish on GitHub Pages.

## Publish it for free (GitHub Pages)

1. Go to github.com and create a free account if you don't have one.
2. Click "New repository." Name it anything (e.g. `mohi-ai-partners`). Make it **Public**.
3. Upload these files: drag `index.html`, the `blog/` folder, and this `README.md` into the repo using GitHub's "Add file → Upload files" button, then commit.
4. In the repo, go to **Settings → Pages**.
5. Under "Build and deployment," set Source to **Deploy from a branch**, Branch to **main** (or `master`), folder `/ (root)`, then Save.
6. Wait 1–2 minutes. GitHub will give you a live URL like `https://yourusername.github.io/mohi-ai-partners/`.

That's it — no cost, no server to manage.

## Adding a new blog post later

1. In the `blog/` folder, copy `post-template.html` and rename it, e.g. `post-2.html`.
2. Open your new file and edit the parts marked `CHANGE THIS:` — title, date, headline, and body text.
3. Open `blog/index.html` and copy one `<a class="post-card">` block (there's a commented example showing the format), paste it into the `post-list` section, and update the link, date, title, and preview text. Add newest posts at the top.
4. Commit/upload the changed files back to GitHub — the site updates automatically within a minute or two.

## Adding payments / paid booking later

GitHub Pages hosts static files only, so payments run through a third-party link embedded in the site:

- **Stripe Payment Links** (stripe.com) — create a link for a paid service or package, then swap the "Book a Free Consult" button's link in `index.html` (or add a second button) to point to it.
- **Calendly** (calendly.com) — free booking pages, with paid Calendly plans supporting Stripe checkout for paid consults.
- **PayPal.me** — simplest option for one-off payment links.

## Notes

- The "Book a Free Consult" button currently opens an email draft to mohimaryam@gmail.com. Replace the `mailto:` link in `index.html` with a Calendly or Stripe link whenever you're ready.
- The Facebook footer link is a placeholder (`href="#"`) — update it with the real Mohi AI Partners Page URL once you have the public link.
