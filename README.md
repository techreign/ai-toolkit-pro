# AI Toolkit Pro

> **Free online tools that respect your privacy. 100% client-side — your files never leave your device.**

[![Live App](https://img.shields.io/badge/Live%20App-ai--toolkit--pro.vercel.app-blue?style=for-the-badge)](https://ai-toolkit-pro-ashen.vercel.app)
[![Client-Side Only](https://img.shields.io/badge/Processing-100%25%20Client--Side-green?style=for-the-badge)](#privacy)
[![Next.js](https://img.shields.io/badge/Built%20with-Next.js-black?style=for-the-badge&logo=next.js)](https://nextjs.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

## Live App

**[https://ai-toolkit-pro-ashen.vercel.app](https://ai-toolkit-pro-ashen.vercel.app)**

No sign-up. No upload limits. No server. Just tools that work.

---

## Features

### PDF Tools
- **PDF Merge** — Combine multiple PDF files into one
- **PDF Compress** — Reduce PDF file size without quality loss
- **PDF Split** — Extract pages or split a PDF into multiple files

### Image Tools
- **Image Compressor** — Reduce image file size while preserving quality
- **Image Resize** — Resize images to any dimension
- **Image Convert** — Convert between JPG, PNG, WebP, and more

### QR Code Generator
- Generate QR codes for URLs, text, WiFi, contact cards, and more
- Download as PNG or SVG
- Customizable colors and sizes

### Resume Builder
- Professional resume templates
- Export to PDF directly in your browser
- No data sent to any server

---

## Privacy

All processing happens **entirely in your browser** using WebAssembly and client-side JavaScript.

- No file uploads to any server
- No analytics on your files
- No account required
- Works offline after first load

---

## Tech Stack

| Technology | Purpose |
|---|---|
| [Next.js 14](https://nextjs.org) | React framework with App Router |
| [TypeScript](https://www.typescriptlang.org) | Type-safe development |
| [Tailwind CSS](https://tailwindcss.com) | Utility-first styling |
| [pdf-lib](https://pdf-lib.js.org) | Client-side PDF manipulation |
| [browser-image-compression](https://github.com/Donaldcwl/browser-image-compression) | In-browser image compression |
| [qrcode](https://github.com/soldair/node-qrcode) | QR code generation |

---

## Screenshots

> Screenshots coming soon. Visit the [live app](https://ai-toolkit-pro-ashen.vercel.app) to see it in action.

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/techreign/ai-toolkit-pro.git
cd ai-toolkit-pro

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env.local

# Run the dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Contributing

Contributions are welcome! If you'd like to add a new tool or improve an existing one:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-tool-name`)
3. Commit your changes (`git commit -m 'Add: your tool name'`)
4. Push to the branch (`git push origin feature/your-tool-name`)
5. Open a Pull Request

Please keep the **client-side only** principle — no server-side file processing.

---

## License

MIT — see [LICENSE](LICENSE) for details.

---

*Built with care to keep your files private.*
