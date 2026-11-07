# Historical VizHub feature overview

> **Unverified historical reference:** This is a preservation of the former `README.md` feature overview, not a current product specification. Claims about UI routes, access controls, exports, billing, self-hosting, and integrations have not been checked against the November 2026 VizHub deployment. Prefer [the new repository README](README.md) and the live product's own documentation for current behavior.

# VizHub Feature Overview (original notes)

**VizHub** is an open-source platform for creating, modifying, and sharing interactive data visualizations built with **HTML, CSS, and JavaScript** (often alongside libraries such as D3.js or Vega-Lite). Below is a concise guide to the core workflow and capabilities that set VizHub apart.

---

## Core Workflow

1. **Fork → Modify → Share**

   | Step | What Happens in VizHub | Why It Matters |
   |------|------------------------|----------------|
   | **Fork** | Click **Fork** on any public “Viz” to create your own copy. | Start from a working example instead of a blank page. |
   | **Modify** | Edit code directly in the browser—change data, tweak styles, add interactions. | Rapid prototyping without local setup. |
   | **Share** | Generate a unique URL, social card, and embed snippet with a single click. | Instantly show your work to the world. |

---

## Feature Highlights

### 🖍️ Forking & Modifying
- **One-Click Fork**: Duplicate any public visualization to kick-start your own version.  
- **Version Isolation**: Your fork tracks its own history, leaving the original untouched.

### 🤖 Editing with AI
- **AI Code Assistant**: Invoke **/ai-edit** to get line-level refactors, doc comments, or full rewrites.  
- **Prompt-Based Changes**: Describe what you want (“add a tooltip”) and watch the editor update in seconds.

### 🔒 Changing Visibility
- **Public ↔ Private Toggle**: Switch a Viz between public, unlisted, or private at any time.  
- **Team-Only Mode**: Share privately with collaborators without exposing the link publicly.

### 👥 Real-Time Collaboration
- **Live Cursor Presence**: See teammates’ cursors and selections, Google-Docs style.  
- **Conflict-Free Merging**: Edits sync instantly—no git conflicts or refreshes required.

### 📣 Sharing on Social Media
- **Smart Social Cards**: VizHub auto-generates Open Graph images so links look great on X/Twitter, LinkedIn, and Facebook.  
- **Permalink Stability**: Each visualization has a canonical URL that never changes.

### 🖼️ Embedding
- **Iframe Snippet**: Copy-paste a tiny embed tag into Medium, Notion, or your own blog.  
- **Responsive by Default**: Embedded visualizations resize to fit any container or device.

### 💾 Exporting Code
- **Download ZIP**: Grab a clean, runnable bundle of HTML, JS, CSS, and assets.  
- **Choose Bundler**: Export plain ES modules or a pre-built Rollup bundle for older browsers.

### 🏃 Running Exported Code Locally
1. **Unzip** the download.
2. **Install Dependencies** (if any):
   ```bash
   npm install
```

3. **Start a Local Server**:

   ```bash
   npx serve .
   # or
   npm run dev   # if a Vite config is included
   ```
4. Open `http://localhost:3000` (or the printed port) to view the visualization offline.

---

## Why Developers Love VizHub

* **No Infrastructure Overhead**: Skip the boilerplate; focus on the visualization.
* **Instant Feedback Loop**: Live preview updates with every keystroke.
* **Open Source & Self-Hostable**: Deploy your own VizHub if you need complete control.

Ready to explore? Fork a Viz, try the AI editor, and share your creation with the world—no install required.
