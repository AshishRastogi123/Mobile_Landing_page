# Sync - Mobile App Landing Page HTML Template

## Overview

Sync is a responsive landing page HTML template built with Bootstrap 4 for presenting mobile apps to the online audience and converting visitors into users. It features a modern design with details lightbox, tabbed content, image slider, image lightbox, statistics counters, dropdown navigation, extra pages, and a working contact form.

## Features

- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **Bootstrap 4**: Built with the latest Bootstrap framework
- **Interactive Elements**:
  - Details lightbox for showcasing app features
  - Tabbed content sections
  - Image slider with screenshots
  - Image lightbox for gallery viewing
  - Animated statistics counters
- **Navigation**: Dropdown menu with smooth scrolling
- **Contact Form**: Working PHP contact form with validation
- **Extra Pages**: Article details, privacy policy, terms & conditions
- **SEO Optimized**: Includes meta tags for better search engine visibility
- **Social Media Integration**: Open Graph meta tags for sharing

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **PHP** (for contact form processing)
- **Frameworks & Libraries**:
  - Bootstrap 4
  - jQuery
  - Popper.js
  - Swiper (for sliders)
  - Magnific Popup (for lightboxes)
  - Validator.js (for form validation)
  - Font Awesome (for icons)

## File Structure

```
sync-landing-page/
├── index.html                    # Main landing page
├── article-details.html          # Article details page
├── privacy-policy.html           # Privacy policy page
├── terms-conditions.html        # Terms & conditions page
├── css/
│   ├── bootstrap.css            # Bootstrap framework
│   ├── fontawesome-all.css      # Font Awesome icons
│   ├── magnific-popup.css       # Magnific Popup styles
│   ├── styles.css               # Custom styles
│   └── swiper.css               # Swiper slider styles
├── js/
│   ├── bootstrap.min.js         # Bootstrap JavaScript
│   ├── jquery.min.js            # jQuery library
│   ├── popper.min.js            # Popper.js
│   ├── swiper.min.js            # Swiper slider
│   ├── jquery.magnific-popup.js # Magnific Popup
│   ├── validator.min.js         # Form validation
│   ├── jquery.easing.min.js     # Smooth scrolling
│   └── scripts.js               # Custom scripts
├── images/                      # All images and assets
├── php/
│   ├── contact-process.php      # Contact form handler
│   └── privacyform-process.php  # Privacy form handler
├── webfonts/                    # Font Awesome web fonts
└── documentation/               # Documentation files
    ├── index.html               # Documentation page
    ├── css/                     # Documentation styles
    ├── js/                      # Documentation scripts
    └── fonts/                   # Documentation fonts
```

## Installation & Setup

1. **Download**: Download or clone the repository to your local machine.

2. **Open**: Open `index.html` in your web browser to view the template.

3. **Customize**: Edit the HTML, CSS, and JavaScript files as needed.

4. **Deploy**: Upload the files to your web server.

### Requirements

- A web server with PHP support (for contact form functionality)
- Modern web browser

### Contact Form Setup

To enable the contact form:

1. Open `php/contact-process.php`
2. Change `$EmailTo = "yourname@domain.com";` to your email address
3. Upload to a server with PHP support

## Customization

### Changing Images

- Replace images in the `images/` folder
- Update image references in `index.html`
- For logo: Update the `src` attribute in the navigation section
- For screenshots: Update the slider section in `index.html`

### Changing Colors & Styles

- Edit `css/styles.css` for custom styling
- Use Bootstrap classes for layout modifications

### Adding/Modifying Content

- Edit text content directly in the HTML files
- Update navigation links in the header section
- Modify form fields in the contact section

### Icons

- Uses Font Awesome icons
- Change icon classes in `index.html` (e.g., `fa-users`, `fa-code`)

For detailed customization instructions, refer to the `documentation/index.html` file.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## License

This template is provided as-is. Please check the documentation for licensing details.

## Credits

- **Author**: Ashish Rastogi
- **Bootstrap**: https://getbootstrap.com/
- **Font Awesome**: https://fontawesome.com/
- **Swiper**: https://swiperjs.com/
- **Magnific Popup**: https://dimsemenov.com/plugins/magnific-popup/
- **Images**: Various sources (see documentation for credits)

## Support

For support and questions, refer to the documentation or contact the author.

---

*Sync - Helping you present your mobile app beautifully.*
