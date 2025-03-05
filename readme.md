# Rohan blog

Used tools

- [Mkdocs](https://www.mkdocs.org/)
- [Theme: terimal](https://ntno.github.io/mkdocs-terminal/)
- Host on Clouflare pages: [blog.rohanvanwijk.nl](https://blog.rohanvanwijk.nl/)

## How to get started

1. Install [Mkdocs](https://www.mkdocs.org/) -- pip install mkdocs
2. run mkdocs serve

## Tips

- Dont use underscore for filenames

## Image magick commands

Collage side by side, resized to 900px and gap of 8px

Add -rotate 90 to rotate 90 degrees

```bash
magick montage -geometry 900x900+8+8 image-1.JPG image-2.JPG output-montage.jpg
```
