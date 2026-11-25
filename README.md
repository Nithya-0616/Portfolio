# Nithya Sreenath · Portfolio

Static portfolio site (plain HTML, CSS and JavaScript, no build step).

## Deploy on Vercel
1. Push this folder to a GitHub repository (for example `Nithya-0616/portfolio`).
2. In Vercel, choose **Add New → Project**, import the repository and keep the defaults
   (Framework preset: **Other**, no build command, output directory: root).
3. After the first deploy, replace `REPLACE-ME.vercel.app` in `index.html`, the project pages,
   `robots.txt` and `sitemap.xml` with the real address (search and replace across the folder).

## Structure
- `index.html`: home page
- `projects/<name>/index.html`: one case study per project (served as `/projects/<name>`)
- `assets/img`: dashboard screenshots and diagrams
- `assets/docs`: Premier Club SRS and BRD
- `resume/`: Data Analyst and Business Analyst resumes (replace these PDFs to update them)
