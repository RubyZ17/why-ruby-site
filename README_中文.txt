Why Ruby? — Website package

FILES
- index.html: the website homepage
- assets/: optimized images used by the page
- .nojekyll: lets GitHub Pages serve the files as-is

FASTEST PUBLISH METHOD: GitHub Pages
1. Sign in to https://github.com/ and create a new repository named why-ruby-site.
2. Choose Public only if you are comfortable with the site being visible to anyone. GitHub Pages websites are public.
3. In the repository, choose Add file -> Upload files. Upload index.html, .nojekyll, and the assets folder (all files inside it).
4. Click Commit changes.
5. Open Settings -> Pages. Under Build and deployment, choose Deploy from a branch; select main and /(root); Save.
6. Wait a few minutes, then visit the URL shown in Settings -> Pages. It usually looks like https://YOUR-USERNAME.github.io/why-ruby-site/

EDIT LATER
- Open index.html in the repository and click the pencil icon to edit text, then Commit changes.
- For larger design changes, download the files, edit index.html in VS Code or another editor, and upload the updated files.
- Image files live in assets/. Keep the filenames the same unless you also update the image paths in index.html.

PRIVACY
This is a static website. Once published, anyone with the URL can access it. Remove any personal details you do not want public before publishing.
