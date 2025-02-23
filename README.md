
# Venice.ai Images Generater

An unofficial, browser-based image generator that uses the [Venice.ai API](https://venice.ai) to convert text prompts into images. With support for single image generation and batch creation (10 images at a time), this tool runs entirely in your web browser—no backend required.

## Live Demo

Test the tool live here:  
[https://lr2bmail.github.io/Venice.ai-Images-Generater/](https://lr2bmail.github.io/Venice.ai-Images-Generater/)

## Features

- **Single Image Generation:** Generate an image from a text prompt and view it immediately.
- **Batch Image Generation:** Create 10 images in one go and download them as a ZIP file.
- **API Key Management:** Enter your API key and have it automatically prefixed with `"Bearer "`.
- **Persistent Settings:** Your API key and prompt are saved in your browser's localStorage, so they persist across sessions.
- **No Backend Required:** All processing is done on the client side using HTML, CSS, and JavaScript.

## How It Works

This tool sends POST requests directly from your browser to the Venice.ai API. You enter your desired image parameters (prompt, style, dimensions, etc.), and the tool handles the API calls. For batch generation, it packages the images into a ZIP file using JSZip.

## Getting Started

### Prerequisites

- A valid [Venice.ai API](https://venice.ai) key.
- A modern web browser with JavaScript enabled.
- An active internet connection.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/lr2bmail/Venice.ai-Images-Generater.git
   cd Venice.ai-Images-Generater
   ```

2. **Open the Application:**

   Open the `index.html` file in your web browser or simply visit the [live demo](https://lr2bmail.github.io/Venice.ai-Images-Generater/).

### Usage

1. **Enter Your API Key:**  
   Input your Venice.ai API key into the designated field. The tool will automatically prepend `"Bearer "` if it isn't already included.

2. **Customize Your Request:**  
   Adjust the prompt, style preset, safe mode, model, image dimensions, steps, and watermark options as desired.

3. **Generate Images:**  
   - Click **Generate Image** to create and view a single image.
   - Click **Generate 10 Images and Save** to generate a batch of 10 images, which will then be packaged into a ZIP file and downloaded automatically.

## Disclaimer

This is an unofficial tool and is not affiliated with or endorsed by Venice.ai. Use at your own risk.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
