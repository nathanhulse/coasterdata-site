# CoasterData Website

App landing page, privacy policy, and support page for CoasterData.

## Deploy to GitHub Pages (free)

1. Create a new GitHub repo called `coasterdata-site` (or any name)
2. Push these files to the `main` branch
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch** → `main` → `/ (root)` → Save
5. Your site is live at `https://yourusername.github.io/coasterdata-site/`

## Custom domain (coasterdata.app)

If you own `coasterdata.app`:

1. In the repo's **Settings → Pages → Custom domain**, enter `coasterdata.app`
2. The `CNAME` file in this repo is already set
3. At your domain registrar, add these DNS records:
   - **A records** (all four, for apex domain):
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME record** (for www subdomain):
     - `www` → `yourusername.github.io`
4. Wait ~10 minutes for DNS propagation
5. Back in GitHub Pages settings, check **Enforce HTTPS**

## Pages

- `index.html` — Landing page (link from App Store "Marketing URL")
- `privacy.html` — Privacy policy (link from App Store Connect "Privacy Policy URL")
- `support.html` — Support / FAQ (link from App Store Connect "Support URL")

## App Store Connect URLs

When submitting, use:
- **Privacy Policy URL:** `https://coasterdata.app/privacy.html`
- **Support URL:** `https://coasterdata.app/support.html`
- **Marketing URL:** `https://coasterdata.app`
