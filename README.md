# Simple Static Site — Ákos Magyar

This folder contains a ready-to-publish static website.

## How to use (no coding needed)

1. **Put your PDFs** into the `files/` folder (CV, papers, notes, syllabi, etc.).  
2. **Edit `index.html` online** (with GitHub's editor) to update links/titles.
3. **Publish with GitHub Pages**:

   - Create a new GitHub repository (any name, e.g. `amagyar-website`).
   - Upload all files in this folder to that repository (drag-and-drop works).
   - Go to **Settings → Pages** in the repo.
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Select branch **main** and folder **/** (root). Save.
   - Wait ~30–90 seconds. Your site will appear at a URL like:  
     `https://<your-username>.github.io/<your-repo>/`

4. **(Optional) Add a custom domain** (e.g., `amagyar-math.com`):
   - Register the domain at your preferred registrar (Cloudflare Registrar often has at-cost pricing).
   - In your DNS, set:
     - `www` **CNAME** → `<your-username>.github.io`
     - Apex (root) **A** records → GitHub Pages IPs (see GitHub Docs for current values).
   - In your repo **Settings → Pages**, set **Custom domain** to your domain and enable **Enforce HTTPS**.
   - GitHub creates a `CNAME` file automatically once the custom domain is set.

## Editing text

Open `index.html` in any text editor or GitHub web editor. Look for the sections:
- **About**, **Research**, **Selected Papers**, **Notes**, **Teaching**, **CV**, **Contact**.

Replace placeholder titles and links like `files/magyar_discrete_spherical_maximal.pdf` with your actual filenames.

## Tips

- Keep filenames simple (no spaces), e.g. `magyar_2025_notes.pdf`.
- If you use subfolders under `files/`, make sure the links match (e.g. `files/papers/paper1.pdf`).

---

Generated on 2025-09-13.
