# AI-Image-generation
ImaginAIry is a sleek, responsive web app that turns text into stunning AI-generated images using various state-of-the-art models from Hugging Face. Built with vanilla JavaScript, HTML, and CSS, this project lets users describe imaginative scenes and instantly bring them to life through generative art.

 Features
Prompt-to-Image Generation: Enter any description—wild, poetic, or realistic—and get AI-rendered images tailored to your input.

Model Selection: Choose from several popular models like Stable Diffusion, Openjourney, and FLUX.1 variants for different artistic styles and rendering qualities.

Aspect Ratio Customization: Select between square, landscape, or portrait ratios, dynamically generating dimensions tailored for the model.

Multiple Image Output: Generate up to four images per prompt to explore diverse interpretations.

Dark/Light Mode: Seamlessly toggle between themes, with automatic system preference detection.

Prompt Dice: Stuck? Tap the 🎲 to autofill a creative prompt from a curated list of examples.

🛠️ How It Works
Users enter a prompt or use the randomizer.

They select the preferred model, image count, and aspect ratio.

On submission, the app:

Creates loading placeholders,

Calls Hugging Face's inference API with custom dimensions,

Renders and displays generated images with download links.

🚀 Tech Stack
Frontend: Vanilla JS, HTML5, CSS3

Icons: Font Awesome

API: Hugging Face Inference Endpoint (supports token-authenticated POST requests)

Responsive Design: Optimized for both desktop and mobile

Note: API keys are abstracted out via config.js. Ensure your key is kept secure and excluded from version control using .gitignore.

📸 Try imagining:
“A floating castle above a sea of clouds, glowing with bioluminescent lights at dusk.”

Let your imagination paint pixels. 🌌

