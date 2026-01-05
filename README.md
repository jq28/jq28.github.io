# Poh Jia Qing - Academic Website

Personal academic website with sidebar navigation.

## Setup for GitHub Pages

1. **Create GitHub repository** named `<your-username>.github.io`
   - Example: `jqpoh.github.io`

2. **Upload files**:
   - `index.html`
   - `style.css`
   - `profile.jpg` (your photo)

3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Click Save

4. **Live at**: `https://<your-username>.github.io`

## Adding Your Profile Photo

1. Use a professional headshot (square, ~400x400px)
2. Name it `profile.jpg`
3. Upload to repository root

**Temporary fix**: Comment out the image line in `index.html`:
```html
<!-- <img src="profile.jpg" alt="Poh Jia Qing" class="profile-img"> -->
```

## Customization Guide

### Adding Links

**Google Scholar** (when you create it):
```html
<p><i class="fas fa-graduation-cap"></i> <a href="YOUR_GOOGLE_SCHOLAR_URL" target="_blank">Google Scholar</a></p>
```

**GitHub** (with "Under Construction" tag):
```html
<p><i class="fab fa-github"></i> <a href="https://github.com/YOUR_USERNAME" target="_blank">GitHub <span class="construction">(Under Construction)</span></a></p>
```

### Adding New Publications

When MPCL is submitted as preprint:

```html
<h3 class="pub-category">Preprint Papers</h3>

<div class="publication">
    <div class="pub-title">
        <strong>Your Paper Title</strong>
    </div>
    <div class="pub-authors">
        <strong>Poh, Jia Qing</strong>, Co-authors
    </div>
    <div class="pub-venue">
        <em>arXiv Preprint</em>, 2025
    </div>
    <div class="pub-links">
        <a href="ARXIV_LINK" target="_blank">[Paper]</a>
        <a href="PDF_LINK" target="_blank">[PDF]</a>
        <a href="CODE_LINK" target="_blank">[Code]</a>
        <img src="https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=social" alt="GitHub stars">
    </div>
</div>
```

### Adding GitHub Stars Badge

When you publish code:
```html
<img src="https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=social" alt="GitHub stars">
<img src="https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPO?style=social" alt="GitHub forks">
```

### Updating "About Me" Projects

When your research focus changes:
```html
<p>
    I am currently working on <strong>new project topic</strong> and <strong>another project</strong>.
</p>
```

## Structure

```
repository/
├── index.html       # Main page
├── style.css        # Styling with sidebar navigation
├── profile.jpg      # Your photo
└── README.md        # This file
```

## Features

- **Sidebar navigation** with quick links
- **Responsive design** - works on mobile
- **Clean layout** similar to MMLab researchers
- **Easy to update** - just edit HTML
- **GitHub stars integration** ready

## Sections

1. **About Me** - Bio + current research projects
2. **Publications** - Published papers (add Preprints when ready)
3. **Awards** - Academic achievements
4. **Teaching** - TA experience

## When to Update

- **Immediately**: Add your profile photo
- **When paper is on arXiv**: Add to "Preprint Papers" section
- **When paper is accepted**: Move to "Conference Papers"
- **When code is public**: Add GitHub repo links with stars badge
- **When you create Google Scholar**: Add link in sidebar

## Tips

1. Keep "About Me" section updated with current work
2. Only add papers to Publications when they're written (preprint or published)
3. Use GitHub stars badges to show project popularity
4. Update regularly but don't over-engineer

---

**Contact**: jqpoh2000@gmail.com
