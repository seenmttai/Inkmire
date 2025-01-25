# Portfolio Builder

Transform your PDF CV into an interactive portfolio website with one click. Live demo: [inkmire.pages.dev](https://inkmire.pages.dev)

## Key Features

- **Drag-and-drop PDF processing** - Supports both click upload and drag-and-drop interactions
- **Live HTML preview** - Interactive iframe preview of generated portfolio
- **Client-side processing** - PDF conversion happens in your browser using PDF.js

## How It Works

1. Upload a PDF CV (1+ pages supported)
2. PDF.js converts pages to JPEG images
3. Images are sent to AI processing endpoint
4. Generated HTML is rendered in live preview
5. Download clean HTML file with one click

## Tech Stack

- Built with React (CDN version) + Babel Standalone
- PDF processing via [pdf.js](https://mozilla.github.io/pdf.js/)
- UI animations powered by [AOS Library](https://michalsnik.github.io/aos/)
- Styled with Tailwind CSS + custom glassmorphism effects
- Cloudflare Worker backend for AI processing
