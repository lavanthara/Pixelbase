# ◈ Pixelbase

**A simple, lightweight image-to-Base64 converter that runs entirely in your browser.**

Pixelbase lets you convert images into Base64 strings, Data URLs, and Markdown image syntax. Upload an image, paste one from your clipboard, or provide an online image URL.

<p align="center">
  <a href="https://lavanthara.github.io/pixelbase/">
    <strong>🌐 Visit Pixelbase</strong>
  </a>
</p>

## ✨ Features

- **Image Upload** — Select images directly from your device.
- **Drag & Drop** — Drop images into the upload area.
- **Clipboard Pasting** — Paste copied images and screenshots using `Ctrl + V` or `⌘ + V`.
- **Online Image URLs** — Convert images directly from the internet.
- **Live Preview** — See your image before using the output.
- **Multiple Output Formats:**
  - Data URL (`data:image/...;base64,...`)
  - Raw Base64
  - Markdown Image (`![alt](data:image/...)`)
- **Copy to Clipboard** — Copy the generated output instantly.
- **Download as TXT** — Save the generated output as a text file.
- **Privacy-Friendly** — Images are processed locally in your browser.

## 🚀 Usage

1. Visit [Pixelbase](https://lavanthara.github.io/pixelbase/).
2. Upload an image, paste one, or enter an image URL.
3. Choose your preferred output format.
4. Copy the generated result or download it as a `.txt` file.

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- FileReader API
- Clipboard API
- Fetch API

No frameworks, dependencies, or backend required.

## 🔒 Privacy

Pixelbase is a fully static website.

- Uploaded images never leave your browser.
- Pasted images are processed locally.
- Online images are fetched directly from their respective hosts.
- No Pixelbase backend or image storage is involved.

## ⚠️ Limitations

- Online image hosts must allow CORS requests.
- Base64 increases the original image size by approximately 33%.
- Some Markdown platforms, including GitHub, restrict embedded Base64 images.
- Very large images may consume considerable browser memory.

## 📄 License

Distributed under the [MIT License](LICENSE).

---

<p align="center">
  Made with simplicity in mind. ◈
</p>
