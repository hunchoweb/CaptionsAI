# Captions AI

A modern AI-powered creative studio website built with Vite, featuring responsive design and smooth animations.

## Features

- **AI-powered video creation**: Create studio-grade videos with AI assistance
- **Responsive design**: Optimized for desktop, tablet, and mobile devices
- **Modern animations**: Smooth transitions and interactive elements
- **Performance optimized**: Fast loading with optimized assets and lazy loading

## Tech Stack

- **Vite**: Fast build tool and development server
- **SCSS**: Advanced CSS preprocessing with PostCSS
- **Vanilla JavaScript**: Modern ES6+ features
- **PostCSS**: CSS processing with plugins for SVG loading and responsive typography

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd Captions-AI
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser to see the result.

## Project Structure

```
Captions-AI/
├── public/
│   ├── assets/          # Static assets (images, videos, SVGs)
│   └── fonts/           # Font files
├── src/
│   ├── js/              # JavaScript modules
│   └── scss/            # SCSS stylesheets
├── index.html           # Main HTML file
├── vite.config.js       # Vite configuration
└── package.json         # Dependencies and scripts
```

## Build for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

The built files will be in the `dist/` directory.

## Deploy on Vercel

The easiest way to deploy this Vite app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=vite&utm_source=create-vite&utm_campaign=create-vite-readme) from the creators of Vercel.

Check out the [Vite deployment documentation](https://vitejs.dev/guide/static-deploy.html) for more details.

## Development

### SCSS Architecture

The project uses a well-organized SCSS architecture:

- `abstracts/`: Variables, mixins, functions, and animations
- `base/`: Reset, typography, and base styles
- `layout/`: Component-specific styles
- `utilities/`: Utility classes and overrides

### Asset Management

- Static assets are located in `public/assets/`
- SVG files are loaded using PostCSS inline SVG plugin
- Images and videos are optimized for web delivery

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
