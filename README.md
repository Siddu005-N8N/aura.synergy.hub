# 🌟 Aura Synergy Hub - Frontend

> **Modern Student Success Platform** - Track coding progress, manage wellness, and plan your career journey

## ✨ Features

### 🎨 **Modern Design System**
- **Glassmorphism UI** - Beautiful glass-effect components
- **Custom Aura Branding** - Unique purple gradient theme
- **Dark Mode Optimized** - Elegant dark space theme
- **Responsive Design** - Perfect on all devices

### 🚀 **Performance Optimized**
- **Code Splitting** - Optimized bundle sizes
- **Lazy Loading** - Fast initial page loads
- **Modern Build Tools** - Vite + SWC for lightning-fast builds
- **SEO Ready** - Proper meta tags and descriptions

### 🎯 **Core Functionality**
- **Dashboard Analytics** - Real-time coding statistics
- **Day Tracker** - Daily progress monitoring
- **Mental Wellness Coach** - AI-powered mental health support
- **Physical Wellness Coach** - Health metrics and coaching
- **Career Roadmaps** - Interactive learning paths

## 🛠️ Tech Stack

- **Framework**: React 18 + TypeScript
- **Build Tool**: Vite with SWC
- **Styling**: Tailwind CSS + Custom Design System
- **UI Components**: Radix UI + shadcn/ui
- **State Management**: React Context + TanStack Query
- **Routing**: React Router v6
- **Charts**: Recharts
- **Forms**: React Hook Form + Zod validation

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Base UI components (shadcn/ui)
│   ├── dashboard/      # Dashboard-specific components
│   └── Layout.tsx      # Main layout component
├── pages/              # Route components
├── lib/                # Utilities and API client
├── contexts/           # React contexts
├── hooks/              # Custom React hooks
└── styles/             # Global styles and themes
```

## 🎨 Design System

### Color Palette
- **Primary**: Purple gradient (#8b5cf6 → #c084fc)
- **Mental Health**: Cyan accent (#22d3ee)
- **Physical Health**: Green accent (#10b981)
- **Career**: Magenta accent (#e879f9)

### Components
- **Glass Cards** - Backdrop blur with subtle borders
- **Gradient Text** - Animated gradient text effects
- **Floating Animations** - Subtle hover and focus states
- **Progress Rings** - Animated circular progress indicators

## 🔧 Configuration

### Environment Variables

**Development (.env):**
```env
VITE_API_BASE_URL=http://localhost:3001/api
VITE_APP_NAME=Aura Synergy Hub
VITE_APP_VERSION=1.0.0
```

**Production (.env.production):**
```env
VITE_API_BASE_URL=https://your-backend.onrender.com/api
VITE_APP_NAME=Aura Synergy Hub
VITE_APP_VERSION=1.0.0
```

### Build Configuration

The Vite configuration is optimized for:
- **Development**: Fast HMR and debugging
- **Production**: Optimized bundles with code splitting
- **Deployment**: Render-compatible settings

## 📦 Build Output

Optimized production build creates:
- **Vendor chunk**: React ecosystem (141KB gzipped: 45KB)
- **UI chunk**: Component library (83KB gzipped: 28KB)
- **Charts chunk**: Visualization library (0.4KB)
- **Main chunk**: Application code (331KB gzipped: 85KB)

**Total size**: ~555KB (173KB gzipped) ⚡

## 🚀 Deployment

See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed deployment instructions.

### Quick Deploy to Render

1. **Static Site** (Recommended):
   ```
   Root Directory: Frontend
   Build Command: npm install && npm run build
   Publish Directory: dist
   ```

2. **Environment Variables**:
   - `VITE_API_BASE_URL`: Your backend API URL

## 🎯 Performance Features

- ✅ **Optimized Images** - WebP format with fallbacks
- ✅ **Code Splitting** - Route-based and component-based
- ✅ **Tree Shaking** - Unused code elimination
- ✅ **Lazy Loading** - Components loaded on demand
- ✅ **Caching Strategy** - Efficient browser caching
- ✅ **Bundle Analysis** - Optimized chunk sizes

## 🔐 Security Features

- ✅ **Environment Variables** - Secure API configuration
- ✅ **CORS Protection** - Proper cross-origin handling
- ✅ **Input Validation** - Zod schema validation
- ✅ **XSS Protection** - React's built-in protections
- ✅ **HTTPS Ready** - Production-ready security headers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.

---

**Built with ❤️ using modern web technologies for optimal user experience**
