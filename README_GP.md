# French-FastPitch-HiFiGAN-G2P

This repository documents experiments, demos, and notes on French Text-to-Speech (TTS) using **FastPitch**, **HiFi-GAN**, and **G2P** (grapheme-to-phoneme conversion), powered by Quarto for beautiful, reproducible websites.

## 📁 Structure

```
.
├── _quarto.yml        # Quarto site configuration
├── index.qmd          # Home page
├── notebooks/         # Jupyter notebooks
│   └── fastpitch-hifigan-demo.ipynb
├── README.md          # This file
```

## 🚀 Quickstart

1. **Clone this repo:**
   ```sh
   git clone https://github.com/<your-username>/French-FastPitch-HiFiGAN-G2P.git
   cd French-FastPitch-HiFiGAN-G2P
   ```

2. **Install [Quarto](https://quarto.org/docs/get-started/):**
   - Download from https://quarto.org/download/
   - (Optional) For notebooks: `pip install jupyter`

3. **Preview the site:**
   ```sh
   quarto preview
   ```

4. **Publish to GitHub Pages:**
   - Push to GitHub.
   - In repo settings, enable GitHub Pages (branch: `main` and `/` folder).
   - Or use: `quarto publish gh-pages`

## 📝 Add Your Work

- Place new notebooks in `notebooks/`.
- Add `.qmd` or `.md` files for guides, results, or commentary.
- Update `_quarto.yml` to add them to the navigation bar.

---

Happy experimenting! 🎤🇫🇷
