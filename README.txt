MANOJ KUMAR DEEVI — PORTFOLIO WEBSITE

FILES INCLUDED
1. index.html  - Main portfolio website.
2. resume.pdf  - Your uploaded resume, connected to every Download Resume button.
3. README.txt  - Setup and deployment instructions.

LOCAL PREVIEW
1. Keep all three files in the same folder.
2. Double-click index.html to open the portfolio in your browser.
3. Click any Download Resume button. The browser should download resume.pdf.

GITHUB + VERCEL DEPLOYMENT
1. Open your GitHub portfolio repository.
2. Upload index.html, resume.pdf and README.txt to the repository root (same level).
3. If GitHub asks whether to replace index.html, choose the option to replace/commit the updated file.
4. Commit the changes to your main branch.
5. Open your Vercel project. It should automatically start a new deployment from GitHub.
6. After deployment succeeds, open the live website and test all Download Resume buttons.
7. Also test the direct file URL: https://YOUR-DOMAIN/resume.pdf

IMPORTANT
- Do not put resume.pdf inside a separate folder. It must sit beside index.html because the download link uses the relative path "resume.pdf".
- Upload the actual PDF file; do not rename it unless you also update the href in index.html.
- The contact form opens the visitor's email application with a pre-filled message. It does not submit to a server.
- Replace YOUR-DOMAIN in the test URL with your actual Vercel domain.

DESIGN / CONTENT
The website uses a responsive dark navy, blue and cyan design with Home, About, Expertise, Experience, Projects and Contact sections. It is a static HTML/CSS/JavaScript website and does not require a build command.
