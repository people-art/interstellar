# Interstella Project

A research initiative exploring AGI emergence through token cosmos traversals in LLMs, inspired by *Interstellar*. This Jekyll site serves as the project hub for research, demos, and paper.

## Features
- Sci-fi themed design with dark mode, starry animations, and responsive layout.
- Pages: Home, Research, Demonstrations, Paper, Blog, About.
- MathJax for LaTeX rendering.
- Bootstrap 5 for UI, Plotly for interactive demos.
- SEO optimized with sitemap and meta tags.

## Local Setup
1. Install Jekyll and Bundler:
   ```
   gem install bundler jekyll
   ```
2. Install dependencies:
   ```
   bundle install
   ```
3. Run locally:
   ```
   bundle exec jekyll serve
   ```
   View at `http://127.0.0.1:4000/`

## Deployment to GitHub Pages with Custom Domain
1. Create a new repository on GitHub: `interstella-project` (public).
2. Clone it locally and copy all files from this directory (including `.github/workflows/deploy.yml` for auto-deployment).
3. Commit and push to the `main` branch.
4. GitHub Actions will automatically build and deploy to the `gh-pages` branch on push to `main`.
5. In repo settings > Pages:
   - Set source to "GitHub Actions" (it will use the workflow).
   - Under "Custom domain", enter `interstella.ai-avtar.org` and save.
   - GitHub will create a CNAME record; verify it.
6. Site will be live at `https://interstella.ai-avtar.org`.

### Custom Domain DNS Setup
Configure your DNS provider for `interstella.ai-avtar.org`:
- **A Records** (recommended for apex domain):
  - Point to GitHub's IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- **CNAME Record** (for www subdomain):
  - `www` → `username.github.io.` (replace `username`)
- Enable "Enforce HTTPS" in Pages settings after DNS propagates (may take up to 24 hours).
- The `CNAME` file in the repo root handles the domain mapping.

## Adding Content
- **Blog Posts**: Add Markdown files to `_posts/` with front matter (YYYY-MM-DD-title.md).
- **Demos**: Add to `_demos/` for collection pages.
- **Assets**: Place images in `assets/images/`, PDFs in `assets/papers/`.
- Update `_config.yml` for Google Analytics ID, etc.

## License
MIT License - see [LICENSE](LICENSE) file.

## Contact
jerry zhang - jerry.zhang.bill@gmail.com

---

*Built with Jekyll and hosted on GitHub Pages.* 
