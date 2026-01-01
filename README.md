# BRAINTWIN Project Website

Official website for the BRAINTWIN (Brain Research through Advanced INTegration with Wide-scale Intelligent Networks) research project.

**Live Site:** [https://braintwin.github.io](https://braintwin.github.io)

## About BRAINTWIN

BRAINTWIN is a four-year research project (2025-2029) funded by ANR under the PEPR Sante Numerique program of France 2030. The project develops digital twin technology for precision neurology, focusing on:

- **Primary Brain Tumors** (gliomas, meningiomas, CNS lymphomas)
- **Cerebral Small Vessel Disease** (SVD)

The consortium includes ICM Paris Brain Institute, Ecole Polytechnique, CentraleSupelec, Hospices Civils de Lyon, Universite de Bordeaux, and CNRS.

## Deployment to GitHub Pages

### Prerequisites

- GitHub account
- Repository named `BRAINTWIN.github.io` (for organization site) or `braintwin` (for project site)

### Step-by-Step Deployment Instructions

#### Option 1: Direct Upload (Easiest)

1. **Go to your GitHub repository** at `https://github.com/BRAINTWIN/BRAINTWIN.github.io`

2. **Upload all files:**
   - Click "Add file" > "Upload files"
   - Drag and drop all files and folders from this project
   - Commit the changes

3. **Enable GitHub Pages:**
   - Go to repository "Settings" > "Pages"
   - Under "Build and deployment", select:
     - Source: "Deploy from a branch"
     - Branch: `main` (or `master`)
     - Folder: `/ (root)`
   - Click "Save"

4. **Wait 2-3 minutes** for the site to build

5. **Visit your site** at `https://braintwin.github.io`

#### Option 2: Git Command Line

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BRAINTWIN/BRAINTWIN.github.io.git
   cd BRAINTWIN.github.io
   ```

2. **Copy all website files** into the repository folder

3. **Commit and push:**
   ```bash
   git add .
   git commit -m "Initial website deployment"
   git push origin main
   ```

4. **Enable GitHub Pages** (same as Option 1, Step 3)

#### Option 3: GitHub Actions (Recommended for Team)

1. **Create `.github/workflows/pages.yml`:**
   ```yaml
   name: Deploy Jekyll site to Pages

   on:
     push:
       branches: ["main"]
     workflow_dispatch:

   permissions:
     contents: read
     pages: write
     id-token: write

   concurrency:
     group: "pages"
     cancel-in-progress: false

   jobs:
     build:
       runs-on: ubuntu-latest
       steps:
         - name: Checkout
           uses: actions/checkout@v4
         - name: Setup Ruby
           uses: ruby/setup-ruby@v1
           with:
             ruby-version: '3.1'
             bundler-cache: true
         - name: Setup Pages
           uses: actions/configure-pages@v4
         - name: Build with Jekyll
           run: bundle exec jekyll build
           env:
             JEKYLL_ENV: production
         - name: Upload artifact
           uses: actions/upload-pages-artifact@v3

     deploy:
       environment:
         name: github-pages
         url: ${{ steps.deployment.outputs.page_url }}
       runs-on: ubuntu-latest
       needs: build
       steps:
         - name: Deploy to GitHub Pages
           id: deployment
           uses: actions/deploy-pages@v4
   ```

2. **Enable GitHub Actions deployment:**
   - Go to Settings > Pages
   - Under "Build and deployment", select "GitHub Actions"

## Project Structure

```
braintwin-site/
├── _config.yml          # Jekyll configuration
├── _layouts/
│   ├── default.html     # Main layout template
│   └── post.html        # Blog post layout
├── _includes/
│   ├── header.html      # Navigation header
│   └── footer.html      # Site footer
├── _data/               # Data files (YAML/JSON)
├── assets/
│   ├── css/
│   │   └── style.css    # Custom styles
│   ├── js/
│   │   └── main.js      # JavaScript
│   └── images/          # Images and logos
├── index.html           # Homepage
├── about.md             # About page
├── work-packages.md     # Work packages page
├── team.md              # Team page
├── publications.md      # Publications page
├── software.md          # Software & Data page
├── news.md              # News page
├── contact.md           # Contact page
├── privacy.md           # Privacy policy
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Local Development

### Prerequisites

- Ruby 2.7+ with Bundler
- Git

### Setup

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run local server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View site** at `http://localhost:4000`

### Live Reload (Development)

```bash
bundle exec jekyll serve --livereload
```

## Customization

### Update Site Information

Edit `_config.yml`:
```yaml
title: BRAINTWIN
description: "Your description"
url: "https://braintwin.github.io"
```

### Add Team Members

Edit the `team.md` file to add or update team member information.

### Add News Posts

Create new markdown files in `_posts/` folder with the format:
```
YYYY-MM-DD-title.md
```

Example:
```markdown
---
layout: post
title: "Your News Title"
date: 2025-01-15
author: "Author Name"
---

Your news content here...
```

### Add/Update Images

1. Place images in `assets/images/`
2. Reference them in markdown: `![Alt text]({{ '/assets/images/filename.png' | relative_url }})`
3. Or in HTML: `<img src="{{ '/assets/images/filename.png' | relative_url }}" alt="Alt text">`

### Styling

- Custom CSS is in `assets/css/style.css`
- The site uses Bootstrap 5 for responsive design
- Color variables are defined in CSS custom properties (`:root`)

## Technologies Used

- **Jekyll** - Static site generator
- **Bootstrap 5** - CSS framework
- **AOS** - Animate on scroll library
- **Bootstrap Icons** - Icon library
- **Google Fonts** - Inter & Playfair Display fonts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Create Pull Request

## License

This website is part of the BRAINTWIN project. Content is copyright BRAINTWIN Consortium 2025.

## Contact

- **Project Coordinator:** Dr. Agusti Alentorn
- **Institution:** Paris Brain Institute (ICM)
- **Email:** braintwin@icm-institute.org
- **Website:** [https://braintwin.github.io](https://braintwin.github.io)

---

*BRAINTWIN is funded by ANR under the PEPR Sante Numerique program of France 2030.*
