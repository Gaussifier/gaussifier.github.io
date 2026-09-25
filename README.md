# Gaussifier: Fast 2D Gaussian Decomposition

Anonymous project page for a paper under double-blind review. The page gives the title and
abstract, then traces one Gaussifier forward pass on 13 example images. It shows the dense heads and
predicted Gaussian count, the equal-mass Voronoi placement, each state of the correction loop, and
the final Gaussians.

## View locally

The page loads `data/<example>.json`, so it needs a web server rather than `file://`:

```
python3 -m http.server 8000
```

then open <http://localhost:8000/>.

## Hosting

Static files only (`index.html`, `data/`, `.nojekyll`), ready for GitHub Pages from the repository
root.

## Images

Examples come from the Kodak and DIV2K validation images and from the sample images released with
Image-GS; they are used here for illustration only.
