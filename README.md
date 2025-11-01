# Split Navigation (simple demo)

This is a very small static demo showing a split top navigation bar using only HTML and CSS.

Files
- `index.html` — single-page demo that contains the split navigation markup and styles.

Quick preview
- Open `index.html` in your browser (double-click or use `Start-Process` in PowerShell):

  ```powershell
  Start-Process -FilePath index.html
  ```

- Or serve the folder with a tiny HTTP server (if you have Python installed):

  ```powershell
  # from project root
  python -m http.server 8000
  # then open http://localhost:8000 in your browser
  ```

How to add this project to a GitHub repository (PowerShell)

1. Initialize a local git repo, add files and commit:

```powershell
cd "c:\Users\venka\OneDrive\Desktop\Websites-practices\splitNavigation"
git init
git add .
git commit -m "Initial commit: split navigation demo"
```

2. Create a remote repository on GitHub (web UI) and then add the remote and push:

```powershell
# replace <USERNAME> and <REPO> with your GitHub username and repo name
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git branch -M main
git push -u origin main
```

Optional: if you use the GitHub CLI (`gh`) you can create the remote from the command line:

```powershell
gh repo create <USERNAME>/<REPO> --public --source . --remote origin --push
```

.gitignore recommendations
- A minimal `.gitignore` is included with this project; adjust for your environment.

Suggested next steps
- Add a `LICENSE` file (MIT is common for small demos).
- Add a short `index.html` title and update `title`/`meta` information if you plan to publish.

Contact / Attribution
- Small personal demo — feel free to reuse and modify.

Enjoy!
