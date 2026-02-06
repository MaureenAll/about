# Maureen Allanic - Resume Portfolio

A lean, clean, minimalist resume portfolio website built with Tailwind CSS and optimized for GitLab Pages.

## 🎨 Design Features

- **Ultra-minimalist** dark theme with high contrast
- **Typography-focused** layout with generous spacing
- **Fully responsive** mobile-first design
- **Zero animations** for fast, distraction-free experience
- **Semantic HTML5** structure
- **Optimized** for performance and accessibility

## 🚀 Local Development

### Prerequisites
- Node.js 18+ installed

### Running Locally

1. Navigate to the project directory:
```bash
cd C:\Users\Maureen\.gemini\antigravity\scratch\resume-portfolio
```

2. Start a local server:
```bash
npx serve .
```

3. Open your browser to `http://localhost:3000`

### Building for Production

To generate optimized CSS:

```bash
npm install
npm run build
```

This will create a minified `styles.css` file.

## 📦 GitLab Pages Deployment

### Step 1: Create GitLab Repository

1. Go to [GitLab.com](https://gitlab.com) and sign in
2. Click **New Project** → **Create blank project**
3. Name it `resume-portfolio` (or any name you prefer)
4. Set visibility to **Public** or **Private**
5. Click **Create project**

### Step 2: Initialize Git and Push

In your project directory, run:

```bash
# Initialize Git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Minimalist resume portfolio"

# Add your GitLab repository as remote
git remote add origin https://gitlab.com/YOUR_USERNAME/resume-portfolio.git

# Push to GitLab
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitLab username.

### Step 3: Enable GitLab Pages

GitLab Pages will automatically deploy when you push to the `main` branch thanks to the `.gitlab-ci.yml` configuration.

1. Go to your GitLab project
2. Navigate to **Settings** → **Pages**
3. After the CI/CD pipeline completes (check **CI/CD** → **Pipelines**), your site URL will appear
4. Your site will be available at: `https://YOUR_USERNAME.gitlab.io/resume-portfolio/`

### Step 4: Monitor Deployment

1. Click **CI/CD** → **Pipelines** in your GitLab project
2. Watch the pipeline run (usually takes 1-2 minutes)
3. Green checkmark = successful deployment ✅
4. Click on the pipeline to see detailed logs if needed

## 📝 Customization

### Updating Content

Edit `content.json` to update your:
- Professional information
- Work experience
- Education
- Skills
- Awards
- Publications

After editing, commit and push the changes:

```bash
git add content.json
git commit -m "Update resume content"
git push
```

GitLab Pages will automatically rebuild and deploy.

### Changing Colors

The accent color is defined in both `index.html` and `tailwind.config.js`. To change it:

1. Open `index.html`, find `'accent': '#3b82f6'` and change the hex color
2. Open `tailwind.config.js` and update the same value
3. Commit and push

### Customizing Design

The HTML uses Tailwind CSS utility classes. Key classes to modify:

- **Background**: `bg-neutral-950` (body background)
- **Text colors**: `text-neutral-200`, `text-neutral-400`, etc.
- **Spacing**: `mb-16`, `py-12`, etc.
- **Typography**: Font sizes are in `text-lg`, `text-xl`, etc.

## 📁 Project Structure

```
resume-portfolio/
├── index.html              # Main resume page
├── content.json            # Your professional data
├── package.json            # Build configuration
├── tailwind.config.js      # Tailwind customization
├── .gitlab-ci.yml         # GitLab Pages deployment config
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## 🔧 Troubleshooting

### Pipeline Failing?
- Check **CI/CD** → **Pipelines** → Click failed job for logs
- Ensure `content.json` is valid JSON (use a JSON validator)

### Site Not Updating?
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check that the pipeline completed successfully
- Wait 1-2 minutes after pipeline completion

### Content Not Loading?
- Open browser console (F12) to check for errors
- Ensure `content.json` exists and is valid
- Check that file paths are correct (case-sensitive on Linux/GitLab)

## 📄 License

© 2026 Maureen Allanic. All rights reserved.
