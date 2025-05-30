# Premium Apple-Inspired Invoice Template

A modern, responsive invoice template designed with Apple's design principles in mind. Perfect for freelancers, designers, and creative professionals who want to present their work professionally.

## 🌟 Features

### Design & UI
- **Apple-inspired Design**: Clean, minimalist interface with SF Pro Display font
- **Dark Mode by Default**: Professional dark theme with light mode toggle
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle fade-in animations and hover effects
- **Glassmorphism Elements**: Modern card designs with subtle shadows

### Functionality
- **QR Code Payment**: Integrated UPI QR code for easy payments
- **Multi-method Download**: Robust QR code download system that works on all devices
- **Theme Toggle**: Switch between dark and light modes
- **Scroll Indicator**: Visual progress bar showing page scroll position
- **Video Support**: Embedded video player for reel/video work showcase
- **Copy Link Feature**: Easy sharing of QR code links

### Professional Elements
- **Fixed Invoice Number**: Consistent invoice numbering (INV-004)
- **Auto Date Generation**: Current date automatically populated
- **Work Portfolio Display**: Showcase thumbnails and video work
- **Pricing Breakdown**: Clear summary of services and costs
- **Client Information**: Professional client details section

## 🚀 Quick Start

1. **Download the Files**
   - Save the HTML file as `index.html`
   - Create an `images` folder in the same directory

2. **Add Your Assets**
project-folder/
├── index.html
└── images/
├── Glitch Thumbnil-1.jpg
├── Glitch Thumbnil-2.jpg
├── Glitch Thumbnil-3.jpg
├── Glitch Thumbnil-4.jpg
├── Glitch Reel Cover.png
├── Glitch Reel Edit.mp4
└── pay.png (Your UPI QR Code)


3. **Customize Content**
- Update client information
- Replace thumbnail images
- Add your video content
- Update pricing details
- Replace QR code with your payment QR

4. **Open in Browser**
- Double-click `index.html` or serve via local server

## 📱 Device Compatibility

### Desktop Browsers
- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)

### Mobile Browsers
- ✅ iOS Safari
- ✅ Chrome Mobile
- ✅ Samsung Internet
- ✅ Firefox Mobile

### Download Functionality
- **Method 1**: Fetch + Blob (Modern browsers)
- **Method 2**: Canvas conversion (Fallback)
- **Method 3**: Direct download link (Legacy support)
- **Method 4**: New tab opening (Last resort)

## 🎨 Customization

### Colors
The template uses CSS custom properties for easy theming:

```css
:root {
--accent: #0071e3;        /* Primary blue */
--background: #000000;    /* Dark background */
--surface: #1d1d1f;      /* Card background */
--primary: #f5f5f7;      /* Text color */
--secondary: #a1a1a6;    /* Secondary text */
}

### Fonts

- Primary: SF Pro Display (Apple's system font)
- Fallback: -apple-system, BlinkMacSystemFont, sans-serif

## 💳 Payment Integration

### UPI QR Code Setup

1. Generate your UPI QR code from your payment app
2. Save as `images/pay.png`
3. The template automatically handles:

1. QR code display
2. Download functionality
3. Mobile-friendly sharing



### Supported Payment Methods

- UPI (Primary)
- Any QR code-based payment system
- Easy to extend for other payment methods

### Dependencies

- **None!** Pure HTML, CSS, and JavaScript
- No external libraries or frameworks
- Self-contained and lightweight


### Browser APIs Used

- Intersection Observer (animations)
- Clipboard API (copy functionality)
- Canvas API (image processing)
- Fetch API (download functionality)


## 📋 Checklist for Use

### Before Sending to Client

- Update invoice number if needed
- Replace all placeholder images
- Update client name and description
- Verify all work items and prices
- Test QR code payment functionality
- Check total amount calculation
- Update your contact information
- Test on mobile device


### File Preparation

- Optimize images (recommended: under 500KB each)
- Compress video files for web
- Test QR code with payment app
- Verify all links work correctly


## 🎯 Use Cases

### Perfect For

- **Freelance Designers**: Showcase design work professionally
- **Video Editors**: Display video content with embedded players
- **Content Creators**: Present work to clients/sponsors
- **Small Agencies**: Professional client billing
- **Consultants**: Service-based invoicing


### Industries

- Graphic Design
- Video Production
- Social Media Management
- Web Development
- Digital Marketing
- Photography


## 🔧 Troubleshooting

### Common Issues

**QR Code Not Downloading**

- Ensure image is accessible
- Check browser permissions
- Try different download method from modal


**Video Not Playing**

- Verify video format (MP4 recommended)
- Check file path and encoding
- Ensure video is web-optimized


**Animations Not Working**

- Check if browser supports CSS animations
- Verify JavaScript is enabled
- Clear browser cache


**Mobile Display Issues**

- Test viewport meta tag
- Check responsive breakpoints
- Verify touch interactions


### Performance Tips

- Optimize images before adding
- Use compressed video formats
- Test loading speed on slow connections
- Consider lazy loading for large galleries


## 📄 License

This template is not free to use for personal and commercial projects. 


## 📞 Support

For questions or customization help:

- aimlbysoham@gmail.com


---

**Made with ❤️ for @dzynsbysoham**

This README provides comprehensive documentation for your invoice template, covering everything from setup to customization to troubleshooting. It's structured to help both technical and non-technical users understand and implement the template effectively.
