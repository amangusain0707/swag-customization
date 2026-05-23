# 3D Swag Customization App

An interactive 3D T-shirt customizer built with React and Three.js, 
featuring AI-powered design generation via DALL-E API.

## Live Demo
[streetstitch.netlify.app]

## Features
- 3D T-shirt model rendered in real time using React Three Fiber and GLTF
- Smooth color transitions with damped easing via Drei
- Logo and full-texture decal placement on the 3D model
- Mouse-driven shirt rotation through a custom CameraRig
- AI design generation from text prompts using DALL-E API
- Custom image file upload and apply as logo or full texture
- Download final design as canvas image
- Responsive camera positioning for mobile and desktop
- Global state management with Valtio proxy store
- Smooth UI animations with Framer Motion

## Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, Framer Motion
- **3D Rendering:** Three.js, React Three Fiber, Drei
- **AI:** DALL-E API (OpenAI)
- **State Management:** Valtio
- **Backend:** Node.js, Express (API proxy for DALL-E)

## Getting Started

### Prerequisites
- Node.js v18+
- OpenAI API key

### Installation

```bash
# Clone the repo
git clone https://github.com/amangusain0707/swag-customization.git
cd swag-customization

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

### Environment Setup
Create a `.env` file in the `/server` folder:

### Run the App

```bash
# Start backend (from /server)
npm start

# Start frontend (from /client)
npm run dev
```

Frontend runs on `http://localhost:5173`  
Backend runs on `http://localhost:8080`

## Project Structure

swag-customization/

├── client/         # React frontend

│   ├── src/

│   │   ├── canvas/     # Three.js 3D components

│   │   ├── components/ # UI components

│   │   ├── config/     # State, motion config

│   │   └── pages/      # Home, Customizer

└── server/         # Node.js + Express backend


## Author
**Aman Gusain**  
[LinkedIn](https://www.linkedin.com/in/aman-gusain-298310258) • 
[GitHub](https://github.com/amangusain0707)
