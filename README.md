# My Portfolio Website

A responsive, modern portfolio website built with Jekyll and hosted on GitHub Pages.

## 📋 Features

- **Home Page** - Professional profile with introduction and social links
- **About Page** - Background, qualifications, skills, and activities
- **Projects Page** - Portfolio of projects with descriptions and links
- **Contact Page** - Contact form and social media connections
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Jekyll Integration** - Powered by Jekyll for static site generation
- **GitHub Pages Ready** - Deploy directly to GitHub Pages
- **Clean Code** - Well-organized, modular structure

## 📁 Project Structure

```
portfolio/
├── _config.yml               # Jekyll configuration
├── _layouts/
│   ├── default.html         # Default page layout
│   └── home.html            # Home page layout
├── _pages/
│   ├── index.md             # Home page (Markdown)
│   ├── about.md             # About page (Markdown)
│   ├── projects.md          # Projects page (Markdown)
│   └── contact.md           # Contact page (Markdown)
├── assets/
│   ├── css/
│   │   └── style.css        # Main stylesheet
│   ├── js/
│   │   └── script.js        # JavaScript for interactivity
│   └── images/
│       ├── profile.jpg      # Profile photo
│       └── projects/        # Project screenshots
├── Gemfile                  # Ruby dependencies
└── README.md               # This file
```

## 🚀 Getting Started Locally

### Prerequisites
- Ruby 2.7 or higher
- Git

### Installation

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/GGBUUR/test.git
   cd test
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run Jekyll locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site**
   Open your browser and go to: `http://localhost:4000`

## 📦 Deploy to GitHub Pages

### Method 1: Automatic Deployment (Recommended)

1. Push your code to GitHub:
   ```bash
   git add .
   git commit -m "Initial Jekyll setup"
   git push origin main
   ```

2. Go to your repository settings → Pages
3. Select `main` branch as source
4. GitHub will automatically build and deploy your site

### Method 2: Manual Build

```bash
bundle exec jekyll build
# The `_site` folder contains your static site
```

## 🎨 Customization

### Edit Site Settings
Update `_config.yml` with your information:
```yaml
title: "My Portfolio"
author: "Your Name"
url: "https://yourusername.github.io/test"
```

### Edit Page Content
All pages are in `_pages/` folder as Markdown files:
- `index.md` - Home page
- `about.md` - About page
- `projects.md` - Projects page
- `contact.md` - Contact page

### Customize Styles
Edit `assets/css/style.css` to change colors, fonts, and layout.

### Add Images
Place images in `assets/images/` and reference them in your pages:
```markdown
![Alt text](/assets/images/your-image.jpg)
```

## 🔗 Resources Used

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
- [Font Awesome 6](https://fontawesome.com/) - Icons
- [Kramdown](https://kramdown.gettalong.org/) - Markdown processor

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 About

Created by Rasul Huseynli - [GitHub](https://github.com/GGBUUR)

