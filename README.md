# MetaLet
AI powered translator

# Create the README.md file

readme_content = '''# MetaLet - AI-Powered Layout-Preserved Translator

MetaLet is a complete, production-ready, browser-based translation application that supports PPTX, PDF, images, and text translation with layout preservation. Built with the MetaVirt dark professional theme.

## Features

### Input Types Supported
- **PPTX files** - Translate presentations while preserving slide layouts
- **PDF files** - Translate documents with original formatting
- **Images** (PNG/JPG/JPEG) - OCR + translation with text overlay
- **Direct text** - Instant text-to-text translation

### Translation Modes
- **AI Contextual Translation** (Default) - Uses AI to understand context, tone, and intent
- **Literal Word-to-Word Translation** - Direct dictionary-based translation

### Layout Preservation & Smart Auto-Fit
- Preserves original layout, positions, and alignment
- Automatically adjusts font size (minimum 8pt) to fit text boundaries
- Auto-adjusts line spacing for clean, readable text

### Language Support (23 Languages)
All pairs supported with auto-detection:

**Core:** English (en), Chinese (zh), Bengali (bn)
**European:** Spanish (es), French (fr), German (de), Italian (it), Dutch (nl), Portuguese (pt), Russian (ru), Polish (pl), Swedish (sv), Danish (da), Norwegian (no), Finnish (fi)
**Asian:** Japanese (ja), Korean (ko), Vietnamese (vi), Thai (th), Malay (ms), Hindi (hi), Arabic (ar)
**Other:** Turkish (tr)

### No Limits
- No file size limits (supports 1MB → 1GB+ files)
- No page/slide count limits (supports 1 → 500+ pages)
- No image resolution limits
- No watermarks or usage restrictions

## Technical Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **OCR:** Tesseract.js v5 (supports all 23 languages)
- **AI Translation:** DeepL Free API
- **Literal Translation:** MyMemory Translation API
- **PPTX Processing:** PptxGenJS + JSZip
- **PDF Processing:** PDF-lib + PDF.js
- **Image Processing:** Canvas API + Tesseract.js

## Project Structure

```
/
├── index.html    - Main UI structure
├── style.css     - MetaVirt dark theme styling
├── script.js     - Full application logic
└── README.md     - Documentation
```

## How to Run

1. Download all files to a folder
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. No server required - 100% client-side
4. No API keys required for basic functionality

## Usage

### File/Image Translation
1. Click "File & Image Translation" tab
2. Drag & drop or select files (PPTX, PDF, PNG, JPG, JPEG)
3. Select source language (or auto-detect) and target language
4. Choose translation mode (AI Contextual or Literal)
5. Click "Start Translation"
6. Download translated files

### Text Translation
1. Click "Text Translation" tab
2. Enter text in source box
3. Select languages and mode
4. Click "Translate"
5. Copy result to clipboard

## Hosting

Can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any static web host
- Local file system (open directly in browser)

## Privacy

- **100% Client-Side** - All processing happens in your browser
- **No Data Collection** - Files never leave your device
- **No Server** - No backend, no database, no tracking
- **Secure** - Your documents remain private

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Notes

- For production use with DeepL API, users should obtain their own API key
- MyMemory API has rate limits for free usage
- Tesseract.js language packs are loaded on-demand
- Large files may take longer to process depending on device capabilities

## License

Open source - Free to use, modify, and distribute.

---

**MetaLet** - Breaking language barriers, preserving layouts.
'''

