# Is Durga Parsai in Jail?

A minimalist single-page website.

## Deploy to GitHub Pages

1. Create a new repository on GitHub.
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your repository.
4. Under **Source**, select **main** branch and **/ (root)** folder, then click **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Changing the Answer

Open `index.html` and change the value of `ANSWER` near the bottom of the file:

```js
const ANSWER = "No";   // Change to "Yes" or "No"
```
