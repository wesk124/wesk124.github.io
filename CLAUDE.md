# CLAUDE.md — Sheng Wei Personal Website

## Project Overview
Personal website for Sheng Wei, deployed on GitHub Pages at **https://wesk124.github.io**.
Sections: Home, Resume, Blog.

## File Structure
```
website/
├── index.html               # Home page
├── resume.html              # Full resume
├── css/style.css            # All styles (shared across all pages)
├── blog/
│   ├── index.html           # Blog listing
│   ├── bridging-systems-and-ml.html
│   └── rag-multi-agent-chatbot.html
└── resume_sheng_wei.pdf     # Original resume (linked as download)
```

## Design
- Style: **Minimal / Clean** — white background, Inter font, accent color `#4f6ef7` (blue)
- No frameworks — pure HTML/CSS, no JavaScript dependencies
- Responsive via CSS Grid/Flexbox + media queries at 600px breakpoint
- CSS variables defined in `:root` in `style.css`

## Owner Info
- **Name:** Sheng Wei
- **GitHub:** github.com/wesk124
- **LinkedIn:** linkedin.com/in/sheng-wei-0721

## How to Add a Blog Post
1. Copy an existing post file (e.g. `blog/bridging-systems-and-ml.html`)
2. Update the `<title>`, `<h1>`, `.post-meta`, and body content
3. Add a link in `blog/index.html` (`.blog-list` section)
4. Add a link in `index.html` (the "Recent Blog Posts" section)

## Deployment
- Repo: `git@github.com:wesk124/wesk124.github.io.git`
- Branch: `main`
- GitHub Pages source: root of `main` branch
- Live URL: `https://wesk124.github.io`

## Key CSS Classes
| Class | Use |
|---|---|
| `.container` | Page-width wrapper (max 760px, centered) |
| `.btn .btn-primary` | Filled blue button |
| `.btn .btn-outline` | Outlined button |
| `.timeline` / `.timeline-item` | Two-column date + content layout |
| `.project-card` | Bordered card with hover effect |
| `.blog-card` | Row-style blog post link |
| `.skill-card` | Grey background skill box |
| `.post-body` | Blog post content area |
| `.section-label` | Small uppercase accent label above headings |
