# Vastra & Co. 🧵✨

A high-end, immersive luxury textile website designed to showcase premium handwoven fabrics, sarees, and garments. This project features a state-of-the-art interactive 3D web experience built to impress.

## 🌟 Key Features

- **Immersive 3D Experience**: Features an interactive 3D T-shirt `.glb` model that responds naturally to user scrolling, powered by **Three.js**.
- **Cinematic Scroll Animations**: Smooth, scroll-driven choreography and seamless fade-out section transitions implemented via **GSAP & ScrollTrigger**.
- **Liquid Glass Aesthetics**: Premium UI design utilizing deep blur backdrop-filters, dynamic drop shadows, and high-saturation liquid glass morphism on all cards and forms.
- **Dynamic Day/Night Mode**: A beautifully orchestrated theme toggle that smoothly transitions the interface and the 3D WebGL background color between dark luxury mode and a light airy theme.
- **Photorealistic Imagery**: Integration of 8k AI-generated photorealistic textile macro-shots, including Kanjivaram silk, handloom cotton, and bridal collections.

## 🛠 Tech Stack

- **Core**: HTML5, Vanilla CSS, Vanilla JavaScript
- **3D Rendering**: [Three.js](https://threejs.org/) (r128), GLTFLoader
- **Animations**: [GSAP](https://gsap.com/) 3.12.5 & ScrollTrigger
- **Hosting**: Designed for continuous deployment via [Netlify](https://www.netlify.com/)

## 🚀 Running Locally

Because this project loads external 3D models (`.glb` files) and texture images, it must be run on a local HTTP server to avoid CORS (Cross-Origin Resource Sharing) security restrictions.

1. Clone the repository:
   ```bash
   git clone https://github.com/Senthil-Achievements/vastra-and-co.git
   cd vastra-and-co
   ```

2. Start a local server:
   - **Using Python 3**:
     ```bash
     python -m http.server 8080
     ```
   - **Using Node.js (npx)**:
     ```bash
     npx serve .
     ```

3. Open your browser and navigate to `http://localhost:8080` (or the port provided by your local server).

## 🌍 Deployment

This repository is optimized for deployment via **Netlify**. 
1. Connect your Netlify account to this GitHub repository.
2. Ensure the build command is left blank and the publish directory is set to `/` (the root directory).
3. Push changes to the `main` branch to trigger automatic continuous deployment.

---
*Crafted in Tamil Nadu, India.*
