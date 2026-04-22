# Matale Peter Molepo — Portfolio

Animated single-page portfolio. All content lives in **one file**.

---

## 📁 File Structure

```
portfolio/
├── index.html            ← The animated site (don't edit this)
├── portfolio-data.json   ← YOUR CONTENT — edit this to update the site
└── netlify.toml          ← Netlify config (caching headers)
```

---

## ✏️ How to Update Your Portfolio

1. Open `portfolio-data.json` in any text editor (VS Code recommended)
2. Edit whatever you need — new job, new project, new skill, etc.
3. Save the file
4. Commit and push to GitHub
5. Netlify auto-deploys — your site updates in ~30 seconds

---

## 🔑 Key Sections in `portfolio-data.json`

| Section | What to edit |
|---|---|
| `meta` | Your name, title, subtitle, availability status |
| `contact` | Email, phone, GitHub, LinkedIn, location |
| `stats` | The 3 stats shown on the hero card |
| `skills` | Skill names and percentage (0–100) |
| `chips` | All the tech badges in the stack cloud |
| `marquee` | Company/org names in the scrolling ticker |
| `experience` | Work history — jobs, bullets, dates, chips |
| `projects` | Projects — emoji, name, description, tags, optional link |
| `datascience` | Data science cards with tools |
| `education` | Degrees, modules, scores |
| `languages` | Spoken languages |

---

## 🚀 Deploy to Netlify (First Time)

1. Push this folder to a GitHub repo
2. Log in to [netlify.com](https://netlify.com)
3. Click **Add new site → Import from Git**
4. Select your repo
5. Build settings: leave everything blank (no build command needed)
6. Click **Deploy site**

Done. Every `git push` after that auto-deploys.

---

## 💡 Tips

- To add a **new job**: copy an existing block inside `"experience": [...]` and edit it
- To add a **new project**: copy a block inside `"projects": [...]` — add a `"link"` URL to show a button
- To add your **LinkedIn**: fill in the `"linkedin"` field in `contact`
- To mark yourself as **unavailable**: set `"available": false` in `meta`
- **Don't rename** `portfolio-data.json` — the site looks for that exact filename
