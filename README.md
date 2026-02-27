# ✍️ Handwritten Signature and Watermark Tool

A powerful online handwritten signature and watermark tool that supports custom signatures, watermark addition, and image export.

## 🌟 Features

- ✍️ **Handwritten Signature** - Support mouse and touch screen drawing
- 💧 **Custom Watermark** - Customize watermark text, color, size, and opacity
- 🎨 **Brush Settings** - Freely adjust brush color and width
- 💾 **Image Export** - Support preview and download signature images
- 📱 **Responsive Design** - Perfect support for mobile and desktop
- 🎯 **Zero Dependencies** - Only uses html2canvas library, no complex configuration

## 🚀 Quick Start

### Online Access

Visit the deployed version on GitHub Pages:
```
https://ironicbo.github.io/e-sign/
```

### Local Usage

1. Clone the repository
```bash
git clone https://github.com/IRONICBo/e-sign.git
cd e-sign
```

2. Open the HTML file directly
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

Then visit `http://localhost:8000/`

## 📖 Usage Guide

### Basic Operations

1. **Draw Signature**
   - Drag mouse or finger on the canvas to draw
   - Adjust brush color and width as needed

2. **Add Watermark**
   - Click "Show/Hide Watermark" button
   - Customize watermark text, color, size, and opacity
   - Adjust watermark row and column spacing

3. **Export Image**
   - Click "Save as Image" to preview the final result
   - Click "Download Image" to save locally

### Parameter Description

| Parameter | Description | Default Value |
|-----------|-------------|---------------|
| Pen Color | Brush color | Black |
| Pen Width | Brush width | 3px |
| Watermark Text | Watermark text content | Confidential |
| Watermark Opacity | Watermark transparency | 0.05 |
| Watermark Size | Watermark font size | 60px |
| Watermark Color | Watermark color | Black |
| Row Spacing | Vertical spacing between watermarks | 3x |
| Column Spacing | Horizontal spacing between watermarks | 3x |

## 🛠️ Tech Stack

- HTML5 Canvas - Drawing functionality
- JavaScript (Vanilla) - Interaction logic
- CSS3 - Styling and animations
- [html2canvas](https://html2canvas.hertzen.com/) - Screenshot export

## 📦 Project Structure

```
e-sign/
├── index.html                  # Main page (all functionality included)
├── README.md                   # Project documentation
└── .github/
    └── workflows/
        └── deploy.yml          # GitHub Pages auto-deploy configuration
```

## 🚢 Deployment

### GitHub Pages

The project is configured for automatic deployment to GitHub Pages. It will auto-deploy whenever you push to the main branch.

Manual deployment steps:
1. Fork or clone this repository
2. Enable GitHub Pages in repository settings
3. Select **GitHub Actions** as the source
4. Push code to main branch, GitHub Actions will auto-deploy

### Other Platforms

- **Vercel**: Import GitHub repository for one-click deployment
- **Netlify**: Drag and drop project folder for deployment
- **Cloudflare Pages**: Connect GitHub repository for auto-deployment

## 🤝 Contributing

Issues and Pull Requests are welcome!

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 🙏 Acknowledgments

- [html2canvas](https://html2canvas.hertzen.com/) - Powerful HTML to image library
- All contributors and users

## 📞 Contact

If you have any questions or suggestions, feel free to contact:

- Submit an [Issue](https://github.com/IRONICBo/e-sign/issues)
- Email: [your-email@example.com]

---

⭐ If this project helps you, please give it a star!
