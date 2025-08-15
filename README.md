# Tolin Simpson - Resume Website

A professional resume website built with Jekyll and deployed on GitHub Pages.

## 🚀 Live Site

Visit: [https://tolinsimpson.github.io](https://tolinsimpson.github.io)

## 📋 Features

- **Professional Design**: Clean, modern resume layout
- **Responsive**: Works perfectly on desktop, tablet, and mobile
- **Contact Protection**: Email and phone number protected from web scrapers
- **GitHub Pages Ready**: Optimized for GitHub Pages deployment
- **Fast Loading**: Minimal dependencies and optimized assets
- **SEO Optimized**: Proper meta tags and structure

## 🛠️ Technology Stack

- **Jekyll**: Static site generator
- **HTML5 & CSS3**: Modern web standards
- **JavaScript**: Contact protection and interactivity
- **GitHub Pages**: Hosting and deployment

## 📁 Project Structure

```
TolinSimpson.github.io/
├── _config.yml          # Jekyll configuration
├── Gemfile              # Ruby dependencies
├── index.html           # Main resume page
├── robots.txt           # Search engine directives
├── README.md            # This file
└── assets/
    └── images/          # Images and headshot
```

## 🔧 Local Development

### Prerequisites

- Ruby 2.5 or higher
- Bundler gem

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/TolinSimpson/TolinSimpson.github.io.git
   cd TolinSimpson.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**
   Open [http://localhost:4000](http://localhost:4000) in your browser

## 🚀 Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Manual Deployment

1. **Build the site**
   ```bash
   bundle exec jekyll build
   ```

2. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Update resume"
   git push origin main
   ```

## 🔒 Security Features

- **Email Protection**: JavaScript-based email obfuscation
- **Phone Protection**: Protected phone number display
- **Web Scraping Prevention**: robots.txt and contact protection
- **Search Engine Control**: Prevents unwanted indexing

## 📱 Contact Information

- **GitHub**: [@TolinSimpson](https://github.com/TolinSimpson)
- **Email**: Protected (hover to reveal)
- **Phone**: Protected (hover to reveal)

## 🎨 Customization

### Updating Contact Information

Edit the JavaScript in `index.html` to update your contact details:

```javascript
// Email parts
const emailParts = ['your', 'email', '@', 'domain', '.com'];

// Phone parts  
const phoneParts = ['+1', ' ', '(', 'area', ')', ' ', 'phone', '-', 'number'];
```

### Styling Changes

Modify the CSS in the `<style>` section of `index.html` to customize colors, fonts, and layout.

## 📄 License

This project is for personal use. All rights reserved.

## 🤝 Contributing

This is a personal resume website. For professional inquiries, please use the contact information provided on the site.
