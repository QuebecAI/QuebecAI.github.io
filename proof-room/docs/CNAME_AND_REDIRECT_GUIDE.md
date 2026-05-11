# CNAME and redirect guide

If `https://QuebecAI.github.io/proof-room/` redirects to a custom domain, remove the custom domain from the GitHub Pages repository.

Do this in GitHub:

1. Delete the root `CNAME` file if it contains `quebecartificialintelligence.com`.
2. Go to **Settings → Pages**.
3. Remove the custom domain from the Custom domain field.
4. Do not change DNS, MX, SPF, DKIM, or DMARC records.

Deleting a GitHub repository `CNAME` file is not the same thing as changing email DNS records.
