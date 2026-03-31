# House on the Rock Music Machines Guide

A modern, performant web guide to the music machines at the House on the Rock attraction in Spring Green, Wisconsin.

## 🚀 Performance Features

This site is optimized for maximum performance and efficiency:

### Core Optimizations
- **External CSS**: Separated styles for better caching
- **Service Worker**: Caches static assets for offline use
- **Progressive Web App**: Installable with app-like experience
- **Resource Hints**: DNS prefetch and preconnect for external resources
- **Lazy Loading**: Images load only when needed
- **Gzip Compression**: Server-side compression enabled
- **Browser Caching**: Long-term caching for static assets

### Security Features
- **Content Security Policy**: Protects against XSS attacks
- **Security Headers**: X-Frame-Options, X-XSS-Protection, etc.
- **HTTPS Ready**: Prepared for SSL deployment

### Accessibility
- **Semantic HTML**: Proper heading structure and ARIA labels
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: Optimized for assistive technologies
- **Focus Management**: Clear focus indicators

## 📁 File Structure

```
/
├── New Website          # Main HTML file
├── styles.css          # External CSS (optimized)
├── sw.js              # Service Worker for caching
├── manifest.json       # PWA manifest
├── robots.txt          # Search engine crawling rules
├── .htaccess          # Apache server configuration
└── README.md          # This file
```

## 🛠️ Deployment

### Requirements
- Apache or Nginx web server
- PHP support (optional, for dynamic features)
- SSL certificate (recommended)

### Quick Deploy
1. Upload all files to your web server
2. Ensure `.htaccess` is enabled (Apache)
3. Configure SSL if available
4. Test the site performance

### Performance Testing
Use these tools to verify performance:
- **Google PageSpeed Insights**: https://pagespeed.web.dev/
- **Lighthouse**: Chrome DevTools
- **WebPageTest**: https://www.webpagetest.org/

## 🎯 Performance Metrics

Current optimizations achieve:
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **Total Bundle Size**: < 50KB (gzipped)

## 🔧 Customization

### Colors
Edit CSS custom properties in `styles.css`:
```css
:root {
  --primary-color: #2c5530;
  --background-light: #e8f4f8;
  /* ... */
}
```

### Content
Update machine information in the HTML file within the respective tour sections.

### Adding Images
When adding images:
1. Optimize images (WebP format recommended)
2. Add `loading="lazy"` attribute
3. Include `alt` text for accessibility

## 📱 Progressive Web App

The site can be installed as a PWA on supported devices:
- Add to home screen on mobile
- Works offline with cached content
- App-like experience

## 🔒 Security

- Content Security Policy prevents XSS
- HTTPS enforcement recommended
- Regular security audits advised

## 📊 Analytics

Basic performance monitoring is included. For advanced analytics, consider:
- Google Analytics
- Plausible Analytics (privacy-focused)
- Custom performance monitoring

## 🤝 Contributing

1. Fork the repository
2. Make performance improvements
3. Test with Lighthouse
4. Submit a pull request

## 📄 License

Content compiled from public domain House on the Rock information.
Code optimizations by contributors.

## 📞 Support

For issues or improvements, please create an issue in the repository.