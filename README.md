# YOUR LAB NAME website

A static multi-page website designed for GitHub Pages.

## Publish with GitHub Pages

1. Create a GitHub repository. For the primary site under your account, name it `YOUR-GITHUB-USERNAME.github.io`.
2. Add the HTML files and the `assets/css/style.css` file exactly as shown in the file structure.
3. Commit and push the files to the `main` branch.
4. In the GitHub repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. After GitHub finishes deployment, your site will appear at the URL GitHub Pages provides.

## Customize before publishing

Search across the repository for these placeholders and replace them:

- `YOUR LAB NAME`
- `Dr. Your Name`
- `YOUR.EMAIL@ufl.edu`
- Placeholder publication records, news, people, biography, and mailing address

## Add photos

Place photos in `assets/images/`, then replace an avatar block such as:

```html
<div class="avatar">PI</div>
```

with:

```html
<img src="assets/images/pi-headshot.jpg" alt="Dr. Your Name" style="width:100%;height:200px;object-fit:cover;display:block;">
```

Use a descriptive `alt` value for every informative image.
