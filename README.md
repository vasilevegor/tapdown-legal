# tapdown-legal

Static legal pages for the **TapDown** mobile game, hosted on GitHub Pages.

| Page | URL (after Pages is enabled) |
|------|------------------------------|
| Privacy Policy | https://vasilevegor.github.io/tapdown-legal/privacy.html |
| Terms of Service | https://vasilevegor.github.io/tapdown-legal/terms.html |
| Landing | https://vasilevegor.github.io/tapdown-legal/ |
| Support | mailto:vasilev.egor163@gmail.com |

## Publish (one-time)

```powershell
cd C:\Users\vasil\Documents\tapdown-legal
git init
git add .
git commit -m "Add privacy policy, terms, support landing"
git branch -M main
git remote add origin https://github.com/vasilevegor/tapdown-legal.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save**.
Pages goes live at the URLs above within ~1 minute.

## Updating later

Edit the `.html` files, then:

```powershell
git add . && git commit -m "Update legal pages" && git push
```

> If the app's display name changes from "TapDown", search-replace it across the `.html` files before publishing.
