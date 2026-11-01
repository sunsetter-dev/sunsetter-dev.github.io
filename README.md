# Sunsetter showcase page

A static one-page site for applications and outreach. It contains no product code.

## Publish on GitHub Pages (free)

1. Open `index.html` and fill in the `CONFIG` block near the top:
   - `CONTACT_EMAIL`: where requests should go.
   - `WAITLIST_URL` (optional): a Tally or Google Form link. Without it, "Request access" opens an email.
   - `VIDEO_URL` (optional): an embed URL (YouTube `https://www.youtube.com/embed/<id>` or a Loom embed). The video section stays hidden until it is set.
2. In your GitHub organization, create a new **public** repo named `<org>.github.io`. Keep the product code in its own private repo in the same org.
3. Upload the contents of this folder (`index.html`, `assets/`, this README) to the repo's root.
4. In the repo, go to **Settings → Pages**, and set **Source: Deploy from a branch, Branch: `main`, folder `/ (root)`**.
5. After a minute the page is live at `https://<org>.github.io/`. A custom domain can be added under Settings → Pages.

The full setup (organization, private code repo, this page, GitHub App) is in `docs/github-setup.md` in the product repo.

## Updating numbers

Every figure on the page comes from `STATUS.md` and `docs/real-repos.md` in the product repo. Update the page when those change, especially after the first real GitHub App pull request lands.
