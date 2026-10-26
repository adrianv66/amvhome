# amvhome.net

Landing page at https://www.amvhome.net, linking to the travel and tech sites. GitHub Pages, repo `adrianv66/amvhome`.

Everything you'd change is in `_config.yml`: `name`, `tagline`, `bio` (Markdown), `photo`, the `sites` on the shelf
(title, url, colour, blurb, optional small `label` at the foot of the spine) and the footer `links`.

## Setup

1. Create a public repo `amvhome` on github.com/adrianv66 and push this folder to `main`.
2. Repo **Settings → Pages**: Deploy from a branch, `main`, `/ (root)`. Custom domain shows `www.amvhome.net` (from `CNAME`).
3. GoDaddy DNS for amvhome.net:
   - Delete the `A` record `@` that says **Parked**.
   - Add four `A` records, name `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
   - Edit the `CNAME` named `www` so it points to `adrianv66.github.io`.
   - Leave the MX and TXT records (email) and the `travel` / `tech` CNAMEs alone.
4. When the DNS check is green, tick **Enforce HTTPS**. Both amvhome.net and www.amvhome.net then open this page.
