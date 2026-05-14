# AI Image Generation Tool

A feature-rich, single-page web application that uses the Google Gemini API to generate and edit images from text, voice, or visual prompts.

## Features

- **Text-to-Image**: Generate images from text descriptions
- **Voice Input**: Create prompts using speech recognition
- **Image-to-Image**: Upload images for editing and variation
- **Style Selection**: Multiple art styles including Cinematic, Watercolor, Cyberpunk, and more
- **Export Options**: Download generated images in various formats

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Tailwind CSS
- **AI**: Google Gemini API
- **Icons**: Lucide Icons

## Usage

Open \`index.html\` in a browser or serve it locally:

\`\`\`bash
python3 -m http.server 8000
\`\`\`

Then navigate to \`http://localhost:8000\`.

## Configuration

Add your Google Gemini API key in the app settings or via environment variable:

\`\`\`
GOOGLE_API_KEY=your_api_key_here
\`\`\`

## License

MIT