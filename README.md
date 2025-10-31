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

```html
<!-- START EDITING BELOW -->
   ...content...
<!-- STOP EDITING ABOVE -->
```

 Only edit between these markers.

 
## How to Test Locally

Browsers block local includes (fetch()),
so you must view the site through a local server, not by double-clicking the HTML file.

Using Python

Open a terminal or PowerShell in the project folder.

Run:

```bash
python -m http.server 8000
```

On browser go to ***http://localhost:8000/***

## How to put it online

### Step 1 - push your code into a new repo

### Step 2 - Enable GitHub Pages

Go to your repository → Settings → Pages

Under Build and deployment, choose: 
- Source → Deploy from a branch
- Branch → main
- Folder → / (root)
- Click Save

Wait about 1–2 minutes, then refresh the page.

Go to ***https://USERNAME.github.io/academic-profile/***

## Important Notes

GitHub Pages requires the repository to be public (for free accounts).
Private repositories disable Pages unless you have a paid plan.

Always keep the folder structure identical — relative paths must stay the same.

Profile photos should be around 300 × 300 px, JPG or PNG, under 200 KB.

To prevent your page from appearing in search engines, create a robots.txt file:

```bash
User-agent: *
Disallow: /
```

##  Credits

Template created for academic profiles at
Technical University of Cluj-Napoca — Department of Automation

© 2025 Technical University of Cluj-Napoca
Maintainer: [Rares Lemnariu](mailto:rares.popescu@campus.utcluj.ro)