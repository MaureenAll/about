# Website Customization Guide

This guide will help you customize your personal resume website.

## Quick Start

Your website consists of two main files:
- `index.html` - Contains the content and structure
- `style.css` - Contains the styling and colors

## Customizing Content

### 1. Header Section
Edit the name and tagline in `index.html`:
```html
<h1>Maureen</h1>
<p class="tagline">Professional Resume</p>
```

### 2. About Section
Replace the placeholder text with your own introduction:
```html
<section id="about" class="section">
    <h2>About Me</h2>
    <p>Your personal introduction here...</p>
</section>
```

### 3. Work Experience
Update each experience item with your actual job details:
- Position title
- Company name
- Date range
- Key responsibilities and achievements

### 4. Education
Add your educational background:
- Degree name
- Institution name
- Graduation year
- Relevant coursework or honors

### 5. Skills
Customize the three skill categories:
- Technical Skills
- Professional Skills
- Tools & Technologies

### 6. Contact Information
Update your contact details:
- Email address
- LinkedIn profile URL
- GitHub username

## Customizing Design

### Colors
The main color scheme uses purple/blue gradients. To change colors, edit `style.css`:
- Header gradient: `.header` background
- Section headers: `.section h2` color
- Links and accents: Update `#667eea` and `#764ba2`

### Fonts
Change the font family in the `body` selector in `style.css`:
```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

### Layout
The website is responsive and adapts to different screen sizes automatically.

## Publishing to GitHub Pages

1. Make sure your changes are committed to the main/master branch
2. Go to your repository Settings on GitHub
3. Navigate to Pages section
4. Select the branch to deploy (usually `main`)
5. Your site will be available at: `https://maureenall.github.io/`

## Tips

- Keep content concise and professional
- Use bullet points for easy reading
- Update contact information to be current
- Test on different devices to ensure responsiveness
- Add your own sections if needed (Projects, Publications, etc.)

## Need Help?

If you need assistance customizing your website, feel free to open an issue in the repository.
