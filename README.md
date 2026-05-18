# Dr. Dheeraj Bharti — GitHub Pages Academic Website

This is a static GitHub Pages starter website for a faculty/research-lab identity around:

- Robotic perception
- SLAM and 3D reconstruction
- GNSS-VIO and sensor fusion
- Embedded AI and edge perception
- Agriculture robotics
- Mining and industrial inspection

## Recommended repository name

For a personal GitHub Pages website, create a repository named:

```bash
<your-github-username>.github.io
```

Then upload all files from this folder to that repository.

## Quick deployment steps

```bash
git clone https://github.com/<your-github-username>/<your-github-username>.github.io.git
cd <your-github-username>.github.io
cp -r /path/to/dheeraj_githubio_site/* .
git add .
git commit -m "Initial academic website"
git push origin main
```

Then go to:

```text
https://<your-github-username>.github.io
```

If GitHub Pages does not activate automatically:

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/** root.
6. Save.

## First things to edit

### 1. Contact information
Edit `contact.html` and replace:

- Official IIT email once available
- Office number after joining
- Google Scholar link: https://scholar.google.com/citations?user=OvjT6EsAAAAJ&hl=en
- GitHub link: https://github.com/dheerajbharti
- ORCID link
- LinkedIn link

### 2. Footer links
Edit the footer in each `.html` file and replace the placeholder GitHub URL.

### 3. Publications
Edit `publications.html` and replace placeholder publication entries with final paper titles, venues, years, DOI, PDF, code, dataset, and BibTeX links.

### 4. Project images
Replace the placeholder SVG images in `assets/img/` with your own:

- Orchard point cloud screenshots
- Camera trajectory plots
- GNSS/SLAM evaluation plots
- Robot/sensor photos
- Jetson setup images

Use the same filenames if you want to avoid changing HTML paths.

### 5. Official IIT faculty profile
After your IIT(ISM) profile becomes active, add the official link in `contact.html` and optionally in the homepage footer.

## File structure

```text
.
├── index.html
├── research.html
├── projects.html
├── publications.html
├── teaching.html
├── students.html
├── contact.html
├── assets/
│   ├── css/styles.css
│   ├── js/main.js
│   └── img/
│       ├── logo.svg
│       ├── hero-pattern.svg
│       └── project-placeholder.svg
└── README.md
```

## Design philosophy

The official IIT faculty page should remain the institutional page. This GitHub.io site should be the richer research identity page: lab vision, project demos, student opportunities, teaching material, publications, and research narrative.


## Links added in this version

- Google Scholar: https://scholar.google.com/citations?user=OvjT6EsAAAAJ&hl=en
- GitHub: https://github.com/dheerajbharti
- Website: https://dheerajbharti.github.io
