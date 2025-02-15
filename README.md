# AI Photo Generator

## Overview
AI Photo Generator is a desktop application that allows users to generate AI-generated stock images based on specified themes. The app supports:
- Single-theme and multi-theme image generation
- Saving and managing themes
- Configuring an API key for OpenAI's DALL·E model

## Installation
1. **Download the executable**
   - Ensure you have downloaded the `AI_Photo_Generator.exe` file.

2. **Run the application**
   - Double-click on `AI_Photo_Generator.exe` to launch the program.

## Usage

### 1. Configuration Setup
Before generating images, you need to configure your API key and themes.

- **Open the "Config" tab**
  - Enter your OpenAI API Key in the provided text box.
  - Add themes by typing in the text box and clicking **"Add Theme"**.
  - Remove themes by selecting a theme from the list and clicking **"Remove Selected Theme"**.
  - Click **"Save Config"** to save your changes.

### 2. Generating Images

- **Open the "Generation" tab**
  - Select a theme from the dropdown list.
  - Set the number of images to generate (1-20).
  - Click **"Start (Single Theme)"** to generate images for the selected theme.
  - Click **"Start (All Themes)"** to generate images for all saved themes (6 images per theme).
  - The progress and status updates will appear in the log section.

### 3. Viewing Generated Images
- Images are saved in the `generated_images` folder, categorized by theme.
- The images are upscaled to 2048x2048 resolution and saved as `.jpg` files.

## Troubleshooting
- **API Key Missing**: Ensure you have entered a valid OpenAI API Key in the Config tab.
- **No Theme Selected**: Add and select a theme before starting generation.
- **Slow Generation**: The OpenAI API has rate limits, causing delays between image requests.
- **Application Crashes**: Ensure you have a stable internet connection and the correct API key.

## Notes
- This application relies on OpenAI's DALL·E 3 for image generation.
- Ensure you comply with OpenAI's terms of service while using AI-generated images.

## Contact
For issues or feedback, feel free to contact the gmail "kolyatro080589@gmail.com".

