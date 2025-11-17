# Secure Password Generator

A stunning, feature-rich password and passphrase generator with a **futuristic glassmorphic UI**, offering both traditional random passwords and memorable word-based passphrases with extensive customization options.

![Password Generator Screenshot](https://i.imgur.com/m7MP7Em.png)

> **Note:** The screenshot above shows the previous design. The app now features a beautiful glassmorphic, futuristic UI with animated gradients, glowing effects, and smooth animations!

## ✨ Features

### 🎨 Glassmorphic Futuristic UI
- **Animated gradient backgrounds** with smooth color transitions (dark & light themes)
- **Frosted glass effect** with backdrop blur on all interactive elements
- **Neon glow effects** with purple and pink accent colors
- **Floating animations** for container and UI elements
- **Shimmer effects** on hover for buttons and controls
- **Gradient borders** with animated glow on focus
- **Smooth transitions** throughout the entire interface
- **Custom glowing scrollbars** with gradient styling
- **Interactive hover states** with scale, lift, and glow effects
- **Strength indicators** with gradient fills and glowing bars
- **Professional depth** with multiple shadow layers and transparency

### 🔐 Dual Generation Modes
- **Password Mode**: Generate strong random passwords with custom character sets
- **Passphrase Mode**: Create memorable passphrases using random dictionary words (e.g., `Correct-Horse-Battery-Staple-123`)

### 🎯 Password Generation
- Generate 4 different passwords simultaneously
- Adjustable password length (4-64 characters)
- Include/exclude character types:
  - Lowercase letters (a-z)
  - Uppercase letters (A-Z)
  - Numbers (0-9)
  - Symbols (!@#$%^&*()_+-=[]{}|;:,.<>?)
- Custom character support for specialized requirements

### 🔤 Passphrase Generation
- Generate memorable word-based passphrases
- Adjustable word count (3-8 words)
- Customizable word separator
- Optional word capitalization
- Optional number inclusion for added security
- 850+ word dictionary for high entropy

### 💪 Password Strength Indicator
- Real-time strength analysis for all generated passwords
- Visual strength meter with color coding:
  - 🔴 Weak
  - 🟡 Fair
  - 🟢 Good
  - 🟢 Strong
- Strength evaluation based on length and character variety

### 🎨 Theme Support
- Light and Dark theme toggle
- Theme preference saved in local storage
- Smooth theme transitions
- Optimized for both day and night use

### 📋 Clipboard & Export
- One-click copy individual passwords
- Copy all passwords at once
- Export passwords to text file with metadata
- Visual feedback on successful copy

### 📜 Password History
- Automatically saves recently generated passwords
- Stores up to 20 passwords in local history
- Quick copy from history
- Clear history option
- Persistent storage using localStorage

### ♿ Accessibility & UX
- Fully keyboard accessible
- ARIA labels for screen readers
- Keyboard shortcuts:
  - `Ctrl/Cmd + G`: Generate new passwords
  - `Ctrl/Cmd + Shift + C`: Copy all passwords
- Responsive design for mobile, tablet, and desktop
- Touch-friendly interface

### 🔒 Security & Privacy
- All generation happens client-side in your browser
- Cryptographically secure random number generation using `crypto.getRandomValues()`
- No passwords sent to any server
- No analytics or tracking
- No external dependencies

## 🚀 Live Demo

Check out the live demo: [https://xpalien.github.io/password-generator/](https://xpalien.github.io/password-generator/)

Or visit the custom domain: [https://pw.b3nx.com](https://pw.b3nx.com)

## 💻 Technologies

This project is built with pure web technologies - no frameworks or build tools required:

- **HTML5** - Semantic markup with ARIA accessibility
- **CSS3** - Advanced styling with:
  - CSS variables for theming
  - Backdrop-filter for glassmorphic effects
  - CSS animations (gradientShift, float, glow, shimmer)
  - Linear gradients for modern aesthetic
  - Flexbox and Grid for responsive layouts
  - Custom scrollbar styling
- **Vanilla JavaScript** - No dependencies, just pure JS
- **Web Crypto API** - Cryptographically secure random generation
- **Local Storage API** - Theme and history persistence

## 🛠️ Installation & Setup

### Option 1: Use the standalone HTML file (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/xPAlien/password-generator.git
   cd password-generator
   ```

2. Open `index.html` in your web browser - that's it!

### Option 2: Serve with a local server

```bash
# Python 3
python -m http.server 8000

# Node.js (with npx)
npx http-server

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 📦 Deployment

### GitHub Pages

This project is configured for easy deployment to GitHub Pages:

1. Fork or clone this repository
2. Push to your GitHub account
3. Go to Settings > Pages
4. Set the source to the main branch
5. Your site will be published at `https://yourusername.github.io/password-generator/`

### Other Hosting Options

Deploy to any static site hosting service:

- **Netlify**: Drag and drop the repository folder
- **Vercel**: Import from GitHub
- **Firebase Hosting**: `firebase deploy`
- **Cloudflare Pages**: Connect your GitHub repo
- **Any static file hosting**: Upload `index.html`

## 🎯 Usage Tips

### Creating Strong Passwords
1. Use at least 16 characters for maximum security
2. Enable all character types (lowercase, uppercase, numbers, symbols)
3. Check the strength indicator - aim for "Strong"
4. Avoid common patterns or dictionary words in password mode

### Creating Memorable Passphrases
1. Use 4-5 words for good balance of security and memorability
2. Enable capitalization for easier visual parsing
3. Add numbers for additional entropy
4. Choose memorable separators (-, _, ., etc.)
5. Example: `Beautiful-Garden-Morning-Coffee-789`

### Managing Your Passwords
- Use the history feature to retrieve recently generated passwords
- Export passwords immediately after generation
- Clear history after copying to password manager
- Use the copy-all feature for batch operations

## 🔒 Security Best Practices

- **Never reuse passwords** across different services
- **Use a password manager** to store generated passwords securely
- **Enable two-factor authentication** (2FA) wherever possible
- **Change passwords regularly** for sensitive accounts
- **Clear history** after copying passwords to your password manager
- **Don't share passwords** via insecure channels (email, chat, etc.)

## 🙌 Contribution

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/xPAlien/password-generator/issues).

### How to contribute:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is [MIT](LICENSE) licensed.

## 🎉 Changelog

### Version 2.1 (Latest) - Glassmorphic UI
- ✨ **Complete UI redesign** with glassmorphic futuristic aesthetic
- 🎨 Animated gradient backgrounds with 15s color-shifting animations
- ✨ Frosted glass effect with backdrop-filter blur on all elements
- 💫 Neon glow effects with purple (#8b5cf6) and pink (#ec4899) accents
- 🌊 Floating animations for container and overlay elements
- ⚡ Shimmer effects on button hover interactions
- 🔮 Gradient borders with animated glow effects
- 🎯 Enhanced strength indicators with gradient fills and glow
- 📜 Custom gradient scrollbars with glow effects
- 🎭 Professional depth with multi-layer shadows and transparency
- 🌈 Smooth hover states with scale, lift, and glow transformations

### Version 2.0
- ✅ Added passphrase generation mode with 850+ word dictionary
- ✅ Added password strength indicator with visual feedback
- ✅ Added light/dark theme toggle with persistence
- ✅ Added password history (up to 20 passwords)
- ✅ Added copy all passwords feature
- ✅ Added export to file functionality
- ✅ Improved accessibility with ARIA labels and keyboard shortcuts
- ✅ Enhanced mobile responsiveness
- ✅ Increased password length maximum to 64 characters
- ✅ Switched to cryptographically secure random generation
- ✅ Improved UI/UX with better visual feedback
- ✅ Added organized code structure with comments

### Version 1.0
- Basic password generation
- Character type selection
- Custom characters support
- Copy to clipboard
- Dark mode UI

## 🔗 Links

- **Live Demo**: [https://xpalien.github.io/password-generator/](https://xpalien.github.io/password-generator/)
- **Custom Domain**: [https://pw.b3nx.com](https://pw.b3nx.com)
- **Repository**: [https://github.com/xPAlien/password-generator](https://github.com/xPAlien/password-generator)
- **Issues**: [https://github.com/xPAlien/password-generator/issues](https://github.com/xPAlien/password-generator/issues)

## 💡 Acknowledgments

- Inspired by best practices in password security
- Word list curated from common English words for memorability
- UI design inspired by glassmorphism and futuristic aesthetics
- Animations and effects designed for smooth, modern user experience
- Built with ❤️ for the security-conscious community

---

**Made with ❤️ by [xPAlien](https://github.com/xPAlien)**

If you found this project helpful, please consider giving it a ⭐!
