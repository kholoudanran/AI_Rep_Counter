---
title: AI Fitness Coach
emoji: 💪
colorFrom: green
colorTo: blue
sdk: gradio
sdk_version: 4.31.0
app_file: app.py
pinned: false
license: mit
---

# AI Fitness Coach 🏋️

Track your exercises in real-time using computer vision! This app uses MediaPipe pose detection to count reps and provide form feedback for squats, push-ups, and bicep curls.

## Features
- 🎥 **Live Webcam Tracking**: Real-time rep counting and form feedback
- 📁 **Video Upload**: Process pre-recorded exercise videos
- 📸 **Single Image Analysis**: Analyze individual poses
- 📊 **Detailed Statistics**: Track angles, stages, and rep counts

## How to Use
1. **Webcam Mode**: Allow camera access and start tracking
2. **Video Upload**: Upload an exercise video for processing
3. **Image Analysis**: Upload a single image for pose feedback

## Exercises Supported
- Squats 🏋️
- Push-ups 💪
- Bicep Curls 🔱

## Tips for Best Results
- Ensure good lighting
- Face the camera sideways for squats
- Position yourself fully in frame
- Wear contrasting clothing
- Start with slow, controlled movements

## Technical Details
Built with:
- MediaPipe for pose detection
- OpenCV for image processing
- Gradio for the web interface
- Deployed on Hugging Face Spaces

## License
MIT
