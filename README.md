# Snap2Slides

**Transform images and documents into PowerPoint presentations using AI**

A Next.js web app that uses Google Gemini Vision API to analyze images and generate presentation slides.

## Live Demo

- **Try it:** [snap2slides.me](https://snap2slides.me)
- **Demo video:** [YouTube](https://www.youtube.com/watch?v=G8rV8L0Eo_A)

## What It Does

- Upload images, PDFs, or documents
- AI analyzes content and creates slide text
- Download as PowerPoint (.pptx)
- Works on mobile and desktop

## Built With

- **Frontend:** Next.js 14, TypeScript, Tailwind CSS
- **AI:** Google Gemini Vision API
- **File Processing:** PDF parsing, image analysis
- **Deployment:** Vercel

## Development Journey

Built over 3 weeks as a learning project:

- **Week 1:** Set up Next.js, integrated Gemini API
- **Week 2:** Added file upload, PowerPoint generation
- **Week 3:** Mobile optimization, deployment

### Key Challenges

- Learning to work with AI APIs
- Handling different file formats
- Making it work reliably on mobile
- Deploying and managing API quotas

## Quick Start

```bash
# Clone and install
git clone https://github.com/SaurabhCodesAI/snap2slides.git
cd snap2slides
npm install

# Set up environment
cp .env.example .env.local
# Add your Google Gemini API key

# Run development server
npm run dev
```

Visit http://localhost:3000

## Features

- Multi-file upload (images, PDFs, Word, PowerPoint)
- Real-time processing progress
- Professional slide layouts
- Mobile-responsive design
- Download as editable PowerPoint

## Project Structure

```
snap2slides/
 app/              # Next.js pages
 components/       # React components  
 lib/              # Utilities and API handlers
 public/           # Static assets
```

## License

MIT License - see [LICENSE](LICENSE)

## Author

Built by Saurabh Pareek as a learning project

---

*This project was built to learn Next.js, TypeScript, and AI API integration.*
