# AI Image Generator

A web-based AI image generator that uses Hugging Face’s Inference API to create stunning images from text prompts. Users can select the model, aspect ratio, and number of images, and download the generated results.

---

## Features

- Generate multiple images from a single prompt
- Choose AI models (e.g., Stable Diffusion)
- Select image aspect ratios (1:1, 16:9, 4:3, etc.)
- Download generated images
- Random example prompts for inspiration
- Dark/light theme toggle
- Animated loading indicators
- Responsive and clean UI

## Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/reddypavan2k/ai-image-generator.git
cd ai-image-generator
\`\`\`

2. Open \`index.html\` in your browser. No backend is required; the app runs entirely client-side.

3. Add your Hugging Face API key in \`script.js\`:
\`\`\`javascript
const API_KEY = "YOUR_HUGGING_FACE_API_KEY";
\`\`\`

---

## Usage

1. Enter a prompt in the input box or click the dice button for a random prompt.  
2. Select the model, aspect ratio, and number of images.  
3. Click **Generate**.  
4. Wait for the images to appear. Download each image using the download button.

---

## Example Prompts

- A magic forest with glowing plants and fairy homes among giant mushrooms  
- A steampunk airship floating through golden clouds at sunset  
- An underwater kingdom with merpeople and glowing coral buildings  
- A cyberpunk city with neon signs and flying cars at night  

*(Full list included in \`script.js\`)*

---

## Dependencies

- [Hugging Face Inference API](https://huggingface.co/inference-api)  
- [Font Awesome](https://fontawesome.com/) for icons  
- Vanilla HTML, CSS, and JavaScript

---

## Notes

- Ensure your Hugging Face API key has **Inference API access**.  
- Some models require you to **accept the model license** on Hugging Face before use.  
- For production, consider using a **server proxy** to keep your API key secure instead of exposing it client-side.

---

## Troubleshooting

**Error:** \`This authentication method does not have sufficient permissions\`  

- Use an API key with the correct **Inference API permissions**.  
- Accept the model license on Hugging Face if required.  
- Check your token scopes in your Hugging Face account settings.