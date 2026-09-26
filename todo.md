Yes. Based on your current site and GitHub, I’d simplify it **dramatically**. Your existing portfolio has a lot of sections and claims; the new version should feel more like a **premium personal landing page**: one screen, lots of whitespace, strong typography, and direct links. Your current site identifies you as an AI/ML Engineer and highlights Python, PyTorch, Deep Learning, LLMs, RAG, agents, etc.; your GitHub similarly describes you as focused on AI/ML and shows your project work. ([Rushikesh Mohalkar Portfolio][1])

I’d use **Montserrat**, GitHub Pages + Jekyll, plain HTML/Liquid/CSS, and no unnecessary JS/framework.

## 1. Copy-paste prompt for the code generator

Build a **single-page, ultra-clean personal portfolio website** for **Rushikesh Mohalkar**, an AI/ML Engineer.

### Goal

Create a premium, minimalist portfolio that feels like a serious AI/ML engineer's personal homepage — **not a traditional resume website**.

The website must be:

* Single page
* Extremely clean
* Minimal
* Professional
* Fast-loading
* Responsive
* Mobile-friendly
* Light theme
* Lots of whitespace
* Typography-focused
* No unnecessary animations
* No cards everywhere
* No gradients
* No glassmorphism
* No excessive icons
* No stock images
* No AI-generated decorative graphics
* No dark theme

### Technology

Use:

* Jekyll
* HTML/Liquid
* CSS
* Minimal JavaScript only if genuinely necessary
* Google Fonts: **Montserrat**
* GitHub Pages compatible
* No React
* No Next.js
* No Tailwind
* No external UI framework

The project must be deployable directly through GitHub Pages.

### Personal information

Name:
Rushikesh Mohalkar

Primary title:
AI/ML Engineer

Location:
Bengaluru, India

GitHub:
[https://github.com/mohalkarushikesh](https://github.com/mohalkarushikesh)

LinkedIn:
[https://www.linkedin.com/in/rushikesh-mohalkar](https://www.linkedin.com/in/rushikesh-mohalkar)

Instagram:
[https://www.instagram.com/mohalkarushikesh](https://www.instagram.com/mohalkarushikesh)

X:
[https://x.com/mohalkarushikesh](https://x.com/mohalkarushikesh)

Portfolio:
[https://mohalkarushikesh.github.io/](https://mohalkarushikesh.github.io/)

### Professional positioning

Use this positioning:

AI/ML Engineer building intelligent systems with Python, PyTorch, deep learning and modern generative AI.

Areas of interest:

* Deep Learning
* Generative AI
* Large Language Models
* RAG
* AI Agents
* NLP
* Reinforcement Learning
* ML Systems

Do NOT position me primarily as a QA Engineer.

Do NOT exaggerate my experience.

Do NOT claim that I have built frontier models.

### Page structure

The entire website should essentially fit into one elegant viewport, while remaining responsive on smaller screens.

#### Header

Very minimal.

Left:
Rushikesh Mohalkar

Right:
GitHub
LinkedIn
X

Do not create a large navigation menu.

#### Hero

Large typography:

Rushikesh Mohalkar

AI/ML Engineer

Then a short 1–2 line description:

Building intelligent systems with deep learning, generative AI, LLMs and modern ML engineering.

Below it, two simple text links/buttons:

GitHub →
LinkedIn →

#### Technical focus

Instead of large cards, display a simple horizontal or wrapped text list:

Deep Learning · Generative AI · LLMs · RAG · AI Agents · NLP · Reinforcement Learning · ML Systems

Keep it visually subtle.

#### Selected work

Show only 3 projects.

Use the following projects as the initial selection:

1. Oryza
   Local/self-hosted AI chatbot using Ollama and Qwen.

2. RAG App
   End-to-end local RAG pipeline for document question answering.

3. ML Pipeline
   Production-oriented machine-learning pipeline project.

Each project should be represented as a simple text row:

Project name
Short one-line description
GitHub →

Do NOT use large project cards.

#### Footer

Minimal:

© 2026 Rushikesh Mohalkar

GitHub · LinkedIn · X · Instagram

### Visual design

Use Montserrat throughout.

Typography should be the primary design element.

Recommended hierarchy:

Name:
font-weight: 600–700

Main title:
large, bold, approximately 64–80px desktop

Body:
16–18px

Small metadata:
12–14px

Use:

* white/off-white background
* near-black text
* subtle gray secondary text
* thin borders where necessary
* generous spacing

Avoid:

* colorful gradients
* excessive shadows
* rounded cards
* huge illustrations
* unnecessary badges
* skill progress bars
* percentage skill ratings
* animated backgrounds

### Layout

Desktop:

* max-width around 1100–1200px
* centered
* generous horizontal margins
* hero occupies most of the first viewport

Mobile:

* 20–24px horizontal padding
* title scales down appropriately
* links wrap naturally
* no horizontal scrolling

### Interactions

Links should have subtle hover effects.

For example:

* underline animation
* slight opacity transition

Keep interactions understated.

### Accessibility

Include:

* semantic HTML
* descriptive link text
* proper heading hierarchy
* keyboard-accessible links
* visible focus states
* sufficient contrast
* responsive typography

### SEO

Add:

* title
* meta description
* canonical URL
* Open Graph metadata
* Twitter/X card metadata

Suggested title:

Rushikesh Mohalkar — AI/ML Engineer

Suggested description:

AI/ML Engineer building intelligent systems with deep learning, generative AI, LLMs and modern machine learning.

### Jekyll structure

Generate the complete project with:

_config.yml
_layouts/default.html
_includes/
assets/css/style.css
index.md

Keep the structure simple.

### GitHub Pages compatibility

The website must work with:

[https://mohalkarushikesh.github.io/](https://mohalkarushikesh.github.io/)

Do not require a custom build server.

Make sure relative paths work correctly when deployed through GitHub Pages.

### Important

Before producing the final code, check for:

* broken links
* invalid Jekyll syntax
* incorrect asset paths
* mobile overflow
* unnecessary dependencies
* unnecessary JavaScript

The final result should feel like a **minimal personal homepage for an AI/ML engineer**, not a conventional portfolio template.

## 2. Recommended project structure

```text
portfolio/
├── _config.yml
├── _layouts/
│   └── default.html
├── _includes/
│   └── ...
├── assets/
│   └── css/
│       └── style.css
└── index.md
```

If you want it even simpler, you can start with:

```text
portfolio/
├── _config.yml
├── index.html
└── assets/
    └── css/
        └── style.css
```

For your use case, **I'd start with the second structure**. You don't need a complicated Jekyll architecture for a one-page site.

## 3. Step-by-step: create it

### Step 1 — Create the repository

Your GitHub Pages URL is already:

[mohalkarushikesh.github.io](https://github.com/mohalkarushikesh?utm_source=chatgpt.com)

For a user site, the repository should be:

```text
mohalkarushikesh.github.io
```

If you already have that repository, **clone it instead of creating another one**.

```bash
git clone https://github.com/mohalkarushikesh/mohalkarushikesh.github.io.git
cd mohalkarushikesh.github.io
```

### Step 2 — Create the basic files

```bash
mkdir -p assets/css
touch _config.yml
touch index.html
touch assets/css/style.css
```

You should have:

```text
mohalkarushikesh.github.io/
├── _config.yml
├── index.html
└── assets/
    └── css/
        └── style.css
```

### Step 3 — Generate the code

Give the prompt above to your coding model and tell it:

> **Generate the complete contents of all files. Do not explain first. Give me each file separately with its filename.**

Then replace your existing files.

### Step 4 — Test locally

If Jekyll is installed:

```bash
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000
```

Check:

* Desktop
* Mobile width
* GitHub links
* LinkedIn
* X
* Instagram
* Project links
* Font loading
* No horizontal scrolling

### Step 5 — Push to GitHub

```bash
git status
git add .
git commit -m "Redesign portfolio as minimal AI ML landing page"
git push origin main
```

### Step 6 — GitHub Pages

On GitHub:

**Repository → Settings → Pages**

Set:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Save.

GitHub Pages will build the site.

### Step 7 — Check the live site

Open:

[Your portfolio](https://mohalkarushikesh.github.io/?utm_source=chatgpt.com)

GitHub Pages deployment can take a little time after the first push.

---

### One important change I'd make from your current portfolio

Your existing website currently has **a lot of information competing for attention** — projects, articles, AI/ML map, experience, skills, contact form, etc. ([Rushikesh Mohalkar Portfolio][1])

For this redesign, I'd make the homepage communicate only:

> **Rushikesh Mohalkar**
> **AI/ML Engineer**
> *Building intelligent systems with deep learning, GenAI & modern ML.*
>
> **Work · GitHub · LinkedIn · X**

Then let GitHub contain the technical depth. Your GitHub already has **55 repositories** and showcases projects ranging from PPO reinforcement learning to CNN and NLP work. ([GitHub][2])

That gives you the **“single-page blank, clean portfolio”** feeling you're looking for rather than another portfolio packed with sections.

[1]: https://mohalkarushikesh.github.io/ "Rushikesh Mohalkar — AI/ML Engineer & Software Developer"
[2]: https://github.com/mohalkarushikesh "mohalkarushikesh (Rushikesh Mohalkar) · GitHub"
