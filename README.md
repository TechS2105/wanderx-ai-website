# WanderX - Futuristic Travel Agency Website

A modern, responsive single-page website for a travel agency featuring sleek design, smooth animations, and interactive elements.

## 🌟 Features

### Design & UI
- **Futuristic Design**: Glassmorphism effects, gradients, and neon accents
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations using AOS library
- **Modern Typography**: Space Grotesk and Inter fonts for a contemporary look

### Interactive Elements
- **Hero Slider**: Auto-advancing background image carousel
- **Package Filtering**: Dynamic filtering by category (Adventure, Luxury, Weekend, Family)
- **Testimonials Carousel**: Swiper.js powered testimonials slider
- **Gallery Lightbox**: Click to view full-size images
- **Contact Form**: Interactive form with floating labels
- **Newsletter Signup**: Email subscription functionality

### Navigation & UX
- **Sticky Navigation**: Glassmorphism navbar with scroll effects
- **Smooth Scrolling**: Anchor-based navigation with smooth transitions
- **Mobile Menu**: Hamburger menu for mobile devices
- **Floating CTA**: Persistent "Plan Your Trip" button
- **WhatsApp Integration**: Direct messaging button

### Performance & SEO
- **Fast Loading**: Optimized images and efficient code
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessibility**: ARIA labels and keyboard navigation support
- **Cross-browser Compatible**: Works on all modern browsers

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern structure
- **CSS3**: Advanced styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Vanilla JS with modern features
- **AOS (Animate On Scroll)**: Scroll-triggered animations
- **Swiper.js**: Touch-enabled carousel/slider
- **Font Awesome**: Icon library
- **Google Fonts**: Space Grotesk and Inter typography

## 📁 Project Structure

```
Travel Agency/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Enjoy** the WanderX travel agency website!

### Development Setup

For local development with live reload:

1. **Install Node.js** (if not already installed)
2. **Install Live Server**:
   ```bash
   npm install -g live-server
   ```
3. **Navigate** to the project directory
4. **Run** the development server:
   ```bash
   live-server
   ```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #06b6d4;
    /* ... other variables */
}
```

### Content
- **Hero Images**: Replace URLs in the hero slider section
- **Destinations**: Update destination cards with your locations
- **Packages**: Modify package offerings and pricing
- **Testimonials**: Add real customer reviews
- **Contact Info**: Update contact details and social media links

### Animations
- **AOS Settings**: Modify animation duration and effects in `script.js`
- **Custom Animations**: Add new keyframes in `styles.css`

## 🔧 Configuration

### Contact Form
The contact form currently simulates submission. To integrate with a real email service:

1. **EmailJS**: Add EmailJS configuration
2. **Formspree**: Use Formspree endpoint
3. **Custom Backend**: Implement your own API endpoint

### WhatsApp Integration
Update the WhatsApp number in the floating button:

```html
<a href="https://wa.me/YOUR_PHONE_NUMBER" target="_blank">
```

### Analytics
Add Google Analytics or other tracking services to the `<head>` section of `index.html`.

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please contact:
- Email: hello@wanderx.com
- Website: www.wanderx.com

## 🚀 Deployment

### Static Hosting
Deploy to any static hosting service:
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **GitHub Pages**: Enable in repository settings
- **Firebase Hosting**: Use Firebase CLI

### Custom Domain
1. Purchase a domain
2. Configure DNS settings
3. Update hosting provider settings
4. Add SSL certificate

## 📈 Performance Tips

1. **Optimize Images**: Use WebP format and appropriate sizes
2. **Minify Assets**: Compress CSS and JavaScript files
3. **Enable Caching**: Set proper cache headers
4. **Use CDN**: Serve assets from a content delivery network
5. **Lazy Loading**: Implement lazy loading for images

## 🔒 Security Considerations

- Use HTTPS in production
- Validate form inputs
- Sanitize user-generated content
- Keep dependencies updated
- Implement CSP headers

## 📊 SEO Optimization

- Meta tags are properly configured
- Semantic HTML structure
- Alt text for images
- Structured data markup (optional)
- Sitemap generation (for multi-page sites)

---

**Built with ❤️ for the modern travel industry** 