
BrainDump Site
==============

What this is
------------
- A super simple website with 3 pages:
  - `index.html` (landing)
  - `privacy.html` (privacy policy)
  - `terms.html` (terms of service)

Fastest way to put it live
--------------------------
Option A: Vercel (very easy)
1) Go to vercel.com and log in with GitHub.
2) Click New Project → Import this folder as a new repo, or upload directly.
3) Framework: “Other”. Click Deploy.
4) In Project → Settings → Domains → Add `braindumpapp.org` and `www.braindumpapp.org`.
5) At your domain registrar (where you bought the domain), set DNS:
   - A record: host `@` → `76.76.21.21`
   - CNAME: host `www` → `cname.vercel-dns.com`
6) Back in Vercel, set your preferred primary domain and enable redirect from the other. HTTPS is automatic.

Option B: Netlify (also easy)
1) app.netlify.com → New site from Git → pick the repo with `site/` as root, or drag-and-drop this folder.
2) In Domain settings, add `braindumpapp.org` and follow Netlify DNS or custom DNS instructions shown.

Where to update links
---------------------
- Update the App Store / Play links in `index.html` when your apps are live.
- Support email is `support@braindumpapp.org` (change if needed).

FAQ
---
Q: Do I need my own site for Supabase to work?
A: No. Supabase works with its own hosted domain (`*.supabase.co`). Your site is for App Store review, legal pages, brand presence, and future marketing.


