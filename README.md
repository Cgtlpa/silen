# silen-website

Static website for **Silen Linux** - served at https://cgtlpa.github.io/silen/.

- `index.html` - home
- `get.html` - ISO downloads (standard + NVIDIA; Arch, Debian and Void bases coming soon)
- `packages.html` - spk package manager + repository
- `styles.css` - Bebas Neue + warm brown theme

No build step. Open `index.html` or serve the folder:

```sh
python3 -m http.server -d . 8080
```

ISO files: [Silen-Linux on Hugging Face](https://huggingface.co/datasets/vgzz/silen-isos).
