# silen-website

Static website for **Silen Linux**.

- `index.html` — home
- `download.html` — ISO downloads (Standard + NVIDIA)
- `styles.css` — muted cyan-blue + purple theme

No build step. Open `index.html` or serve the folder:

```sh
python3 -m http.server -d . 8080
```

ISO links point at [SilenLinux Releases](https://github.com/Cgtlpa/SilenLinux/releases).
