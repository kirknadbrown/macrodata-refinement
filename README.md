# Macrodata Refinement

An interactive p5.js visualization inspired by the Severance TV series.

## Features

- Interactive number grid with selection
- Drag and drop functionality
- Multiple bins for organizing numbers
- Progress tracking and completion animations
- Touch support for mobile devices

## Deployment to Vercel

This project is ready to deploy to Vercel. Follow these steps:

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. Navigate to the project directory:
   ```bash
   cd /Users/kirknadbrown/Downloads
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts to link your project and deploy.

### Option 2: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project"
3. Import your Git repository (if using Git) or drag and drop the project folder
4. Vercel will automatically detect the static site configuration
5. Click "Deploy"

### Option 3: Deploy via GitHub/GitLab

1. Push your code to a Git repository (GitHub, GitLab, etc.)
2. Go to [vercel.com](https://vercel.com)
3. Click "Add New Project"
4. Import your repository
5. Vercel will automatically detect and deploy

## Local Development

To run locally:

```bash
npm install
npm run dev
```

Or simply open `index.html` in a web browser.

## Technologies

- HTML5
- p5.js (loaded via CDN)
- Vanilla JavaScript

## License

MIT
