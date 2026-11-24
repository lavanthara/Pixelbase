# ◈ Pixelbase

**A lightweight, browser-based image-to-Base64 converter.**

Pixelbase converts images into Base64 strings and Data URLs, with support for file uploads, clipboard pasting, and online image URLs. Everything runs directly in your browser — no backend or account required.

## ✨ Features

- **File Upload** — Select images from your device.
- **Drag & Drop** — Drop images directly into the application.
- **Clipboard Support** — Paste copied images and screenshots using `Ctrl + V` or `⌘ + V`.
- **Image URLs** — Convert images directly from online URLs.
- **Live Preview** — Preview your image after conversion.
- **Multiple Output Formats:**
  - Data URL (`data:image/...;base64,...`)
  - Raw Base64
  - Markdown Image (`![alt](data:image/...)`)
- **Copy to Clipboard** — Copy generated output instantly.
- **Download** — Save the generated Base64 as a `.txt` file.
- **Privacy-Friendly** — Images are processed locally in your browser.

## 🚀 Getting Started

Pixelbase is a static website. No installation, dependencies, or build tools are required.

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/lavanthara/pixelbase.git
   ```

2. Enter the project directory:

   ```bash
   cd pixelbase
   ```

3. Open `pixelbase.html` in your browser.

Alternatively, rename it to `index.html` and serve it using any static web server.

## 🌐 Deployment

Pixelbase can be hosted for free using **GitHub Pages**:

1. Push the project to a GitHub repository.
2. Rename `pixelbase.html` to `index.html`.
3. Open your repository's **Settings → Pages**.
4. Select your deployment branch and root directory.
5. Save your settings.

Your website will be available through your GitHub Pages URL.

## ⚠️ Notes & Limitations

- Online image URLs must allow cross-origin requests (CORS). Some image hosts block browser access.
- Base64 encoding increases image size by approximately 33%.
- Some Markdown platforms, including GitHub, restrict embedded Base64 images in Markdown.
- Large images may consume significant browser memory.

## 🔒 Privacy

Pixelbase does not have a backend.

- Local files are processed entirely in your browser.
- Pasted images are processed locally.
- Online images are fetched directly from their respective hosts.
- No images are uploaded to a Pixelbase server.

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- FileReader API
- Clipboard API
- Fetch API

---

<p align="center">
  Made with simplicity in mind.
</p>
