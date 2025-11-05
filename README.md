
# QueryChips – Landing Page (Vercel)

This is a simple static site for **QueryChips.com**. It’s ready to deploy to **Vercel** and uses a basic HTML/CSS landing page with an email signup form (via Formspree).

## Quick start

### 1) Prepare the repo
- Create a new GitHub repo (public or private), e.g. `querychips-site`.
- Add these files to the root: `index.html`, `README.md`, `vercel.json`, `favicon.ico`, and the `assets/` folder.
- Commit & push.

### 2) Deploy on Vercel
- Sign in at https://vercel.com with your GitHub account.
- Click **New Project → Import** your `querychips-site` repo.
- Keep defaults and **Deploy**.
- You’ll get a URL like `https://querychips.vercel.app`.

### 3) Connect your domain (querychips.com)
- In the Vercel dashboard, go to your project → **Settings → Domains** → Add `querychips.com`.
- Follow Vercel’s DNS instructions:
  - If Vercel is your DNS: click “Add” and you’re done.
  - If your registrar manages DNS: create a **CNAME** from `www` → `cname.vercel-dns.com` and set a redirect/apex record to `www`. Vercel provides exact instructions.
- Wait a few minutes for SSL to be issued automatically.

### 4) Enable the email form
- Create a free Formspree form at https://formspree.io (no code).
- Replace `yourformid` in `index.html` with your actual Formspree endpoint ID.

### 5) Make changes
- Edit `index.html` or assets locally.
- Push to GitHub → Vercel auto‑deploys a new version.
- Rollback anytime from the Vercel dashboard if needed.

## Files
- `index.html` — the landing page.
- `assets/logo.svg` — simple gradient logo.
- `favicon.ico` — generated icon.
- `vercel.json` — optional headers (cache) for static assets.
- `README.md` — this guide.

## Optional
- Replace the logo and colors to match your visual identity.
- Add analytics (Vercel Analytics or Plausible/GA).
- Swap Formspree for Mailchimp/Beehiiv if you prefer.

---

Questions? hello@querychips.com
