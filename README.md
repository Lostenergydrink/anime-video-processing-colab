# Anime Video Processing Colab Notebook

This repository contains a Google Colab notebook for processing anime videos. The notebook includes separate modules for upscaling (increasing resolution) and frame interpolation (increasing framerate).

## Features

### Upscaling Module
- Increase resolution from 1080p to 4K using AI-based methods
- Optimized for anime content with models trained on animation
- Preserves color quality and details
- Multiple scaling options (2x, 3x, 4x)

### Frame Interpolation Module
- Increase framerate (24fps → 30/60/120fps)
- Uses RIFE algorithm optimized for anime
- Scene detection to prevent artifacts at cuts
- Multiple quality presets for different needs

## Usage

1. Open the notebook in Google Colab by clicking the badge:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Lostenergydrink/anime-video-processing-colab/blob/main/Anime_Video_Processing.ipynb)

2. Follow the instructions in the notebook to:
   - Mount your Google Drive
   - Upload your video files
   - Choose processing parameters
   - Run upscaling and/or interpolation

## Requirements

- Google account
- Google Drive space for input/output files
- Patience (processing can take time)

## Tips for Best Results

- For best results with limited resources, process in small chunks (1-2 minutes)
- Use the "low quality" preset for quick previews before processing entire videos
- Free Colab sessions have time limits; consider saving checkpoints

## License

MIT

## Acknowledgments

- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- [RIFE](https://github.com/hzwer/arXiv2020-RIFE)