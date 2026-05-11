# Removing the GitHub Pages redirect

If `https://QuebecAI.github.io/proof-room/` redirects to `https://www.quebecartificialintelligence.com/proof-room/`, remove the custom domain from GitHub Pages.

## Safe rule

Delete only the GitHub repository file named `CNAME`. Do not change domain DNS, MX records, email settings, Squarespace settings, SPF, DKIM, or DMARC records.

## Steps

1. Open `QuebecAI / QuebecAI.github.io`.
2. Open the root file named `CNAME`.
3. Copy its content somewhere as a backup.
4. Delete the file.
5. Commit message: `Remove GitHub Pages custom domain redirect`.
6. Go to **Settings → Pages**.
7. Remove the custom domain if it still appears there.
8. Wait a few minutes and test: `https://QuebecAI.github.io/proof-room/`.
