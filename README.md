# AI & Automation Blog

A modern, SEO-optimized blog built with Astro, Tailwind CSS, and MDX for exploring the latest in AI and automation.

## 🚀 Quick Start

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```

3. **Build for production**
   ```bash
   npm run build
   ```

4. **Preview production build**
   ```bash
   npm run preview
   ```

## 📁 Project Structure

```
/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── content/
│   │   ├── config.ts    # Content collection configuration
│   │   └── posts/       # Blog posts in MDX format
│   ├── layouts/
│   │   └── BlogPost.astro  # Blog post layout template
│   └── pages/
│       ├── index.astro      # Homepage with post listings
│       └── blog/
│           └── [slug].astro # Dynamic blog post routes
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind CSS configuration
└── package.json
```

## ✍️ Writing Blog Posts

Blog posts are stored in `src/content/posts/` as MDX files with frontmatter:

```mdx
---
title: "Your Post Title"
description: "SEO meta description (150-160 chars)"
date: YYYY-MM-DD
tags: ["ai", "automation", "relevant-tag"]
author: "AI Automation Team"
---

Your content here...
```

## 🎨 Styling

- Built with Tailwind CSS for utility-first styling
- Responsive design that works on all devices
- Typography plugin for beautiful article formatting
- Customizable color scheme in `tailwind.config.mjs`

## 🔧 Configuration

### Site URL
Update the `site` field in `astro.config.mjs` with your deployment URL

### Content Collections
Modify `src/content/config.ts` to adjust the blog post schema or add new content types

## 📦 Deployment

### Netlify
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`

### Other Platforms
This is a standard Astro project and can be deployed to any static hosting platform (Vercel, Cloudflare Pages, AWS S3, etc.)

## 🛠️ Tech Stack

- **Astro** - Static site generator
- **Tailwind CSS** - Utility-first CSS framework
- **MDX** - Markdown with JSX support
- **TypeScript** - Type-safe development

## 📝 SEO Features

- Automatic meta descriptions from frontmatter
- Semantic HTML structure
- Clean, readable URLs based on post slugs
- Fast page loads with static generation
- RSS feed support (via @astrojs/rss)

## 🌟 Features

- ✅ Fast, static site generation
- ✅ SEO-optimized
- ✅ Responsive design
- ✅ Beautiful typography
- ✅ Code syntax highlighting
- ✅ Tag-based organization
- ✅ Easy content management with MDX
- ✅ Type-safe with TypeScript
- ✅ Zero JavaScript by default (progressive enhancement)

---

Built with ❤️ using Astro and Tailwind CSS