# Royal and Co website

Static site (no build step). Files: `index.html`, `CNAME`, `robots.txt`, `sitemap.xml`.

## Deploy on GitHub Pages
1. Create a repo, push these files to the `main` branch root.
2. Repo Settings > Pages > Deploy from branch > `main` / root.
3. In Pages settings, set custom domain to `royalandco.site` and tick Enforce HTTPS once available.

## DNS (at your domain registrar)
- `A` records for `@` pointing to: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` for `www` pointing to `<your-github-username>.github.io`
- Propagation can take from minutes to a few hours.

## Adding real clients
Edit the `CLIENTS` array near the bottom of `index.html`. Add only clients who have agreed to be named. The section stays hidden while the list is empty.

## Before going live
- Add company registration details (CIN/LLPIN, GSTIN) to the footer once you have them.
- Only keep technologies and services in the lists that you can actually deliver.
- Set up email hosting for the domain so hr.ops@royalandco.site can receive mail, and consider a separate contact@ address for sales enquiries.
