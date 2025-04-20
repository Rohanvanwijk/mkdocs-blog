# Rohan blog

Used tools

- [Mkdocs](https://www.mkdocs.org/)
- [Theme: terimal](https://ntno.github.io/mkdocs-terminal/)
- Host on Clouflare pages: [blog.rohanvanwijk.nl](https://blog.rohanvanwijk.nl/)

## How to get started

1. Install [Mkdocs](https://www.mkdocs.org/) -- pip install mkdocs
2. run mkdocs serve

## Tips

- Dont use underscore for filenames in docs
- prefix image kit url with cloudflare worker for the correct signature: https://imagekit.rohan-10.workers.dev?url=foo
- Windows desktop build command: python3 C:\Users\rohan\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.13_qbz5n2kfra8p0\LocalCache\local-packages\Python313\site-packages\mkdocs\__main__.py build

## Image magick commands

Collage side by side, resized to 900px and gap of 8px

Add -rotate 90 to rotate 90 degrees

```bash
magick montage -geometry 900x900+8+8 image-1.JPG image-2.JPG output-montage.jpg
```
