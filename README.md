# FrameAI – AI Storyboard Generator

Generate 4-panel cinematic storyboards from any concept in seconds.

## Features

- **Concept Input** → 4-panel storyboard with titles, captions, images
- **Flux Image API** → Cinematic 16:9 images per panel
- **Text API** → AI-generated scene titles, prompts, and narratives
- **Per-panel Regeneration** → Reroll individual panels with different seeds
- **PNG Export** → Composite all 4 panels into one downloadable image via Canvas API
- **Shareable URLs** → Hash-encoded concepts for sharing storyboards
- **6 Visual Styles** → Cinematic, Concept Art, Watercolor, Noir, Anime, 3D

## Tech Stack

- **APIs:** Pollinations.AI (image.pollinations.ai + text.pollinations.ai)
- **Frontend:** Vanilla JS + CSS (no dependencies)
- **Deployment:** GitHub Pages (100% client-side)

## How to Use

1. Enter a story concept (e.g., "astronaut lost on alien planet")
2. Click **Generate**
3. Wait for 4 Flux images to render
4. Regenerate individual panels if desired
5. Export as PNG or share via URL

## Live Demo

[https://funvidzz.github.io/frameai](https://funvidzz.github.io/frameai)

## API Credits

- Image generation: [Flux](https://pollinations.ai)
- Text generation: [Pollinations Text API](https://pollinations.ai)
- No backend required, runs entirely in the browser

## License

MIT
