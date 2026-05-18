# Aayush Sahu — Portfolio

Cinematic dark-luxury personal portfolio. Two files, zero dependencies, instant deploy.

## 📁 Files
```
portfolio/
├── index.html          # Full portfolio (HTML + CSS + JS)
└── Aayush_Sahu_CV.pdf  # Resume — linked for download in the site
```

> ⚠️ Both files must be in the **same folder** for the resume download to work.

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `portfolio`)
2. Upload **both** `index.html` AND `Aayush_Sahu_CV.pdf` to the root
3. Go to **Settings → Pages → Source → main / root**
4. Your site is live at `https://yourusername.github.io/portfolio`

## 🚀 Deploy to Vercel (faster)

Drag the entire folder (with both files) into vercel.com/new — done.

Or via CLI:
```bash
npx vercel --prod
```

## ✏️ How the resume download works

The hero "Resume" button and the Resume section "Download Resume (PDF)" button
both use:
```html
<a href="Aayush_Sahu_CV.pdf" download="Aayush_Sahu_CV.pdf">
```
This is a relative path — it looks for the PDF in the same directory as `index.html`.
As long as both files are together, it works on any host.
