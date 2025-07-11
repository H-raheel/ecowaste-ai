# 🌱 EcoWaste AI - Organic Waste Analysis App

A smart, eco-friendly web application that uses AI to analyze organic waste photos and provide sustainable disposal solutions, composting tips, and environmental guidance.

![EcoWaste AI](./images/hero-screenshot.png)

## ✨ Features

- 📸 **Photo Upload & Analysis** - Drag & drop or click to upload organic waste images
- 🤖 **AI-Powered Analysis** - Advanced image recognition for waste identification
- ♻️ **Eco-Friendly Solutions** - Personalized composting and disposal recommendations
- 🌿 **Sustainable Tips** - Environmental best practices and waste reduction guidance
- 📱 **Responsive Design** - Beautiful, modern UI that works on all devices
- 🎨 **Intuitive Interface** - Clean, green-themed design with smooth animations

## 🚀 Quick Start

### Prerequisites

- Node.js 18.0 or higher
- npm or yarn package manager
- Python backend server (for AI analysis)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/my-organic-waste-app.git
   cd my-organic-waste-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js 14 (React)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Language**: JavaScript
- **Backend API**: Python FastAPI (separate service)

## 📁 Project Structure

```
my-organic-waste-app/
├── public/                 # Static assets
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
├── src/
│   ├── app/               # Next.js app directory
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.js
│   │   └── page.js
│   └── components/        # React components
│       └── OrganicWasteApp.js
├── images/                # Screenshots and documentation images
├── eslint.config.mjs      # ESLint configuration
├── jsconfig.json          # JavaScript configuration
├── next.config.mjs        # Next.js configuration
├── package.json           # Dependencies and scripts
├── postcss.config.mjs     # PostCSS configuration
└── README.md              # Project documentation
```

## 🎯 How It Works

1. **Upload Image**: Drag and drop or click to select an organic waste photo
2. **AI Analysis**: The image is sent to a Python backend for AI-powered analysis
3. **Get Results**: Receive personalized eco-friendly disposal recommendations
4. **Take Action**: Follow the sustainable solutions provided

![How It Works](./images/workflow-diagram.png)

## 🔗 API Integration

The app connects to a Python FastAPI backend running on `http://127.0.0.1:8000` with the following endpoint:

- **POST** `/describe-image` - Analyzes uploaded organic waste images

### Example API Response
```json
{
  "html": "<h2>Banana Peels</h2><p>These banana peels are perfect for composting...</p><ul><li>Add to compost bin</li><li>Mix with dry materials</li></ul>"
}
```

## 🎨 Design System

### Color Palette
- **Primary Green**: `#16a34a` (green-600)
- **Light Green**: `#f0fdf4` (green-50)
- **Dark Green**: `#166534` (green-800)
- **Accent Green**: `#15803d` (green-700)

### Key Components
- **File Upload Zone** - Drag & drop with visual feedback
- **Image Preview** - Responsive image display
- **Analysis Results** - Formatted HTML content with custom styling
- **Loading States** - Smooth animations and feedback

## 📱 Screenshots

### Main Interface
![Main Interface](./images/main-interface.png)

### File Upload
![File Upload](./images/file-upload.png)

### Analysis Results
![Analysis Results](./images/analysis-results.png)

### Mobile View
![Mobile View](./images/mobile-view.png)

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically

### Manual Deployment
```bash
npm run build
npm start
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Development Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
npm run lint:fix     # Fix ESLint issues
```

## 🌍 Environmental Impact

EcoWaste AI helps users:
- Reduce organic waste in landfills
- Create nutrient-rich compost
- Learn sustainable disposal methods
- Make environmentally conscious decisions

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file:
```env
NEXT_PUBLIC_API_URL=http://127.0.0.1:8000
```

### Tailwind CSS
Custom green theme configuration in `tailwind.config.js` for consistent eco-friendly branding.

## 📞 Support

- 📧 Email: support@ecowaste-ai.com
- 🐛 Issues: [GitHub Issues](https://github.com/yourusername/my-organic-waste-app/issues)
- 📖 Documentation: [Wiki](https://github.com/yourusername/my-organic-waste-app/wiki)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons by [Lucide](https://lucide.dev/)
- Styling by [Tailwind CSS](https://tailwindcss.com/)
- Framework by [Next.js](https://nextjs.org/)
- AI analysis powered by custom Python backend

---

Made with 💚 for a sustainable future
