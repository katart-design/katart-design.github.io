KATART PORTFOLIO — QUICK START

Files:
- index.html: the website content
- style.css: colors, layout, fonts, responsive design
- assets/: put your artwork images here

UPLOAD TO GITHUB PAGES:
1. Create a public GitHub repository named exactly: YOUR-GITHUB-USERNAME.github.io
2. Upload index.html, style.css, and the assets folder contents to the repository root (not inside an extra nested folder).
3. Open repository Settings > Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Choose branch main and folder /(root), then Save.
6. Wait a few minutes and visit https://YOUR-GITHUB-USERNAME.github.io

ADD YOUR ART:
- Export web-ready JPG or WebP images (roughly 1600–2200 px on the long edge; compress large files).
- Upload to assets/ with these names: project-01.jpg, project-02.jpg ... project-06.jpg.
- The gallery will show each matching file. For other names, edit the image src values in index.html.
- To add a new project, copy one <article class="project-card"> block and change the image filename, title, and category.

EDIT BEFORE LAUNCH:
- Replace YOUR-EMAIL@example.com in index.html.
- Edit the About text to reflect your real experience and services.
- Replace the featured placeholder shapes with a real featured image if desired.
- Do not upload client work, private work, or high-resolution originals unless you have permission.

CUSTOM DOMAIN:
1. Buy a domain from a registrar, checking both first-year and renewal price.
2. In GitHub repository Settings > Pages, enter the domain under Custom domain and save.
3. At your registrar, add the DNS records shown in GitHub's official documentation for the domain type you use. For www, this is usually a CNAME to YOUR-GITHUB-USERNAME.github.io.
4. Wait for DNS to propagate, then enable Enforce HTTPS in Settings > Pages when available.
