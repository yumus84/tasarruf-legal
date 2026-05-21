# tasarruf-legal (GitHub Pages)

Nur Gizlilik Politikasi fuer Google Play.

## Play Console URL

Nach Deploy:

`https://DEIN-GITHUB-NAME.github.io/tasarruf-legal/gizlilik-politikasi.html`

## Repo auf GitHub anlegen (ohne gh CLI)

1. https://github.com/new — Name: `tasarruf-legal`, Public, ohne README
2. Im Projektordner PowerShell:

```powershell
cd C:\Users\Batu\Desktop\indirimler\publish\tasarruf-legal
git init
git add .
git commit -m "Gizlilik Politikasi"
git branch -M main
git remote add origin https://github.com/DEIN-NAME/tasarruf-legal.git
git push -u origin main
```

3. https://github.com/DEIN-NAME/tasarruf-legal/settings/pages  
   **Source:** GitHub Actions  
4. Unter Actions den Workflow **Deploy GitHub Pages** abwarten (gruen)

## Mit GitHub CLI

```powershell
cd C:\Users\Batu\Desktop\indirimler
powershell -File scripts\setup-github-pages-legal.ps1
```
