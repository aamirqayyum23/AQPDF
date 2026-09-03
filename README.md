# AQPDF - Free Online PDF Tools

![AQPDF Logo](public/logo-full.png)

## 🚀 Overview

AQPDF is a modern, free online platform providing professional PDF tools for everyone. Built with Next.js 16, TypeScript, and Tailwind CSS, it offers a fast, secure, and user-friendly experience.

## ✨ Features

### PDF Tools (12 Total)
- 📄 **Merge PDF** - Combine multiple PDFs into one
- ✂️ **Split PDF** - Extract pages or divide PDFs
- 🗜️ **Compress PDF** - Reduce file size without quality loss
- 🖼️ **PDF to Image** - Convert to JPG/PNG
- 📸 **Image to PDF** - Create PDFs from images
- 📊 **PDF to Excel** - Extract tables to XLSX
- 🔒 **Protect PDF** - Add password protection
- 🔓 **Unlock PDF** - Remove passwords
- 🔄 **Rotate PDF** - Change page orientation
- 🗑️ **Delete Pages** - Remove unwanted pages
- ✏️ **Edit PDF** - Add text and images
- ✍️ **Sign PDF** - Electronic signatures

### Key Features
- ✅ 100% Free - No registration required
- 🔐 Secure - SSL encryption, auto-delete after 1 hour
- ⚡ Fast - Optimized processing
- 📱 Responsive - Works on all devices
- 🎨 Modern UI - Beautiful gradient design
- 🌐 SEO Optimized - Complete meta tags and structured data

## 🛠️ Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS 4
- **Database:** PostgreSQL + Drizzle ORM
- **Icons:** Lucide React
- **Deployment:** Vercel-ready

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/aqpdf.git

# Navigate to project
cd aqpdf

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your DATABASE_URL

# Push database schema
npx drizzle-kit push

# Run development server
npm run dev
```

## 🌐 Environment Variables

Create a `.env` file:

```env
DATABASE_URL=postgresql://postgres:postgres@localhost:5432/aqpdf_db
```

## 📝 Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run typecheck    # Run TypeScript checks
npm run lint         # Run ESLint
```

## 🔍 SEO Features

- ✅ Comprehensive meta tags (title, description, keywords)
- ✅ Open Graph tags for social media
- ✅ Twitter Card support
- ✅ Structured Data (Schema.org)
- ✅ Dynamic sitemap.xml
- ✅ Robots.txt
- ✅ PWA manifest.json
- ✅ Canonical URLs
- ✅ Optimized images and performance

## 📂 Project Structure

```
aqpdf/
├── public/
│   ├── favicon.svg
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── apple-touch-icon.png
│   ├── og-image.jpg
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── app/
│   │   ├── page.tsx              # Homepage
│   │   ├── layout.tsx            # Root layout
│   │   ├── sitemap.ts            # Dynamic sitemap
│   │   ├── merge-pdf/            # Tool pages
│   │   ├── split-pdf/
│   │   ├── compress-pdf/
│   │   ├── about/
│   │   ├── blog/
│   │   ├── faq/
│   │   ├── contact/
│   │   ├── privacy/
│   │   └── terms/
│   └── db/
│       ├── index.ts              # Database client
│       └── schema.ts             # Database schema
├── package.json
├── tsconfig.json
└── tailwind.config.ts
```

## 🎨 Design System

### Colors
- **Primary:** Blue (#2563eb)
- **Secondary:** Purple (#9333ea)
- **Accent Colors:** Pink, Teal, Orange, etc.
- **Neutral:** Slate scale

### Typography
- **Headings:** Bold, modern sans-serif
- **Body:** Clean, readable font stack
- **Gradients:** Blue to purple on key elements

## 🚀 Deployment

### Vercel (Recommended)

1. Push code to GitHub
2. Import project in Vercel
3. Add environment variables
4. Deploy!

### Other Platforms

```bash
# Build production bundle
npm run build

# Start production server
npm start
```

## 📊 Performance

- ⚡ Fast page loads with Next.js SSR/SSG
- 🎯 Optimized images and assets
- 📦 Minimal CSS with Tailwind
- 🔄 Automatic code splitting
- 💨 Lighthouse score: 95+

## 🔐 Security

- SSL/TLS encryption
- Files auto-deleted after 1 hour
- No permanent storage
- Privacy-first approach
- GDPR compliant

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📧 Contact

- Website: https://aqpdf.com
- Email: support@aqpdf.com
- GitHub: https://github.com/yourusername/aqpdf

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Tailwind CSS for the utility-first CSS
- Lucide for beautiful icons
- Vercel for hosting platform

---

Made with ❤️ by AQPDF Team
