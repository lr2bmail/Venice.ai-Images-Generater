# Venice.ai Image Generation

A sleek, browser-based tool for generating AI images using the [Venice.ai API](https://venice.ai/chat?ref=bwY1lo). Create single images or batches with customizable settings—no backend needed.

## Live Demo

Try it here: [https://lr2bmail.github.io/Venice.ai-Images-Generator/](https://lr2bmail.github.io/Venice.ai-Images-Generator/)

## Features

- **Flexible Generation**: Generate single images or batches (up to 50) with concurrent request support (1-10).
- **Advanced Options**: Customize prompts (positive/negative), style presets, models, aspect ratios, steps, and more.
- **Interactive Viewer**: Fullscreen lightbox with navigation for all generated images.
- **Download Options**: Save individual images or entire batches as ZIP files.
- **Persistent Settings**: API key and prompts saved via localStorage.
- **Client-Side**: Built with HTML, CSS, Bootstrap, and JavaScript—no server required.

## How It Works

Sends POST requests from your browser to the Venice.ai API. Uses JSZip for batch downloads and Bootstrap for a polished UI.

## Getting Started

### Prerequisites

- [Venice.ai API key](https://venice.ai/chat?ref=bwY1lo)
- Modern browser with JavaScript enabled
- Internet connection

### Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/lr2bmail/Venice.ai-Images-Generator.git
   cd Venice.ai-Images-Generator
   
2. Open index.html in a browser or visit the live demo.

### Usage

    - Enter your API key .
    - Set your prompt, negative prompt, and other parameters.
    - Click "Generate Images" to create and view results.

### Disclaimer

Unofficial tool, not affiliated with Venice.ai. Use at your own risk.
License

MIT License - see LICENSE for details.
