# Vítor Ferreira - Digital Resume

This is the source code for my digital Curriculum Vitae. It is designed as a single-page web application that is easy to read, print, and export as a PDF.

## Tech Stack

The project relies on a minimal, high-performance stack focusing on simplicity and maintainability:
- **HTML5**: Semantic and accessible structure.
- **Vanilla CSS3**: Custom styles, responsive grid, flexbox, and print-specific CSS rules. No heavy frameworks are used.
- **Vite**: A lightning-fast development server and build tool that bundles the assets seamlessly.

## Getting Started

To run this project locally, you will need Node.js installed on your machine.

1. Clone the repository:
   ```bash
   git clone https://github.com/vitorstick/resume.git
   cd resume
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
The site will be available locally (usually at `http://localhost:5173/`).

## Deployment

This website is automatically hosted on **GitHub Pages**. 

### How it works
We use a package called `gh-pages` alongside Vite to compile the site and push solely the production-ready code to a special `gh-pages` branch. 

### How to release an update
Whenever you make changes to the source code (e.g., updating your experience or tweaking styles), simply commit those changes to the `main` branch, and then run:

```bash
npm run deploy
```

This command will:
1. Run `vite build` to optimize and bundle the static files into the `dist` folder.
2. Automatically turn the `dist` folder into a commit and force-push it to the `gh-pages` branch on GitHub.

*Note: In the repository settings on GitHub, the GitHub Pages source must be set to "Deploy from a branch" and the branch must be pointing to `gh-pages`.*

## Live Site
You can see the live and up-to-date version of the resume here:
**[https://vitorstick.github.io/resume/](https://vitorstick.github.io/resume/)**
