# Bozy Bonifacio Public Profile

This is a single-file static site prepared for GitHub Pages.

## Files
- `index.html` — the whole public profile site

## Publish to GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Commit and push.
4. In GitHub, open **Settings > Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`), folder `/root`
6. Save.
7. Your site will be published at `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Customization
Edit the following in `index.html`:
- name and headline
- about section
- contact links
- focus areas
- chatbot knowledge block in the `<script>` section

## Note about the chatbot
The included bot is fully static and runs in the browser. It does not use an AI model.

If you want a real AI chatbot:
- keep this page on GitHub Pages
- add a serverless backend for model calls
- keep your API key on the backend, not in the page
