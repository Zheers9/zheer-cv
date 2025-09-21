# Zheer Salam - Portfolio & CV

A modern, responsive portfolio website built with VuePress showcasing professional experience, projects, and skills.

## 🚀 Live Site

Visit the live portfolio: [https://yourusername.github.io/zheer-cv/](https://yourusername.github.io/zheer-cv/)

## 📋 Features

- **Responsive Design**: Optimized for all devices
- **Modern UI**: Clean and professional interface
- **Fast Loading**: Built with VuePress for optimal performance
- **SEO Optimized**: Proper meta tags and structure
- **Easy Navigation**: Intuitive menu and page structure

## 🛠️ Tech Stack

- **Framework**: VuePress 2.0
- **Styling**: SCSS
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## 📁 Project Structure

```
├── docs/                    # Documentation source
│   ├── .vuepress/          # VuePress configuration
│   │   ├── config.js       # Site configuration
│   │   ├── public/         # Static assets
│   │   └── styles/         # Custom styles
│   ├── about/              # About page
│   ├── contact/            # Contact page
│   ├── projects/           # Projects showcase
│   ├── resume/             # Resume/CV page
│   └── README.md           # Homepage content
├── .github/workflows/      # GitHub Actions
└── package.json           # Dependencies and scripts
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or pnpm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/zheer-cv.git
cd zheer-cv
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Start development server:
```bash
npm run docs:dev
# or
pnpm docs:dev
```

4. Build for production:
```bash
npm run docs:build
# or
pnpm docs:build
```

## 📝 Customization

### Updating Content

- **Homepage**: Edit `docs/README.md`
- **About**: Edit `docs/about/README.md`
- **Projects**: Edit `docs/projects/README.md`
- **Resume**: Edit `docs/resume/README.md`
- **Contact**: Edit `docs/contact/README.md`

### Configuration

Main configuration is in `docs/.vuepress/config.js`:
- Site title and description
- Navigation menu
- Theme settings
- Base URL for deployment

### Styling

Custom styles are in `docs/.vuepress/styles/`:
- `index.scss`: Global styles
- `back-to-top.css`: Back to top button styles

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. The workflow:

1. Triggers on push to `main` branch
2. Installs dependencies
3. Builds the VuePress site
4. Deploys to `gh-pages` branch

### Manual Deployment

```bash
npm run deploy
```

## 📄 License

This project is licensed under the MIT License.

## 📞 Contact

- **Name**: Zheer Salam
- **Email**: [your-email@example.com]
- **LinkedIn**: [Your LinkedIn Profile]
- **GitHub**: [Your GitHub Profile]

---

Built with ❤️ using VuePress
