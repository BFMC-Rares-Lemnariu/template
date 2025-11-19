# Academic Profile Website Template

A lightweight, self-contained HTML/CSS/JS template for academic staff pages, useful for ARACIS accreditation and transparency requirements

Designed for clarity, transparency, and ARACIS compatibility — simple to edit and host.

---

## Folder Structure

```
template/
│
├── index.html             # About page
├── research.html          # Research activity
├── teaching.html          # Teaching activity
├── publications.html      # Publications
├── phd_supervision.html   # PhD supervision
├── contact.html           # Contact and copyright info
│
└── assets/
    ├── header.html        # Shared header (photo, name, navigation)
    ├── footer.html        # Shared footer (copyright line)
    ├── style.css          # Unified academic design
    ├── script.js          # Header/footer loader, dark mode, scroll-to-top
    └── photo.jpg          # Profile photo placeholder
```


Each page contains clearly marked sections to edit:

## Copy the Template

Use the “Use this template” button on GitHub to create your own repository with this structure.

## Edit the Code 
### Option A: Edit Online
Go to Code → Codespaces → Create codespace
Edit files directly in the browser

### Option B: Edit Offline (Local PC)
Clone your repository
Edit files using any code editor
 
## Test Locally 

In the project folder, run:

```bash
python -m http.server 8000
```

Then in your browser go to:
***http://localhost:8000/***

## Check your changes in this local “staging” mode.

## Push Your Changes to GitHub

### Option A: Edit Online
Source Control → Commit → Add a comment → Sync

### Option B: Edit Offline (Local PC)
```bash
git add .
git commit -m "Update website"
git push
```

## Enable GitHub Pages

On your browser, Go to Repository → Settings → Pages

Under Build and deployment, set:
    Source: Deploy from a branch
    Branch: main
    Folder: / (root)
Click Save
Wait about 1–2 minutes, then refresh the page.

## Open Your Public Page

Go to ***https://GITUSER.github.io/GITREPO/***

## Important Notes

GitHub Pages requires a public repository (for free accounts).
Keep the folder structure unchanged — relative paths depend on it.
Profile photo should be ~300×300 px, JPG/PNG, under 200 KB.
To prevent indexing by search engines, add a robots.txt file:

```bash
User-agent: *
Disallow: /
```

GitHub Codespaces offers 15 hours/month for free.
A full video guide is available here: https://youtu.be/nYA1YGD5GWo

Template view here: https://bfmc-rares-lemnariu.github.io/template/

##  Credits

Template created for academic profiles at
Technical University of Cluj-Napoca — Department of Automation

© 2025 Technical University of Cluj-Napoca
Maintainer: [Rares Lemnariu](mailto:rares.popescu@campus.utcluj.ro)
