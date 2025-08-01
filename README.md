# MadeByKings - Basketball & Media Platform

A modern, responsive website showcasing the MadeByKings brand, featuring the Slim Reapers basketball program, The Searchers Podcast, and MadeByKings YouTube channel. Built with Bootstrap and Vite for optimal performance and development experience.

## 🏀 About

MadeByKings is a multi-platform media brand created by Atem Bior, featuring:

- **Slim Reapers Basketball** - A grassroots AAU basketball program empowering youth through mentorship, training, and exposure
- **The Searchers Podcast** - Deep conversations on culture, creativity, identity, and purpose
- **MadeByKings YouTube** - Creative media content celebrating hoopers, developers, and creators

## 🚀 Project Structure

```
├── about.html              # About page with mission and project details
├── home-dashboard.html      # Dashboard with sidebar navigation
├── index.html              # Main landing page with carousel and content cards
├── package.json            # Project dependencies and scripts
├── vite.config.js          # Vite configuration for development
├── public/
│   └── images/             # Basketball game thumbnails and logos
└── src/
    ├── index.html          # Vite development entry point
    ├── js/
    │   └── main.js         # Main JavaScript entry point
    └── scss/
        └── styles.scss     # Custom Sass styles importing Bootstrap
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **Bootstrap 5.2.3** - CSS framework for responsive design
- **Sass** - CSS preprocessing
- **Vite** - Modern build tool and development server
- **JavaScript (ES6+)** - Interactive functionality

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd madebykings-project
   ```

2. **Install dependencies:**
   ```bash
   npm install bootstrap sass
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Navigate to `http://localhost:8080`

## 🎯 Features

### Main Landing Page ([index.html](index.html))
- Responsive navigation with dropdown menus
- Image carousel showcasing basketball values (Leadership, Community, Tenacity)
- Video content cards with YouTube integration
- Quote testimonial section

### About Page ([about.html](about.html))
- Personal mission statement
- Project showcase cards
- Professional bio and background
- Call-to-action buttons

### Dashboard ([home-dashboard.html](home-dashboard.html))
- Fixed sidebar navigation
- Dynamic content switching
- Responsive design for mobile devices

## 🎨 Styling

The project uses Bootstrap's utility classes combined with custom Sass:

- **Primary Colors**: Bootstrap's default color palette
- **Typography**: Bootstrap's typography system
- **Layout**: CSS Grid and Flexbox via Bootstrap classes
- **Components**: Bootstrap cards, navbar, carousel, and buttons

## 📱 Responsive Design

- Mobile-first approach
- Breakpoints: `sm`, `md`, `lg`, `xl`
- Collapsible navigation for mobile devices
- Responsive image handling
- Accessible design patterns

## 🔧 Development Setup

### Vite Configuration
The project uses Vite for fast development with:
- Port 8080 for local development
- Hot module replacement (HMR)
- Bootstrap alias configuration
- Sass preprocessing

### Custom Styles
Located in [`src/scss/styles.scss`](src/scss/styles.scss):
```scss
@import "~bootstrap/scss/bootstrap";
```

## 🚦 Available Scripts

- `npm start` - Start development server on port 8080
- `npm test` - Run tests (placeholder)

## 📂 Key Files

- [`index.html`](index.html) - Main landing page
- [`about.html`](about.html) - About page with detailed information
- [`home-dashboard.html`](home-dashboard.html) - Dashboard interface
- [`vite.config.js`](vite.config.js) - Build tool configuration
- [`src/js/main.js`](src/js/main.js) - JavaScript entry point

## 🐛 Known Issues

1. **Carousel ID Mismatch** - The carousel indicators reference `#carouselExampleCaptions` but the carousel ID is `carouselExampleControls`
2. **HTML Validation** - Unclosed quote attribute and mismatched div tags in the testimonial section
3. **Typos** - "Laedership" should be "Leadership" and "Tanacity" should be "Tenacity"

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 📞 Contact

**Atem Bior** - Creator & Developer

- YouTube: [@madebykings](https://www.youtube.com/@madebykings)
- Podcast: [The Searchers Podcast](https://open.spotify.com/show/2GRrhtrHF5zjPTmvEriXpT)
- Instagram: [@thesearcherspodcast](https://www.instagram.com/thesearcherspodcast/)

---

*"Everyone—and every business—has a story. My goal is to help YOU share YOUR STORY!"* - Atem Bior
