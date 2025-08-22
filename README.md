# Microsoft Presidio Privacy Protection Demo

![Presidio Demo](https://img.shields.io/badge/Presidio-Privacy%20First-blue)
![GDPR](https://img.shields.io/badge/GDPR-Compliant-green)
![Open Source](https://img.shields.io/badge/Open%20Source-MIT-orange)

A professional, interactive demonstration of Microsoft Presidio's PII detection and anonymization capabilities, designed for privacy-first AI development.

**Created by:** [Niranjan Thimmappa](https://github.com/niranjanxprt)

## 🌐 Live Demo
🔗 **[View Live Demo](https://niranjanxprt.github.io/presidio-privacy-demo)**

## ✨ Features

### 🎨 Professional Design
- Modern, enterprise-grade visual design
- Smooth animations and interactions
- Mobile-responsive layout
- Built-in LinkedIn sharing functionality

### 💻 Real Implementation
- Actual Microsoft Presidio code examples
- Real installation commands from official docs
- Live PII detection demonstration
- GDPR compliance integration with Langfuse

### 🔧 Technical Highlights
- **Zero build process** - works instantly on GitHub Pages
- **CDN-optimized** for fast loading
- **SEO friendly** with proper meta tags
- **Accessibility compliant** with semantic HTML

## 🚀 Technology Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Styling:** Tailwind CSS via CDN
- **Icons:** Emoji-based (no external dependencies)
- **Hosting:** GitHub Pages
- **Performance:** Optimized for mobile and desktop

## 📱 Perfect for LinkedIn Posts

### Option 1: Screenshot (Recommended)
1. Visit the [live demo](https://niranjanxprt.github.io/presidio-privacy-demo)
2. Take a full-page screenshot using browser dev tools:
   - Open Developer Tools (`F12`)
   - Toggle device toolbar (`Ctrl+Shift+M`)  
   - Set device to "Responsive" → 1200x800px
   - Take screenshot
3. Upload to LinkedIn with your post

### Option 2: Screen Recording
1. Use **Loom**, **ScreenToGif**, or browser screen recording
2. Record 15-20 seconds highlighting key features
3. Export as GIF (under 5MB for LinkedIn)

### Option 3: Direct Link Share
1. Use the built-in "Share on LinkedIn" button
2. Or paste the GitHub Pages URL directly
3. LinkedIn auto-generates rich preview

## 🎯 LinkedIn Post Template

```markdown
🛡️ Privacy-First AI: Microsoft Presidio Demo

Just built an interactive demo showcasing how Microsoft Presidio revolutionizes PII protection in AI pipelines:

✅ 180+ entity types detected with 95%+ accuracy
✅ Multi-modal support (text, images, PDFs)  
✅ Real-time anonymization for LLM training
✅ Complete GDPR compliance framework

🤔 **Question for the community:**
When using observability tools like Langfuse to monitor LLM training, how do you balance detailed performance insights with GDPR's data minimization principle?

🔗 Interactive demo: https://niranjanxprt.github.io/presidio-privacy-demo

#GDPR #DataPrivacy #LLM #AI #MachineLearning #Presidio #PrivacyByDesign #OpenSource #PresidioDemo

What's your experience with privacy-preserving AI architectures? 
```

## 🔧 Local Development

For local development, clone the repository and open `index.html` in your browser with a local server:

### Using VS Code Live Server (Recommended)
1. Install [VS Code](https://code.visualstudio.com/)
2. Install "Live Server" extension
3. Right-click `index.html` → "Open with Live Server"

### Using Python
```bash
# Navigate to project folder
cd path/to/your/project

# Python 3
python -m http.server 8000

# Open: http://localhost:8000
```

### Using Node.js
```bash
npm install -g http-server
http-server
# Open: http://localhost:8080
```

## 🎨 Customization

### Brand Colors
Edit Tailwind classes in `index.html`:
```html
<!-- Replace blue-600 with your brand color -->
<div class="bg-gradient-to-r from-blue-600 to-indigo-600">

<!-- Examples: -->
from-purple-600 to-pink-600     <!-- Purple theme -->
from-green-600 to-emerald-600   <!-- Green theme -->
```

### Add Company Logo
Replace header emoji with your logo:
```html
<!-- In header section -->
<div class="w-8 h-8 bg-gradient-to-r from-blue-600 to-indigo-600 rounded-lg flex items-center justify-center">
    <img src="your-logo.png" alt="Your Company" class="w-5 h-5">
</div>
```

## 📊 Analytics & SEO

### Google Analytics (Optional)
Add before closing `</head>` tag:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Meta Tags (Already Included)
- Open Graph for rich social sharing
- Twitter Card support
- SEO-optimized descriptions
- Mobile viewport configuration

## 🔗 Related Resources
- [Microsoft Presidio Repository](https://github.com/microsoft/presidio)
- [Official Documentation](https://microsoft.github.io/presidio/)
- [Langfuse LLM Observability](https://langfuse.com/)
- [GDPR Compliance Guide](https://gdpr.eu/)

## 🤝 Contributing

This demo is designed to showcase Microsoft Presidio capabilities. Contributions welcome:

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Microsoft Presidio Team** for the amazing privacy protection framework
- **Tailwind CSS** for the utility-first CSS framework
- **GitHub Pages** for free hosting
- **Privacy-First AI Community** for inspiration and support

## 📞 Contact

**Niranjan Thimmappa**
- LinkedIn: [Connect with me](https://linkedin.com/in/niranjan-thimmappa)
- GitHub: [@niranjanxprt](https://github.com/niranjanxprt)
- Email: [niranjan.thimmappa@outlook.com](mailto:niranjan.thimmappa@outlook.com)

---

**⭐ If this demo helped you understand Microsoft Presidio, please star this repository!**

Built with ❤️ for the privacy-first AI community