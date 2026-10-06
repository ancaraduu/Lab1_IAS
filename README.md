# Anca Radu — Personal Website

A responsive static personal website ready for GitHub Pages.

## Preview locally

Open `index.html` in a browser, or run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a public GitHub repository named `Lab1_IAS`.
2. From this directory, run:

   ```powershell
   git init
   git add .
   git commit -m "Create personal website"
   git branch -M main
   git remote add origin https://github.com/ancaraduu/Lab1_IAS.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

The site will be available at `https://ancaraduu.github.io/Lab1_IAS/` after GitHub finishes deploying it.
