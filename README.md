# Personal Website - Chandan Sreedhara

A clean, minimalist personal website showcasing research, projects, and professional experience. This website is creating with the help of Claude AI

## Setup Instructions

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `chandanms.github.io` (replace with your GitHub username)
3. Make it **public**
4. Don't initialize with README (we'll push these files)

### 2. Upload Files
```bash
# Clone the repository
git clone https://github.com/chandanms/chandanms.github.io.git
cd chandanms.github.io

# Copy the index.html and style.css files to this directory

# Add and commit
git add .
git commit -m "Initial website setup"
git push origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select branch: `main`
4. Under "Folder", select: `/ (root)`
5. Click **Save**

Your site will be live at `https://chandanms.github.io` in 1-2 minutes!

## Adding Your Photo

1. Add a profile photo (named `profile.jpg` or `profile.png`) to the repository
2. In `index.html`, uncomment this line:
   ```html
   <!-- <img src="profile.jpg" alt="Chandan Sreedhara" class="profile-photo"> -->
   ```
   So it becomes:
   ```html
   <img src="profile.jpg" alt="Chandan Sreedhara" class="profile-photo">
   ```

## Customization

### Update Links
- Replace placeholder LinkedIn URL in the navigation
- Update project links (arXiv, Hugging Face, GitHub, papers, case studies)
- Add your actual paper and project URLs

### Modify Content
- Edit `index.html` to update your bio, projects, and research interests
- All content is in plain HTML, easy to modify
- Keep the structure simple and focused on your work

### Color Scheme
To change colors, edit `style.css`:
- Links: Change `#0066cc` (line 79, 98, etc.)
- Text: Change `#333`, `#555`, `#888` values
- Backgrounds: Change `#f5f5f5` for interest tags

## Testing Locally

You can test the site locally before pushing:

```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server

# Then open: http://localhost:8000
```

## Updates

To update your site:
1. Edit the HTML/CSS files
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update content"
   git push origin main
   ```
3. Changes will appear on your site within a minute

## Optional Enhancements

- **Custom Domain**: Add a CNAME file with your domain name
- **Analytics**: Add Google Analytics tracking code
- **Blog Section**: Add a blog/posts page for research updates
- **Dark Mode**: Add a dark mode toggle for better accessibility

## Support

For GitHub Pages issues, see: https://docs.github.com/en/pages
