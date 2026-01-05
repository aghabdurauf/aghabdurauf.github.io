# Personal Portfolio Website

A professional portfolio website built with Jekyll and hosted on GitHub Pages to showcase my work, experience, and professional activities.

## About

This portfolio website includes:
- Professional experience and work history
- Project showcase
- Skills and expertise
- About me section
- Contact information

## Tech Stack

- **Jekyll** - Static site generator
- **GitHub Pages** - Free hosting
- **Markdown** - Content writing
- **Liquid** - Templating

## Setup Instructions

### Prerequisites
- Git installed on your computer
- Ruby installed (version 2.5.0 or higher)
- GitHub account

### Local Development

1. **Install Jekyll and Bundler**
   ```bash
   gem install jekyll bundler
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View in browser**
   - Open http://localhost:4000

### Deployment to GitHub Pages

1. **Create a new repository**
   - Go to GitHub and create a new repository named `username.github.io` (replace `username` with your GitHub username)

2. **Initialize git and push**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Jekyll portfolio setup"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Source: Deploy from branch `main`
   - Your site will be live at `https://username.github.io`

## Customization

- Edit `_config.yml` for site settings
- Update content in markdown files
- Modify layouts in `_layouts/` folder
- Add projects to `_projects/` folder
- Customize styles in `assets/css/`

## Project Structure

```
.
├── _config.yml          # Site configuration
├── index.md             # Home page
├── about.md             # About page
├── projects.md          # Projects showcase
├── _layouts/            # Page templates
├── _includes/           # Reusable components
├── _projects/           # Individual project files
└── assets/              # CSS, images, JS
```

## Adding Content

### Add a New Project
Create a new file in `_projects/` folder:
```markdown
---
layout: project
title: "Project Name"
description: "Brief description"
technologies: [React, Node.js, MongoDB]
---

Detailed project description here...
```

### Update Experience
Edit the relevant section in `about.md` or create a dedicated experience page.

## License

This project is open source and available under the MIT License.
