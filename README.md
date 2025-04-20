# Hugo Decap CMS Blog

A modern blog built with Hugo and Decap CMS (formerly Netlify CMS), featuring the PaperModX theme.

## Features

- Fast static site generation with Hugo
- Modern, responsive design using the PaperModX theme
- Content management through Decap CMS
- SEO optimized with proper meta tags
- Ready for deployment on Render.com

## Getting Started

### Prerequisites

- [Hugo Extended](https://gohugo.io/getting-started/installing/) (v0.111.3 or later)
- [Git](https://git-scm.com/)

### Local Development

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/hugo-decapcms-blog.git
   cd hugo-decapcms-blog
   ```

2. Start the Hugo development server
   ```bash
   hugo server --buildDrafts --disableFastRender
   ```

3. Visit http://localhost:1313 in your browser

## Content Management

This blog uses Decap CMS for content management. To access the admin interface:

1. Go to `/admin/` on your deployed site
2. Log in with your credentials

## Deployment

This repository includes a `render.yaml` file for easy deployment on Render.com:

1. Push this repository to GitHub
2. Create a new Render.com Web Service
3. Connect your GitHub repository
4. Render will automatically deploy your site

## License

This project is licensed under the MIT License - see the LICENSE file for details.