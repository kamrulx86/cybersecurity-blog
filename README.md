# 🛡️ Kamrul Hassan - Cybersecurity Blog
![Node.js >= 20](https://img.shields.io/badge/node.js-%3E%3D20-brightgreen) 
![pnpm >= 9](https://img.shields.io/badge/pnpm-%3E%3D9-blue) 
![Astro](https://img.shields.io/badge/Astro-5.13.8-orange)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.2-blue)

A professional cybersecurity blog and research platform built with [Astro](https://astro.build), showcasing security research, bug bounty findings, and industry insights.

[**🖥️ Live Website**](https://kamroot.com)

## About

This is the personal cybersecurity blog and research platform of **Kamrul Hassan**, a Cybersecurity Engineer and Security Researcher recognized by major organizations including Microsoft, Sony, and various government agencies.

## Professional Recognition

- **Microsoft**: Recognized for responsible vulnerability disclosure
- **Sony**: Acknowledged for identifying critical API security flaws
- **Dutch Government**: Credited for responsible disclosure of cybersecurity issues
- **Visma**: Listed in official Hall of Fame for application security contributions
- **Singapore Government**: Recognized for reporting critical web vulnerabilities

## ✨ Features

- [x] **Professional Design**: Modern, cybersecurity-themed design with professional color scheme
- [x] **Research Showcase**: Dedicated sections for security research and publications
- [x] **Blog Platform**: Technical articles on cybersecurity, penetration testing, and research
- [x] **Responsive Design**: Mobile-first approach with excellent user experience
- [x] **Search Functionality**: Full-text search powered by [Pagefind](https://pagefind.app/)
- [x] **Dark/Light Mode**: Professional theme switching with smooth transitions
- [x] **Contact Integration**: Professional contact forms and collaboration information
- [x] **RSS Feed**: Content syndication for security professionals
- [x] **Internationalization**: Multi-language support for global audience

## 🚀 Getting Started

### Prerequisites
- Node.js >= 20
- pnpm >= 9

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kamrulhassan/cybersecurity-blog.git
   cd cybersecurity-blog
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Start the development server:
   ```bash
   pnpm dev
   ```

4. Open [http://localhost:4321](http://localhost:4321) in your browser

### Customization

1. Edit `src/config.ts` to update your personal information
2. Modify `src/content/spec/about.md` for your bio
3. Add your blog posts in `src/content/posts/`
4. Update the theme colors in `src/styles/cybersecurity-theme.css`

### Deployment

Deploy to Vercel, Netlify, or any static hosting platform:

```bash
pnpm build
```

## 📝 Content Structure

### Blog Posts
Create new posts in `src/content/posts/` with the following frontmatter:

```yaml
---
title: "Your Security Research Title"
published: 2024-01-15
description: "Brief description of your research or findings"
tags: [Cybersecurity, Research, Penetration Testing]
category: Security Research
draft: false
image: ./research-image.jpg
---
```

### Research Pages
- **About**: Professional background and achievements
- **Research**: Current projects and publications
- **Contact**: Professional contact information and collaboration

## 🛠️ Technology Stack

- **Framework**: [Astro](https://astro.build) 5.13.8
- **Styling**: [Tailwind CSS](https://tailwindcss.com) with custom cybersecurity theme
- **Icons**: [Astro Icon](https://github.com/natemoo-re/astro-icon)
- **Search**: [Pagefind](https://pagefind.app/) for full-text search
- **Content**: Markdown with enhanced syntax support
- **Deployment**: Optimized for Vercel, Netlify, and other static hosts

## ⚡ Available Commands

| Command                    | Action                                              |
|:---------------------------|:----------------------------------------------------|
| `pnpm install`             | Install dependencies                                |
| `pnpm dev`                 | Start development server at `localhost:4321`        |
| `pnpm build`               | Build production site to `./dist/`                  |
| `pnpm preview`             | Preview production build locally                    |
| `pnpm check`               | Run TypeScript and Astro checks                    |
| `pnpm format`              | Format code using Biome                            |
| `pnpm new-post <filename>` | Create a new blog post                             |
| `pnpm lint`                | Lint and fix code issues                           |

## 🤝 Contact & Collaboration

I'm always interested in discussing cybersecurity topics, research collaborations, and sharing knowledge with the security community.

- **Email**: [kamrulhassan7740@gmail.com](mailto:kamrulhassan7740@gmail.com)
- **LinkedIn**: [linkedin.com/in/kamrul-hassan-x64](https://linkedin.com/in/kamrul-hassan-x64)
- **Website**: [kamroot.com](https://kamroot.com)
- **GitHub**: [github.com/kamrulhassan](https://github.com/kamrulhassan)

## 📄 License

This project is licensed under the MIT License. Feel free to use this as a template for your own cybersecurity blog or research platform.
