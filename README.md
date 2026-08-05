bettscm.github.io

Personal site. Live at https://bettscm.github.io

Single HTML file. No framework, no build step, no dependencies. CSS and JavaScript are inline in index.html. Hosted on GitHub Pages, deployed on push to main.

Structure

index.html The whole site. Tabbed panels for about, projects, research, resume, and contact. Styles in a single style block, tab logic in a single script block at the bottom.

images/ Project and profile images. Sized to a 900px long edge and compressed, since these load on the page.

resume.pdf Linked from the header and the resume panel.

.nojekyll Empty file that tells GitHub Pages to skip Jekyll processing. The site is static HTML and does not need it.

Editing

Open index.html in any editor and open it in a browser to preview. There is nothing to install and nothing to compile.

New images go in images/ and are referenced as images/filename. Keep them under a few hundred KB and give every one real alt text.

Push to main and the deployment runs automatically. Hard refresh after, since browsers cache the page aggressively.
