# Daily Pleiadian Wisdom ✨

A web page that displays a different Pleiadian wisdom message for each day of the year.

## 🌟 Features

- **365 unique wisdoms** - A different message for each day of the year
- **Global synchronization** - All users see the same message on the same day
- **Responsive design** - Works perfectly on desktop and mobile
- **Cosmic theme** - Visual inspired by the cosmos with subtle animations
- **Hidden phrases** - Messages are stored in a separate JSON file

## 🚀 How to host on GitHub Pages

### Step 1: Create a GitHub repository

1. Go to [github.com](https://github.com) and log in
2. Click on "New repository" (green button)
3. Repository name: `pleiadian-wisdom` (or any name you prefer)
4. Mark as **Public**
5. Click "Create repository"

### Step 2: Upload files

1. On the created repository page, click "uploading an existing file"
2. Drag the files:
   - `index.html`
   - `wisdoms.json`
   - `README.md`
3. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. In the repository, click on "Settings"
2. In the sidebar, click on "Pages"
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes

### Step 4: Access your site

Your site will be available at:
```
https://YOUR-USERNAME.github.io/pleiadian-wisdom/
```

Replace `YOUR-USERNAME` with your GitHub username.

## 📱 Testing locally

To test before uploading:

1. Open the `index.html` file directly in your browser
2. **IMPORTANT**: For security reasons, the browser may block JSON loading locally
3. Use a simple local server:
   ```bash
   # If you have Python installed:
   python -m http.server 8000

   # Then access: http://localhost:8000
   ```

## 🎨 Customization

### Change colors

Edit the colors in the `index.html` file, look for:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add more wisdoms

Edit the `wisdoms.json` file and add new phrases to the array.

### Modify the visual

All styling is within the `<style>` tag in the HTML.

## 📖 About the Wisdoms

The 365 messages are channeled Pleiadian wisdom, focused on:
- Consciousness elevation
- Unconditional love
- Connection with the Source
- Planetary ascension
- Spiritual awakening

## 🔒 Message Security

The wisdoms are in a separate JSON file, not directly in the HTML.
This makes it harder (but not impossible) to view all phrases at once.

## 📄 License

Free for personal and spiritual use. Share the light! ✨

---

**Made with 💜 for the elevation of human consciousness**
