# Spectrogram Scope

A single-page tool for finding text or images hidden in the spectrogram of an audio file (useful for CTF challenges).

- Runs fully in the browser. Audio files are never uploaded.
- WAV files of any size are read directly; MP3, FLAC, OGG and M4A are decoded by the browser.
- Drag a box on the picture to zoom into a time and frequency range.
- Controls for window size, channel (left, right, left minus right), colours, noise floor and brightness.

## Use it

Open `index.html` in a browser, or host it with GitHub Pages.

## Host on GitHub Pages

1. Create a new repository and upload `index.html` and `README.md`.
2. Go to Settings, then Pages.
3. Under Build and deployment, set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.
