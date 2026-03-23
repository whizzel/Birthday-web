# 🎂 Birthday Cake from Crush

A romantic 3D birthday celebration experience built with React Three Fiber - an interactive digital surprise for your special someone!

## ✨ Features

- **🎬 Interactive 3D Scene** - Beautiful animated birthday cake, candle, and dining table
- **🎯 Personalized Messages** - Typing animation with custom birthday wishes
- **🕯 Realistic Candle** - Animated flame with custom shaders and flickering effects
- **🎆 Fireworks** - Particle-based celebration when you blow out the candle
- **🖼️ Photo Memories** - Interactive picture frames with your special moments
- **🎵 Background Music** - Romantic soundtrack to set the mood
- **🎮 Easy Controls** - Click or press spacebar to interact

## 🛠️ Tech Stack

- **React 19** + **TypeScript** - Modern frontend development
- **Three.js** - 3D graphics and animations
- **@react-three/fiber** & **@react-three/drei** - React renderer for Three.js
- **Vite** - Fast development server
- **GLB 3D Models** - Professional 3D assets
- **Custom Shaders** - Realistic candle flame effects

## 🚀 Quick Start

```bash
# Clone the repository
git clone <your-repo-url>
cd birthday-cake-from-crush

# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:5173 in your browser
```

## 🎮 How to Use

1. **Click anywhere or press spacebar** to start the experience
2. **Watch the animation** - cake descends, table slides in, candle drops
3. **Click or press spacebar again** to blow out the candle and trigger fireworks
4. **Use mouse to orbit** around the scene and explore
5. **Click on photo frames** and birthday cards for closer look

## 🎨 Customization

### Personalize the Messages
Edit `src/App.tsx` to customize the birthday message:

```typescript
const TYPED_LINES = [
  "> [Name]",           // Change the name
  "...",
  "> today is your birthday",
  "...",
  "> [Your custom message]",
  "...",
  "٩(◕‿◕)۶ ٩(◕‿◕)۶ ٩(◕‿◕)۶"
];
```

### Replace Photos
Replace the images in `public/` folder:
- `frame1.jpg`, `frame2.jpg`, `frame3.jpg`, `frame4.jpg` - Your memories
- `card.png` - Birthday card design
- `music.mp3` - Background music

### 3D Models
The 3D models are located in `public/`:
- `cake.glb` - Birthday cake
- `candle.glb` - Candle with holder
- `table.glb` - Dining table
- `picture_frame.glb` - Photo frame

## 🌟 Highlights

- **Smooth Animations** - Carefully choreographed scene transitions
- **Realistic Physics** - Fireworks with gravity and particle effects
- **Responsive Design** - Works on all screen sizes
- **Performance Optimized** - Efficient Three.js rendering
- **Interactive Elements** - Hover states, click handlers, and smooth transitions

## 🎯 Perfect For

- Birthday surprises for your loved ones
- Anniversary celebrations
- Special romantic gestures
- Learning React Three Fiber
- 3D web development projects

## 💝 Made with Love

This project combines technical creativity with romantic sentiment to create an unforgettable birthday experience. Every detail - from the flickering candle flame to the particle fireworks - is crafted with care.

---

**🎉 Create magical moments with code!**

## 📄 License

MIT License - feel free to use and modify for your own celebrations!
# Birthday-web
