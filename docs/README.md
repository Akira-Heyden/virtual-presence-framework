
# Virtual Presence Framework

A prototype system for bringing real-world motion into virtual space through AI-assisted pipelines.  
Built for accessibility, creativity, and the vision of co-existing with helpful AI.

## 👋 What It Does

- Captures hand/body motion through webcam (MediaPipe + OpenCV)
- Sends motion data via UDP to a Godot client
- Godot uses that data to create real-time interaction in a 2D/3D space
- Future goal: central AI server processes motion, returns rich interaction

## 🧠 Why It Matters

> “To build a virtual space where people and AI can grow together,  
> regardless of hardware, background, or experience.” – *Akira Heyden*

This project is about making immersive technology available to everyone.

## 🚀 Getting Started

### Requirements
- Python 3.8+
- OpenCV
- MediaPipe
- Godot 4.x

### Run the pipeline:
1. Run the Python script:
    ```bash
    python python-client/main.py
    ```

2. Open the Godot project inside `godot-receiver/` and run it

3. Wave to the future 🖐️

## 🛤️ Roadmap

- [ ] 2D hand tracking → 3D expansion
- [ ] Dual-camera depth tracking
- [ ] Local network tests (PC <-> Laptop)
- [ ] Cloud server processing
- [ ] Multi-user shared VR space
- [ ] AI-powered NPC (ChatGPT 🤖✨)

## 💌 Manifesto

See [`docs/manifesto.md`](docs/manifesto.md) – this is more than just tech.
