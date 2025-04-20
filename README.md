# Hugo Decap CMS Blog

A modern, fast, and SEO-optimized blog platform built with Hugo and Decap CMS (formerly Netlify CMS), featuring the elegant PaperModX theme.

![Hugo](https://img.shields.io/badge/Hugo-FF4088?style=for-the-badge&logo=hugo&logoColor=white)
![Decap CMS](https://img.shields.io/badge/Decap_CMS-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

## ✨ Features

- **Lightning Fast**: Static site generation with Hugo for optimal performance
- **Beautiful Design**: Clean, responsive UI with the PaperModX theme
- **User-Friendly CMS**: Easy content management through Decap CMS
- **SEO Optimized**: Proper meta tags, structured data, and optimized layouts
- **Deployment Ready**: Configured for one-click deployment on Render.com
- **Mobile-First**: Fully responsive design works on all devices
- **Customizable**: Easily extendable with Hugo's flexible templating
- **Markdown Support**: Write content in Markdown with front matter
- **Dark Mode**: Support for both light and dark themes
- **Multi-language**: Ready for internationalization

## 🚀 Getting Started

### Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.111.3 or later)
- [Git](https://git-scm.com/)
- Basic familiarity with the command line

### Quick Start

1. Clone this repository
   ```bash
   git clone https://github.com/poolboy17/hugo-decapcms-blog.git
   cd hugo-decapcms-blog
   ```

2. Start the Hugo development server
   ```bash
   hugo server --buildDrafts --disableFastRender --bind=0.0.0.0 --port=5000
   ```

3. Visit http://localhost:5000 in your browser to see your site

4. Make changes to your content in the `content/` directory

### Project Structure

```
.
├── archetypes/         # Content templates
├── content/            # Markdown content files
│   ├── posts/          # Blog posts
│   └── legal/          # Legal pages (privacy policy, terms, etc.)
├── layouts/            # Custom HTML layouts
├── static/             # Static assets (images, CSS, JS)
│   └── admin/          # Decap CMS admin interface
├── themes/             # Hugo themes
│   └── PaperModX/      # The PaperModX theme
├── config.toml         # Hugo configuration
└── render.yaml         # Render.com deployment configuration
```

## 📝 Content Management

This blog uses Decap CMS for content management, providing a user-friendly interface for non-technical users to create and edit content.

### Accessing the CMS

1. Go to `/admin/` on your deployed site (e.g., https://yourblog.com/admin/)
2. Log in with your GitHub credentials (or other authentication method configured)

### Content Types

The CMS is configured with the following content types:

- **Posts**: Blog articles and updates
- **Pages**: Static pages like About, Contact, etc.
- **Legal**: Privacy policy, terms of service, etc.

### Media Management

Upload and manage images and other media directly through the CMS interface.

## 🌐 Deployment

This repository is configured for easy deployment on Render.com:

1. Push this repository to your GitHub account
2. Create a new [Render.com](https://render.com) Static Site
3. Connect your GitHub repository
4. Render will automatically build and deploy your site

### Manual Deployment

You can also build the site manually and deploy to any static site host:

```bash
hugo --minify
```

This will generate the site in the `public/` directory, which you can then upload to any web hosting service.

## ⚙️ Customization

### Site Configuration

Edit the `config.toml` file to customize your site settings:

- Site title and description
- Author information
- Social media links
- Menu items
- Theme options

### Theme Customization

To customize the appearance:

1. Override theme partials by adding files to `layouts/partials/`
2. Add custom CSS in `static/css/custom.css`
3. Configure theme settings in `config.toml`

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [Hugo](https://gohugo.io/) for the amazing static site generator
- [Decap CMS](https://decapcms.org/) for the content management system
- [PaperModX](https://github.com/reorx/hugo-PaperModX) for the beautiful theme
- [Render](https://render.com) for hosting recommendations