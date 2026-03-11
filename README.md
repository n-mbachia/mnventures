# MN Ventures Portfolio

A professional portfolio website customized from the HTML5UP "Read Only" template and hosted on GitHub Pages.

## About

This portfolio website showcases the work and services of MN Ventures. The site has been customized from an HTML5UP template to create a modern, business-focused presence.

## Features

- **Modernized Landing Page**: Updated hero, CTAs, and content hierarchy for clearer UX
- **Project Showcase**: Featured project cards with consistent layout and actions
- **eBook Lead Capture**: Dedicated ebook form page for collecting interest and delivery details
- **Contact Form**: Sends emails to the configured Gmail address via FormSubmit
- **GitHub Pages Hosting**: Deployed and served as a static site

## Technology Stack

- HTML5
- CSS3 (customized HTML5UP styles)
- JavaScript (includes jQuery utilities from the template)
- FormSubmit for email form handling
- GitHub Pages for hosting

## Key Pages

- `index.html`: Main landing page and portfolio
- `mushroom_ebook_form.html`: eBook interest form and payment instructions

## Forms

- **Contact form** (`index.html`) posts to FormSubmit and emails `mnventures2024@gmail.com`.
- **eBook form** (`mushroom_ebook_form.html`) posts to FormSubmit and redirects back with `?success=1`.
- If FormSubmit has not been activated for the address yet, the first submission triggers a confirmation email.

## Design Elements

### Typography
- **Primary Font**: Lato (Google Fonts)
  - Weights: 400 (regular), 700 (bold)
  - Styles: Normal and italic
- **Code Font**: Source Code Pro (monospace)

### Color Palette
- **Primary Brand Color**: `#2C3E50` (Dark blue-gray)
- **Secondary/Accent Color**: `#4DB6AC` (Teal/Mint green)
- **Text Colors**:
  - Primary text: `#888` (Medium gray)
  - Headings: `#777` (Dark gray)
  - Links: `#2C3E50` (Brand color on hover)
  - Header text: `#ffffff` (White)
  - Header links: `#d2f2e9` (Light mint)
- **Background Colors**:
  - Main background: `#ffffff` (White)
  - Header background: `#2C3E50` (Brand color)
  - Footer background: `#fafafa` (Very light gray)
  - Feature icons: `#4db6ac` (Accent color)

## Contact

The contact form on the website is fully functional and configured to send emails to our designated email address. Feel free to reach out through the contact section of the site.

## Performance & Optimization

- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **Optimized Images**: Compressed images for faster loading times
- **Minified Assets**: CSS and JavaScript files are optimized for production
- **Browser Compatibility**: Tested across modern browsers (Chrome, Firefox, Safari, Edge)

## Security Features

- **Content Security Policy**: CSP meta tag configured for controlled external resources
- **Form Security**: Honeypot field and captcha disabled for FormSubmit
- **Secure Hosting**: GitHub Pages provides HTTPS by default
- **Input Validation**: Client-side validation for all form inputs

## Accessibility

- **Semantic HTML5**: Proper use of HTML5 semantic elements
- **ARIA Labels**: Accessible form labels and navigation
- **Keyboard Navigation**: Full keyboard accessibility support
- **Color Contrast**: WCAG compliant color combinations
- **Screen Reader Friendly**: Proper alt texts and structured content

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment & Maintenance

- **Automated Deployment**: GitHub Pages auto-deploys on push to main branch
- **Version Control**: Git version control with meaningful commit messages
- **Backup Strategy**: Code hosted on GitHub with version history
- **Monitoring**: GitHub Pages provides basic uptime monitoring

## Contributing

This is a personal portfolio project. For inquiries or collaboration opportunities, use the contact form on the website.

## License

This project is based on a template by [HTML5UP](https://html5up.net) and has been customized for MN Ventures' specific needs. The original template is licensed under the CCA 3.0 license.
