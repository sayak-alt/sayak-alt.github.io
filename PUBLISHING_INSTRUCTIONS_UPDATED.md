# How to publish the multi-page site

## Files to upload
Upload these files to the root of your GitHub repository:
- index_final.html
- research_highlights.html
- experience.html
- publications.html
- contact.html
- site.css
- CV_sayak_chatterjee.pdf
- profile.jpg (optional)

## Important rename step
GitHub Pages expects the home page to be named `index.html`.
So after downloading the files, rename:
- `index_final.html` → `index.html`

Do not rename the other files.

## GitHub Pages steps
1. Create a GitHub repository. For a personal site, use `yourusername.github.io`.
2. Upload all files listed above to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**.
6. Save.
7. Wait 1–3 minutes. Your site will appear at `https://yourusername.github.io/`.

## Before going live
- Replace placeholder Google Scholar, ORCID, and GitHub links in all pages.
- Upload your CV as `CV_sayak_chatterjee.pdf`.
- Upload a portrait photo as `profile.jpg` if you want the image instead of the SC initials.
- If you want a custom domain later, add it in **Settings → Pages**.

## Optional cleanup
If you only want the new site live, keep only the new HTML files and `site.css` in the repository and remove the older draft files.
