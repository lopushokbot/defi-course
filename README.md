# DeFi Mastery Course - Static Website

A polished, single-page static website for a comprehensive DeFi course with downloadable PDF guides and video walkthroughs.

## Quick Start

This is a plain HTML/CSS site with no build step required. Just serve the files.

### Option 1: Open directly
```bash
open index.html
```

### Option 2: Local dev server (Python)
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Option 3: Local dev server (Node)
```bash
npx serve .
```

## Deploy

Works on any static hosting platform:

- **Netlify** - Drag and drop the project folder, or connect your repo
- **Vercel** - `vercel --prod` from the project root
- **GitHub Pages** - Push to a repo, enable Pages in Settings → Pages → Source: main branch
- **Cloudflare Pages** - Connect your repo, no build command needed
- **S3 + CloudFront** - Upload all files to an S3 bucket with static hosting enabled

**Important:** The `assets/lessons/` directory contains all downloadable lesson files (~160 MB total). Make sure your hosting provider supports the file sizes (the largest MP4s are ~38 MB each).

## Structure

```
├── index.html              # Single-page website
├── assets/
│   └── lessons/            # All downloadable PDFs and MP4s
├── source_assets/          # Original source files (not served)
└── README.md
```

## Course Content

9 lessons covering:
1. DeFi & Smart Contract Fundamentals
2. Stablecoins
3. Automated Market Makers (AMMs)
4. Lending Protocols
5. Perpetual DEXs
6. Yield Farming
7. Core Yield Assets & Strategy
8. Multi-Chain DeFi Strategies
9. DeFi Security
