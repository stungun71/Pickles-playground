# Pickle's Playground

Your personal app collection for friends and family!

## What's Inside

- **index.html** - Main landing page (this is what shows up first)
- **photo-organizer.html** - Photo organizing app (ready!)
- **coloring-page-creator.html** - Photo to coloring page converter (ready!)
- **coloring-page-factory-README.html** - Instructions for the coloring page creator

## How to Upload to GitHub Pages

### Easy Method (No Terminal Required!)

1. **Create a new repository on GitHub:**
   - Go to github.com
   - Click the "+" button → "New repository"
   - Name it whatever you want (like "pickles-playground")
   - Make it **Public**
   - Check "Add a README file"
   - Click "Create repository"

2. **Upload your files:**
   - In your new repo, click "Add file" → "Upload files"
   - Drag ALL the files from this folder into the upload area:
     - index.html
     - photo-organizer.html
     - coloring-page-creator.html
     - coloring-page-factory-README.html
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to your repo's **Settings**
   - Click **"Pages"** in the left sidebar
   - Under "Source" select **"main"** branch
   - Click **Save**
   - Wait 2-3 minutes

4. **Your site will be live at:**
   `https://stungun71.github.io/pickles-playground`

## Editing the Site

Want to change the email address or other text?

1. Open `index.html` in any text editor (Notepad, TextEdit, VS Code, whatever)
2. Find this line:
   ```html
   <a href="mailto:your-email@example.com">your-email@example.com</a>
   ```
3. Replace `your-email@example.com` with your actual email
4. Save the file
5. Re-upload to GitHub (just drag the updated file into the repo)

## Adding More Apps

When you finish a new app:

1. Add the HTML file to this folder
2. Open `index.html`
3. Find one of the "Coming Soon" app cards
4. Change the status from `<span class="app-status">Coming Soon</span>` to `<span class="app-status ready">Ready</span>`
5. Change the link from `<a href="#" class="download-btn disabled">Coming Soon</a>` to `<a href="your-new-app.html" download class="download-btn">Download</a>`
6. Upload to GitHub

## Need Help?

If you get stuck, just message me and I'll walk you through it!

---

**Made with ❤️ by Pickle**
