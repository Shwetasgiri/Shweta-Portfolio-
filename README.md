# Data Analyst Digital Résumé

A simple, responsive, multi-page portfolio made with HTML, CSS, and JavaScript. The homepage acts as a digital résumé. Each project opens a separate page with room for its problem statement, approach, tools, timeline, findings, GitHub repository, and result screenshots. No build step or package installation is needed.

## Personalize it before publishing

1. In `index.html` and the project pages, replace **Alex Morgan**, email, city, LinkedIn, GitHub profile, and résumé link with your details.
2. Edit the projects list in `index.html`. Update each title, short description, tools, and the link to its project page.
3. Edit `project-sales.html`, `project-churn.html`, and `project-student.html`. Replace every bracketed note with your own project details. Change each GitHub link to the matching repository.
4. To add a result screenshot, create an `assets/` folder and put your own image there. On the relevant detail page, replace the `.screenshot-guidance` element with:

   ```html
   <img class="project-shot" src="assets/my-result.png" alt="Describe what the screenshot shows">
   ```

   You can add multiple images by adding more `<img>` elements. Use only screenshots of your own results, and describe each image in its `alt` text.
5. Replace the internship, education, and skills with accurate details. Remove anything that does not apply.
6. Add your PDF résumé as `assets/resume.pdf`, or remove/change the résumé link.

The names, project descriptions, tools, dates, and experience currently shown are examples. Replace them with truthful details before sharing the site with employers.

## Preview

Open `index.html` in a browser. Project rows open the corresponding detail pages in the same tab.

## Host on GitHub Pages

1. Create a GitHub repository for the portfolio.
2. Put `index.html`, `style.css`, `script.js`, the three `project-*.html` files, and your optional `assets/` folder at the repository root.
3. Push the files to GitHub.
4. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select your main branch and the `/ (root)` folder, then save.
5. Once deployed, add the URL shown in Pages settings to your LinkedIn profile.
