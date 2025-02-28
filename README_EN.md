# 🎆 Fireworks Show Simulator

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</div>

<div align="center">
  <p>✨ A colorful web-based fireworks simulator offering an amazing audiovisual experience! ✨</p>
  <p><a href="README.md">Back to Home</a> | <a href="README_CN.md">中文版</a></p>
</div>

![Fireworks Display](https://via.placeholder.com/800x400?text=Fireworks+Show+Simulator)

## 📚 Table of Contents

- [✨ Project Introduction](#-project-introduction)
- [🎮 Features](#-features)
- [🚀 How to Use](#-how-to-use)
- [🔧 Technical Details](#-technical-details)
- [🎨 Customization Options](#-customization-options)
- [🤔 FAQ](#-faq)

## ✨ Project Introduction

Welcome to the magical world of the Fireworks Show Simulator! 🎉

This is an interactive fireworks simulator created with pure front-end technologies, allowing you to enjoy a spectacular fireworks display from the comfort of your home! Whether you want to add a festive atmosphere to special occasions or simply relax and enjoy beautiful visual effects, our fireworks simulator has got you covered!

Each firework is meticulously designed, with the entire process from launch to explosion being lifelike, accompanied by realistic sound effects to provide you with an immersive experience!

## 🎮 Features

### 🌈 Multiple Firework Effects

- **Circular Explosion**: Classic circular fireworks that expand evenly in all directions
- **Spherical Explosion**: Spherical fireworks with 3D effects for a more dimensional experience
- **Double Ring Explosion**: Two ring-shaped fireworks at different angles and colors blooming simultaneously
- **Burst Explosion**: Radial fireworks like shooting stars, trailing beautiful tails

### 🎭 Special Performance Modes

- **Ring Launch**: Multiple fireworks launched simultaneously in a ring formation
- **V-shaped Launch**: Fireworks launched in a V-shape pattern
- **Fan-shaped Launch**: Fireworks spread out in a fan shape, covering the sky
- **Parallel Line Launch**: Neat rows of fireworks launched simultaneously

### 🔊 Realistic Sound Effects

- Each firework explosion is accompanied by realistic explosion sound effects
- Adjustable volume to suit different scenarios

### ⏱️ Timed Performance

- 3-minute automatic fireworks show
- Countdown display with special visual cues during the last 10 seconds
- End-of-show message displayed when the performance concludes

## 🚀 How to Use

Using our fireworks simulator is very simple. Just follow these steps:

1. Open the `fire.html` file (can be opened directly in a browser)
2. Click the "Start Fireworks Show" button at the bottom of the interface
3. Sit back, relax, and enjoy the 3-minute spectacular fireworks display!
4. If you want to adjust the volume, use the volume slider at the bottom of the interface
5. You can click the "Stop Fireworks Show" button at any time to end the performance

💡 **Tip**: Viewing in full screen provides the best experience!

## 🔧 Technical Details

Our fireworks simulator uses the following technologies:

- **HTML5 Canvas**: Used to draw fireworks and particle effects
- **Web Audio API**: Generates realistic firework explosion sound effects
- **JavaScript ES6+**: Uses modern JavaScript features such as classes, arrow functions, etc.
- **CSS3**: Beautiful user interface and animation effects

Performance optimization measures:

- Automatic adjustment of particle count to ensure smooth operation on different devices
- Limited maximum canvas size to avoid excessive resource consumption on high-resolution devices
- Intelligent frame rate monitoring that automatically reduces effect complexity when performance is insufficient

## 🎨 Customization Options

Want to adjust the fireworks effects? Here are some parameters you can modify in the code:

- Adjust the `MAX_WIDTH` and `MAX_HEIGHT` variables to change the maximum canvas size
- Modify the `colors` array to change firework colors
- Adjust the initial value of `timeLeft` to change the performance duration (default is 180 seconds)
- Modify launch positions and target positions in the `createFirework` and `createSpecialFirework` functions

## 🤔 FAQ

**Q: Why can't I hear any sound?**

A: Modern browsers require user interaction with the page before playing sound. Make sure you've clicked the "Start Fireworks Show" button and check if the volume slider is adjusted to an appropriate level.

**Q: The fireworks display looks laggy. What can I do?**

A: Fireworks simulation requires certain computational resources. Try closing other resource-intensive programs, or reduce the number of particles in the code (modify the `particleCount` variable).

**Q: How can I embed this fireworks simulator on my website?**

A: Simply copy the code from the `fire.html` file to your website, ensuring you include all HTML, CSS, and JavaScript sections.

---

<div align="center">
  <p>🌟 We hope you enjoy this fireworks simulator! If you have any questions or suggestions, feel free to let us know! 🌟</p>
  <p>Created by: Fireworks Enthusiast Team 🚀</p>
</div>