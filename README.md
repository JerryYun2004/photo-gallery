# Jerry Yun — Photo Gallery (v0)


A minimal static site that shows one image, deployed with GitHub Pages. Future versions will add grids, EXIF, lazy-loading, and albums.


## Quick start


1. **Create the folder** and add files from this repo structure.
2. Put your first image at `images/Amden.jpg` (JPG around 2500–3200px on the long edge is a good balance).
3. (Optional) Losslessly compress the image with `ImageOptim` / `Squoosh`.


## Publish with GitHub Pages


### A) New repository
- Create a new GitHub repo (e.g., `photo-gallery`).
- In your local folder:
```bash
git init
git add .
git commit -m "v0: one-image site"
git branch -M main
git remote add origin https://github.com/<your-username>/photo-gallery.git
git push -u origin main