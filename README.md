# Modern Static Website

A modern, responsive static website built with HTML5, CSS3, and JavaScript. This site demonstrates best practices in web development and includes a CI/CD pipeline for automated deployment.

## Features

- Responsive design
- Modern UI/UX
- SEO optimized
- Fast loading times
- Progressive Web App (PWA) ready
- Dark/Light mode support

## Tech Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (ES6+)
- Netlify/Vercel for hosting
- GitHub Actions for CI/CD

## Project Structure

```
.
├── src/
│   ├── css/           # Stylesheets
│   ├── js/            # JavaScript files
│   ├── images/        # Image assets
│   └── index.html     # Main HTML file
├── .github/
│   └── workflows/     # GitHub Actions workflows
└── README.md          # This file
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/static-site.git
   cd static-site
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## Deployment

The site is automatically deployed to production when changes are pushed to the main branch. The deployment process includes:

1. Building the site
2. Running tests
3. Deploying to production
4. Invalidating CDN cache

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 