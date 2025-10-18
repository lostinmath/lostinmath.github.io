# Mathematical Research Portfolio

Exploring mathematical problems without obvious commercial applications.

## Live Site

**[View Portfolio →](https://lostinmath.github.io/)**

## Focus Areas

- **Optimization Problems** - Working through non-convex optimization challenges
- **Machine Learning Experiments** - Reinforcement learning and computer vision projects
- **Personal Research** - Mathematical approaches driven by curiosity rather than commercial value

## Current Projects

- **Non-Convex Optimization** - Working through optimization problems without clean solutions
- **RL Distillation** - Making smaller RL models learn from bigger ones

Open to collaboration on similar problems.

---

<details>
<summary>🔧 Development Setup</summary>

### Prerequisites

- Python 3.x (for local server)
- Node.js and npm (optional, for Sass compilation)

### Quick Start

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd lostinmath.github.io
   ```
2. **Set up virtual environment**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. **Start local development server**

   ```bash
   npm run dev
   # or manually:
   source .venv/bin/activate && python -m http.server 8000
   ```
4. **View the site**
   Open http://localhost:8000 in your browser

### CSS Development

The site uses SCSS for styling. To make CSS changes:

1. **Install Sass (one-time setup)**

   ```bash
   npm install
   ```
2. **Edit SCSS files**

   - Main stylesheet: `sass/style.scss`
   - Project card styles are at the bottom of the file
3. **Compile SCSS to CSS**

   ```bash
   # One-time compilation
   npm run sass-build

   # Watch mode (auto-compile on changes)
   npm run sass
   ```

</details>

## Project Structure

```
├── index.html          # Main portfolio page
├── css/               # Compiled stylesheets
├── sass/              # SCSS source files
├── js/                # JavaScript libraries
├── images/            # Portfolio images
├── fonts/             # Web fonts
├── package.json       # Development dependencies
└── README.md          # This file
```

## Content Management

All content is managed directly in `index.html`:

- **Projects**: Lines 100-140 (project cards with descriptions and links)
- **Experience**: Lines 142-203 (professional timeline)
- **Contact**: Lines 387-398 (contact information)

## Deployment

The site is automatically deployed via GitHub Pages when changes are pushed to the main branch.

**Live URL**: https://lostinmath.github.io/

## Technologies

- **Frontend**: HTML5, CSS3, Bootstrap 3, jQuery
- **Build**: Sass for CSS preprocessing
- **Hosting**: GitHub Pages
- **Development**: Python HTTP server for local testing
