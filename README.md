# WebGPU Use Cases Demo

A Flask application showcasing various WebGPU capabilities with interactive examples.

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

- Python 3.8+
- Modern browser with WebGPU support (Chrome 113+, Edge 113+)

## Installation

```bash
# Create virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Running the Application

```bash
# Activate virtual environment if not already active
source venv/bin/activate

# Run the Flask app
python app.py
```

Then open your browser to: http://localhost:5000

## Browser Compatibility

WebGPU requires a compatible browser:
- ✅ Chrome 113+
- ✅ Edge 113+
- ✅ Firefox Nightly (with flags)
- ❌ Safari (not yet supported)

## Project Structure

```
webgpu/
├── app.py                  # Flask application
├── requirements.txt        # Python dependencies
├── templates/
│   ├── index.html         # Main landing page
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
# webgpu
