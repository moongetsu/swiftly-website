<h1 align="center">
  <img src="https://images.gamebanana.com/img/ico/sprays/naruto.gif" width="64" alt="Swiftly Website"/>
  <br />
  Swiftly Website
</h1>
<p align="center">
  <b>The official documentation hub for <span style="color:#1dd1a1;">SwiftlyS2</span>.</b><br>
  <i>Your source for clear, fast, and customizable SwiftlyS2 project docs.</i>
</p>

This is a Next.js application generated with
[Create Fumadocs](https://github.com/fuma-nama/fumadocs).
  
Setup dependecies:

```bash
npm install
npm install next-themes
# or
pnpm install
pnpm add next-themes
# or
yarn install
yarn add next-themes
```

## 📖 About

**Swiftly Website** is the home for documentation and guides related to the SwiftlyS2 project. Powered by [Next.js](https://nextjs.org/) and [Fumadocs](https://fumadocs.vercel.app), it offers a fast, flexible, and beautiful documentation experience with MDX support.

---

## 🚀 Quick Start

### 1. Prerequisites

Before you begin, make sure you have [Node.js](https://nodejs.org/) (version 18 or newer recommended) and [npm](https://www.npmjs.com/) installed.

#### **Install Node.js & npm**
Download and install Node.js from [nodejs.org](https://nodejs.org/). The installer includes npm.

```bash
# Check your Node.js version
node -v

# Check your npm version
npm -v
```

### 2. Install Dependencies

Navigate to the root of the project and install dependencies with your preferred package manager:

```bash
# Using npm
npm install

# OR using pnpm
pnpm install

# OR using yarn
yarn install
```

### 3. Start the Development Server

Now, launch the development server:

```bash
# Using npm
npm run dev

# OR using pnpm
pnpm dev

# OR using yarn
yarn dev
```

Once started, open [http://localhost:3000](http://localhost:3000) in your browser to view the site.

---

## 📁 Project Structure

| Route                     | Description                                            |
|---------------------------|--------------------------------------------------------|
| `app/(home)`              | The route group for your landing page and other pages. |
| `app/docs`                | The documentation layout and pages for SwiftlyS2.      |
| `app/api/search/route.ts` | The Route Handler for search functionality.            |

### Key Files

- **`lib/source.ts`** – Source adapter code ([`loader()`](https://fumadocs.dev/docs/headless/source-api)), lets you access all documentation content.
- **`lib/layout.shared.tsx`** – Shared layout configuration.
- **`source.config.ts`** – Configure frontmatter schema and more for your docs.

---

## ✨ Features

- **⚡ Powered by Next.js 14+**
- **📚 MDX Support** – Write docs using Markdown + React components
- **🔎 Instant Search** – Full-text search for docs
- **🎨 Easily Customizable** – Custom layouts, themes & styles
- **📱 Fully Responsive** – Looks great on any device
- **🚀 Blazing Fast** – Optimized for speed and SEO

---

## 📚 Fumadocs MDX

A `source.config.ts` file is included so you can adapt frontmatter and content structure for SwiftlyS2's needs.

For a deeper dive, read the [Fumadocs Introduction](https://fumadocs.dev/docs/mdx).

---

## 🛠️ Learn More

To learn more about the stack behind Swiftly Website, check out:

- **[Next.js Documentation](https://nextjs.org/docs)** – Framework docs
- **[Learn Next.js](https://nextjs.org/learn)** – Interactive Next.js tutorial
- **[Fumadocs](https://fumadocs.vercel.app)** – Docs on Fumadocs

---

<p align="center">
  <img src="https://badgen.net/badge/Project/SwiftlyS2/green?icon=star" alt="SwiftlyS2" />
  <img src="https://badgen.net/badge/Docs/Fumadocs/pink" alt="Fumadocs" />
  <img src="https://badgen.net/badge/Framework/Next.js/blue?icon=nextjs" alt="Next.js" />
  <img src="https://badgen.net/badge/Language/TypeScript/blue?icon=typescript" alt="TypeScript" />
</p>