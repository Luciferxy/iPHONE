
# iPHONE


**iPhone 3D Showcase** is an immersive web experience that brings Apple's iconic design to life through cutting-edge web technologies. This project combines React's dynamic UI capabilities with Three.js' powerful 3D rendering to create a responsive, interactive product showcase that mirrors Apple's premium aesthetic.


### Key Highlights:
- **Cinematic 3D Visualization**: Rotate, zoom, and explore photorealistic iPhone models with physics-based material rendering
- **Real-Time Customization**: Dynamically switch colors/materials while maintaining 60 FPS performance
- **Technical Showcase**:
  - WebGL-optimized 3D models with Draco compression
  - Smooth scroll-triggered animations using GSAP
  - Mobile-first responsive design with Tailwind CSS
- **Developer-Centric**:
  - Clean component architecture with React-Three-Fiber
  - Context API for cross-component state management
  - Vite-powered ultra-fast build system

**Why This Project?**  
This implementation demonstrates modern web development techniques for:
- Bridging 3D graphics with responsive UI design
- Implementing complex state management for 3D interactions
- Achieving Apple-level polish in web experiences
- Optimizing WebGL performance for consumer devices

**Perfect For**:
- E-commerce product demonstrations
- Interactive tech portfolios
- WebGL/Three.js learning resources
- Progressive Web App (PWA) implementations


## Demo

 http://localhost:5173/


## Features

## ✨ Features

### 🖥️ Core 3D Experience
- **Interactive 3D Viewer**  
  - 360° device rotation with touch/mouse controls  
  - Zoom/pan functionality with multi-touch gestures  
  - Dynamic camera angles for cinematic showcases  
- **Real-Time Customization**  
  - Swap colors/materials with instant visual feedback  
  - Metallic/glass PBR (Physically Based Rendering) materials  
  - Animated transitions between configurations  
- **Device Exploration**  
  - Exploded view of internal components  
  - Interactive spec highlights on hover/tap  
  - Scroll-activated component breakdown  

### 🎨 UI/UX Design
- **Apple-Inspired Interface**  
  - Minimalist typography and spacing  
  - Smooth parallax scrolling effects  
  - Dark/Light theme toggle with system preference detection  
- **Product Configurator**  
  - Storage capacity selector (128GB/256GB/512GB)  
  - Finish/material picker (Matte/Glossy/Ceramic)  
  - Real-time price calculator with currency conversion  
- **Immersive Animations**  
  - GSAP-powered scroll-triggered reveals  
  - Framer Motion micro-interactions  
  - Physics-based page transitions  

### ⚡ Technical Innovations
- **Three.js Optimization**  
  - GLTF models compressed with Draco (70% size reduction)  
  - Automatic LOD (Level of Detail) switching  
  - Smart texture loading with Suspense fallbacks  
- **React Integration**  
  - Context API for global state management  
  - Custom hooks for 3D interaction logic  
  - Code-split components for faster loads  
- **Performance First**  
  - 60 FPS rendering on mid-tier devices  
  - Intersection Observer lazy loading  
  - GPU-accelerated animations  

### 📱 Mobile Excellence
- Progressive Web App (PWA) ready  
- Touch-optimized 3D controls  
- Offline-first caching strategy  
- Battery-efficient rendering  

### 🛠️ Developer Tools
- Hot module replacement for 3D components  
- Visual debugging overlay for Three.js scenes  
- Automated model optimization pipeline  
- CI/CD with Vercel/Netlify integration  

## Installation

## ⚙️ Installation

### Prerequisites
- Node.js (v18 or higher)
- npm (v9 or higher) or yarn (v1.22 or higher)
- Git (for cloning the repository)

###  Clone the Repository and run
```bash
git clone https://github.com/your-username/iphone-3d-website.git
cd iphone-3d-website

npm install
# or
yarn install

npm install three @react-three/fiber @react-three/drei
# or
yarn add three @react-three/fiber @react-three/drei

cp .env.example .env

npm run dev
# or
yarn dev

http://localhost:5173
