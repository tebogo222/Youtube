# YouTube Clone 🎥

A professional, responsive YouTube UI clone built with vanilla HTML, CSS, and JavaScript. This project demonstrates modern web design principles and responsive layout techniques.

## ✨ Features

- **Responsive Design** - Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI** - Clean and intuitive user interface matching contemporary design standards
- **Material Design Icons** - Integrated Material Design Icon library for professional appearance
- **Search Functionality** - Interactive search bar with voice search icon
- **Navigation System** - Smooth navigation with category filters
- **Video Grid** - Dynamic video display grid with hover effects
- **User-Friendly** - Accessible and easy-to-navigate interface

## 🎯 Project Structure

```
Youtube-clean/
├── index.html              # Main HTML markup
├── style.css              # Styling and responsive layout
├── assets/                # Media assets
│   ├── logo.png           # Project logo
│   ├── images.png         # YouTube branding
│   └── *.jpeg             # Thumbnail images
├── docs/                  # Documentation files
├── README.md              # This file
├── CONTRIBUTING.md        # Contribution guidelines
├── LICENSE                # MIT License
└── .gitignore             # Git ignore patterns
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No dependencies or build tools required

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/Youtube-clean.git
   cd Youtube-clean
   ```

2. **Open in browser**

   - Simply open `index.html` in your web browser
   - Or use a local development server:

     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (if http-server is installed)
     npx http-server
     ```

3. **Access the application**
   - Open `http://localhost:8000` in your browser

## 🎨 Design Highlights

### Color Scheme

- **Background**: Clean white background (#FFFFFF)
- **Text**: Dark gray for readability (#212121)
- **Accents**: Professional blue for interactive elements
- **Borders**: Subtle light gray (#CCCCCC)

### Typography

- **Primary Font**: Roboto - Modern and readable
- **Secondary Font**: Open Sans - Clean and professional
- **Icon Library**: Material Icons by Google

### Responsive Breakpoints

- **Desktop**: Full featured experience (1200px+)
- **Tablet**: Optimized layout (768px - 1199px)
- **Mobile**: Touch-friendly interface (< 768px)

## 💡 Key Components

### Navbar

- Logo and branding section
- Search functionality with voice search option
- Navigation icons for notifications and user profile

### Sidebar

- Category navigation (Home, Explorer, Subscriptions, etc.)
- Section-based organization
- Active state highlighting

### Video Grid

- Responsive grid layout
- Hover effects for better interactivity
- Video thumbnail display with metadata
- Channel information

## 📱 Browser Support

| Browser       | Version | Support         |
| ------------- | ------- | --------------- |
| Chrome        | Latest  | ✅ Full Support |
| Firefox       | Latest  | ✅ Full Support |
| Safari        | Latest  | ✅ Full Support |
| Edge          | Latest  | ✅ Full Support |
| Mobile Safari | iOS 12+ | ✅ Full Support |
| Chrome Mobile | Latest  | ✅ Full Support |

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `style.css`:

```css
/* Primary Colors */
background-color: #ffffff;
color: #212121;
border-color: #cccccc;
```

### Adding More Videos

Simply duplicate a video card in `index.html` and update:

- Thumbnail image source
- Video title
- Channel name
- View count and upload time

### Adjusting Layout

Modify CSS grid settings:

```css
.video-grid {
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
}
```

## 📚 Learning Resources

This project is excellent for learning:

- HTML semantic markup
- CSS Flexbox and Grid layouts
- Responsive design techniques
- Modern UI/UX principles
- Web design best practices

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:

- Reporting bugs
- Suggesting features
- Submitting pull requests
- Code style standards

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Tebogo Musi**

## 🙏 Acknowledgments

- Google Material Design Icons
- Roboto and Open Sans fonts from Google Fonts
- Inspired by YouTube's modern design language
- Community feedback and contributions

## 📞 Support

For support, please:

1. Check the [docs/](docs/) folder for detailed documentation
2. Open an issue on GitHub
3. Review the CONTRIBUTING.md file

## 🎓 Educational Use

This project is perfect for:

- **Beginners** learning HTML/CSS fundamentals
- **Students** studying responsive web design
- **Portfolio** pieces for aspiring web developers
- **Reference** for modern UI design patterns

---

**⭐ If you find this project useful, please consider starring it!**

Made with ❤️ by Tebogo