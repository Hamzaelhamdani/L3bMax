# L3bMax - Huawei QuickApp Tic-Tac-Toe Game

🧡 **Modern Mini App with Orange Telecom Branding**

## 🎮 Features

- **Modern Splash Screen** with Maxit logo and progress bar (0% → 100%)
- **Complete Tic-Tac-Toe Game** with Orange Telecom identity
- **Responsive Design** for all Huawei devices
- **Professional Branding** with L3bMax Avec Maxit theme
- **Smooth Animations** and transitions

## 🚀 Quick Start

### Prerequisites
- Node.js (v12 or higher)
- fa-toolkit for Huawei QuickApp development

### Installation & Build

```bash
# Install dependencies
npm install

# Build the QuickApp package
npm run fa-build

# Preview in web browser
npm run fa-preview
```

## 📱 Project Structure

```
L3bMax/
├── src/
│   ├── Splash/
│   │   └── splash.ux         # Modern splash screen with Maxit logo
│   ├── Hello/
│   │   └── hello.ux          # Main Tic-Tac-Toe game
│   ├── app.ux                # App entry point
│   └── manifest.json         # App configuration
├── build/                    # Generated build files
├── preview.html              # Web preview for testing
├── package.json              # Project dependencies
└── README.md                 # This file
```

## 🎨 Design & Branding

- **Primary Color**: Orange Telecom (#FF7900)
- **Typography**: Clean, modern fonts
- **Logo**: Maxit branding with "Max" in white, "it" in black
- **Loading**: Progress bar animation from 0% to 100%
- **Transitions**: Smooth fade effects between screens

## 🏗️ Build Process

The project uses Huawei's fa-toolkit to compile `.ux` files into JavaScript bundles:

1. **Source**: QuickApp UX components (.ux files)
2. **Compilation**: fa-toolkit processes templates, styles, and scripts
3. **Output**: RPK package ready for Huawei AppGallery

## 🌟 Game Features

- **Interactive 3x3 Grid**: Responsive touch controls
- **Turn Management**: Alternating X and O players  
- **Win Detection**: Automatic winner identification
- **Game Reset**: Quick restart functionality
- **Status Updates**: Real-time game state display

## 🔧 Development

### Web Preview
Open `preview.html` in any modern browser to test the complete app experience without a Huawei device.

### QuickApp Testing
Install the generated `.rpk` file on Huawei devices or use Huawei Developer Tools.

## 📦 Deployment

1. **Build**: `npm run fa-build`
2. **Package**: Generated `.rpk` file in `/build/`
3. **Upload**: Submit to Huawei AppGallery Connect
4. **Publish**: Release to Orange Telecom users

## 🎯 Target Audience

- Orange Telecom customers
- Huawei device users
- Mobile gaming enthusiasts
- Professional mobile app users

## 📝 Version

**Current Version**: 1.0.0  
**Package**: com.orange.l3bmax  
**Developer**: Orange Telecom  

## 🤝 Contributing

This project represents Orange Telecom's commitment to innovative mobile experiences on the Huawei ecosystem.

---

**© 2025 Orange Telecom - L3bMax Avec Maxit** 🧡
