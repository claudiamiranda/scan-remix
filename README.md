# Scan Remix

A one-screen browser studio for remixing 3D scans and turning them into printable collage cutouts. Built for a hands-on scanning and collage workshop at Big Wonder, a youth makerspace in Oakland.

## What it does

- **Open a scan** (GLB, or OBJ without color) from a phone scanning app such as Scaniverse, or drop it on the mat.
- **Shape:** twist, bend, melt, lumpy, puff up, stretch, glitch, or "Surprise me."
- **Sculpt:** pull out, push in, and smooth brushes, with size and strength.
- **Look:** the scan's original colors, clay, wireframe, or silhouette in risograph ink colors or any color, or **your photo** wrapped onto the scan (around it or flat from the front, repeated 1, 2 or 4 times).
- **View:** front, back, side, other side, from above, from below, or turn it freely.
- **Cutouts:** the scissors button captures the current view as a transparent, tightly cropped PNG, ready to print and cut.

Undo and redo cover every change, and Reset all returns the scan, look and view to the start. Nothing is uploaded: scans stay in the browser.

## Run it

It is a single `index.html` with no build step, plus `doll_01.glb`, a scan of a doll that loads as the sample. Open it in a browser, or turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

Uses [three.js](https://threejs.org) r147 from a CDN, so it needs an internet connection on first load.
