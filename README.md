# WebGPU Use Cases Demo

A static HTML application showcasing various WebGPU capabilities with interactive examples.

## Features

This demo includes 7 interactive WebGPU examples:

1. **Basic Triangle** - Learn the fundamentals of WebGPU rendering
2. **Compute Shader** - Parallel computation on the GPU
3. **Particle System** - Simulate thousands of particles with GPU acceleration
4. **Image Filter** - Real-time image processing with fragment shaders
5. **Matrix Multiplication** - Accelerate linear algebra operations
6. **LLM Inference** - Visualize neural network inference
7. **Qwen Chat** - Full chat interface with Qwen LLM running in browser

## Requirements

- Modern browser with WebGPU support (Chrome 113+, Edge 113+)

## Running the Application

### Option 1: Open directly in browser
Simply open `index.html` in your browser.

### Option 2: Use a local web server (recommended)

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8080
```

Then open your browser to: http://localhost:8080

## Deploying to Static Hosting

This is a static HTML app that can be deployed to any static hosting service:

- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect your repository
- **Vercel**: Import your repository
- **Cloudflare Pages**: Connect your Git repository

## Browser Compatibility

WebGPU requires a compatible browser:
- ✅ Chrome 113+
- ✅ Edge 113+
- ✅ Firefox Nightly (with flags)
- ❌ Safari (not yet supported)

## Project Structure

```
webgpu/
├── index.html             # Main landing page
├── README.md              # This file
├── templates/
│   └── examples/
│       ├── triangle.html      # Basic triangle rendering
│       ├── compute.html       # Compute shader demo
│       ├── particles.html     # Particle system
│       ├── image-filter.html  # Image processing
│       ├── matrix-math.html   # Matrix multiplication
│       ├── llm-inference.html # LLM neural network inference
│       └── qwen-chat.html     # Qwen LLM chat interface
└── static/
    ├── css/
    │   └── style.css      # Shared styles
    └── js/                # (optional JS files)
```

## What is WebGPU?

WebGPU is a modern web API that provides low-level access to GPU capabilities for:
- **Graphics Rendering** - 3D graphics, games, visualizations
- **Compute Shaders** - General-purpose GPU computation (GPGPU)
- **Machine Learning** - Neural network inference
- **Image/Video Processing** - Real-time filters and effects
- **Scientific Computing** - Simulations and modeling

## License

MIT License
