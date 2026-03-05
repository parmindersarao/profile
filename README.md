# Parminder Singh - Personal Portfolio 🚀

This is a modern, responsive static portfolio website created based on my CV, emphasizing Artificial Intelligence, Machine Learning, and Data Science. It is built purely using HTML and Tailwind CSS (via CDN) making it lightning-fast and extremely simple to deploy.

## Features
- **Fully Responsive Targetting**: Works on Mobile, Tablet, and Desktop.
- **Modern UI**: Styled with Tailwind CSS for clean, Apple-like aesthetics.
- **Zero Build-steps**: Just standard an `index.html` file.
- **Cloudflare Ready**: Can be pushed immediately to Cloudflare Pages.

## How to Deploy on Cloudflare Pages (Free & Fast)

Deploying a raw static HTML file via Cloudflare is highly industry-standard, as it offers global CDN distribution and automatic SSL out of the box.

### Option 1: Direct Upload (Easiest)
1. Go to the [Cloudflare Dashboard](https://dash.cloudflare.com/) and create a free account if you haven't.
2. Navigate to **Workers & Pages** in the left sidebar.
3. Click **Create Application** -> Select the **Pages** tab.
4. Click **Upload assets**.
5. Name your project (e.g., `parminder-portfolio`).
6. Drag and drop the folder containing your `index.html` file.
7. Click **Deploy**. Your website will be live in seconds!

### Option 2: Connect via GitHub (Best for updates)
1. Initialize a Git repository in this folder and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of portfolio"
   git branch -M main
   # Add your GitHub remote and push here
   ```
2. In Cloudflare, under **Workers & Pages**, click **Create Application** -> **Pages**.
3. Choose **Connect to Git** and authorize your GitHub account.
4. Select this repository.
5. In the Build settings:
   - Framework preset: `None`
   - Build command: *(leave empty)*
   - Build output directory: *(leave empty or set to `/`)*
6. Click **Save and Deploy**. Cloudflare will now automatically update your site every time you push to GitHub!

## Local Testing
To preview the website locally, simply drag the `index.html` file into Google Chrome, Firefox, or Safari. Alternatively, if you have Python installed, you can run a local server:

```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.