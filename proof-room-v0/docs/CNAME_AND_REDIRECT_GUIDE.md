# CNAME and redirect guide

If `https://QuebecAI.github.io/proof-room/` redirects to `https://www.quebecartificialintelligence.com/proof-room/`, the GitHub Pages repo likely has a root `CNAME` file or a Pages custom domain set.

To stop the redirect:

1. Delete the root `CNAME` file in `QuebecAI.github.io`.
2. Go to **Settings → Pages → Custom domain**.
3. Remove `quebecartificialintelligence.com`.
4. Do not edit DNS records.
5. Do not edit MX records.
6. Do not edit email records.

Removing the GitHub repository `CNAME` file affects GitHub Pages custom-domain behavior, not email routing. Email is controlled by DNS email records such as MX, SPF, DKIM, and DMARC.
