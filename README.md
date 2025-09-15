# 🚀 Kapranchuk Taras - 3D Interactive Portfolio

A cutting-edge, interactive 3D portfolio built with React Three Fiber, featuring immersive WebGL experiences, custom shaders, and smooth animations. This portfolio showcases both technical expertise and creative design through an engaging virtual environment.

![Portfolio Preview](public/logo.png)

## ✨ Live Demo

🌐 **Visit the live portfolio:** [https://github.io/KapranchukTaras/threePortfolio](https://github.io/KapranchukTaras/threePortfolio)

## 🎯 Features

### 🎨 **Immersive 3D Experience**
- **Interactive 3D Environment**: Navigate through a custom-built virtual room with clickable objects
- **Dual World System**: Seamless transition between two different 3D environments
- **Custom Shaders**: Advanced GLSL shaders for stunning visual effects
- **Real-time Animations**: Smooth camera transitions and object interactions

### 🎮 **Interactive Elements**
- **Clickable 3D Objects**: Laptop, city screen, and mystical gate for project navigation
- **Dynamic Camera Controls**: Smooth orbital camera with custom constraints
- **Mouse-responsive Grid**: Interactive particle system that responds to mouse movement
- **Gate Transition Effects**: Custom fisheye distortion effects for world transitions

### 🎭 **Visual Effects**
- **Custom Shader Materials**: Animated gate with spinning, glowing effects
- **Post-processing Pipeline**: Advanced visual effects and bloom
- **Particle Systems**: Dynamic star field and interactive grid
- **Smooth Animations**: GSAP-powered transitions and micro-interactions

### 📱 **User Experience**
- **Responsive Design**: Optimized for various screen sizes
- **Loading Experience**: Custom loader with progress tracking
- **Smooth Scrolling**: Locomotive scroll integration
- **Performance Optimized**: Efficient rendering with React Three Fiber

## 🛠️ Technology Stack

### **Frontend Framework**
- **React 18.3.1** - Modern React with hooks and context
- **Vite 5.3.4** - Fast build tool and development server

### **3D Graphics & WebGL**
- **Three.js 0.167.1** - Core 3D graphics library
- **React Three Fiber 8.18.0** - React renderer for Three.js
- **React Three Drei 9.121.4** - Useful helpers for R3F
- **React Three Cannon 6.6.0** - Physics integration
- **Cannon-es 0.20.0** - Physics engine

### **Animation & Effects**
- **GSAP 3.12.7** - Professional animation library
- **Framer Motion 12.4.1** - React animation library
- **Locomotive Scroll 4.1.4** - Smooth scrolling
- **Postprocessing 6.36.7** - Advanced visual effects

### **Shaders & Graphics**
- **GLSL Shaders** - Custom vertex and fragment shaders
- **Vite Plugin GLSL** - GLSL shader support
- **GL Noise 1.6.1** - Procedural noise generation

### **Development Tools**
- **ESLint** - Code linting and formatting
- **GitHub Pages** - Deployment platform
- **Leva 0.9.35** - Debug UI for development

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/KapranchukTaras/threePortfolio.git
   cd threePortfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the portfolio

### Build for Production

```bash
npm run build
```

### Deploy to GitHub Pages

```bash
npm run deploy
```

## 📁 Project Structure

```
threePortfolio/
├── public/
│   ├── models/           # 3D models (.glb files)
│   ├── website/          # Embedded project demos
│   ├── videos/           # Video assets
│   ├── sounds/           # Audio files
│   └── imgs/             # Image assets
├── src/
│   ├── CSS/              # Stylesheets
│   │   ├── index.css     # Global styles
│   │   ├── htmll.css     # HTML overlay styles
│   │   └── loader.css    # Loading screen styles
│   ├── shaders/          # GLSL shader files
│   │   └── gate/         # Gate transition shaders
│   ├── helpers/          # Utility components
│   ├── App.jsx           # Main application component
│   ├── World.jsx         # Primary 3D world
│   ├── World2.jsx        # Secondary 3D world
│   ├── Projects.jsx      # Interactive project grid
│   ├── Html.jsx          # HTML overlay content
│   ├── Controls.jsx      # Camera and interaction controls
│   ├── Effects.jsx       # Post-processing effects
│   └── Loader.jsx        # Loading screen
└── package.json          # Dependencies and scripts
```

## 🎨 Key Components

### **World.jsx** - Main 3D Environment
- Interactive 3D room with clickable objects
- Custom shader materials for visual effects
- GSAP animations for smooth transitions
- Mouse interaction handling

### **World2.jsx** - Secondary Environment
- Alternative 3D space accessible via gate
- Different lighting and atmosphere
- Seamless transition effects

### **Projects.jsx** - Interactive Grid
- 400-instance particle system
- Mouse-responsive animations
- Dynamic height calculations
- Performance-optimized rendering

### **Html.jsx** - Content Overlay
- Portfolio information and navigation
- Smooth scroll animations
- Responsive design elements
- Contact information display

### **Effects.jsx** - Visual Effects
- Post-processing pipeline
- Custom fisheye distortion
- Bloom and lighting effects
- Transition animations

## 🎯 Interactive Features

### **Navigation System**
- **Laptop Object**: Navigate to project showcase
- **City Screen**: Access urban development projects
- **Mystical Gate**: Enter alternative 3D environment
- **Back Button**: Return to main view

### **Camera Controls**
- **Orbital Camera**: Smooth rotation and zoom
- **Custom Constraints**: Limited movement ranges
- **Animated Transitions**: GSAP-powered camera movements
- **Free Mode**: Unrestricted camera exploration

### **Visual Effects**
- **Custom Shaders**: Animated gate with spinning effects
- **Particle Systems**: Dynamic star field and interactive grid
- **Post-processing**: Bloom, distortion, and lighting effects
- **Smooth Transitions**: Seamless world switching

## 📊 Performance Optimizations

- **Instanced Rendering**: Efficient particle system rendering
- **Frustum Culling**: Optimized object visibility
- **Shader Optimization**: Efficient GLSL code
- **Asset Compression**: Optimized 3D models and textures
- **Lazy Loading**: Progressive asset loading

## 🌐 Deployment

The portfolio is deployed on GitHub Pages and includes:
- **Visitor Counter**: Real-time analytics tracking
- **Responsive Design**: Mobile-optimized experience
- **Performance Monitoring**: Built-in performance tools
- **SEO Optimization**: Meta tags and structured data


## 📄 License

This portfolio is licensed under a [Creative Commons BY-NC-ND 4.0 License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You may share this work with proper credit, but you may not use it commercially or modify it without permission.

## 🙏 Acknowledgments

- **Three.js Community** - For the amazing 3D graphics library
- **React Three Fiber Team** - For the excellent React integration
- **GSAP Team** - For the powerful animation library
- **Open Source Community** - For all the amazing tools and libraries

---

**Built with ❤️ using React, Three.js, and modern web technologies**

