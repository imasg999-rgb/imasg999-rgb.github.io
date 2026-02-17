# Adding a Favicon to Your Portfolio

A favicon is the small icon that appears in browser tabs. Here's how to add one:

## Quick Method (Using an Emoji or Text)

Add this to the `<head>` section of your `index.html`:

```html
<!-- Simple emoji favicon -->
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>👨‍💻</text></svg>">
```

## Professional Method (Custom Icon)

### Step 1: Create Your Icon
1. Go to https://favicon.io
2. Choose "Text" and enter your initials: "MIA"
3. Or upload a logo/image
4. Download the generated favicon package

### Step 2: Add Files to Your Project
Extract these files to the same folder as `index.html`:
- favicon.ico
- favicon-16x16.png
- favicon-32x32.png
- apple-touch-icon.png

### Step 3: Add to Your HTML
Add these lines in the `<head>` section of `index.html`:

```html
<link rel="icon" type="image/x-icon" href="/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
```

### Step 4: Upload
- If using Netlify: Upload all files together
- If using GitHub: Upload favicon files to your repository

## Easy Online Tools
- https://favicon.io - Generate from text or image
- https://realfavicongenerator.net - Professional options
- https://www.favicon-generator.org - Simple and quick

## Current Setup
Your portfolio currently uses Google Fonts, so adding a favicon will make it even more professional!
