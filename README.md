# GWBF Portfolio: Gidraf Wachira

A targeted portfolio for the **Regional Program Lead, East Africa** role at the Global Whole Being Fund (Resourcing Local Climate Leadership initiative, with the IKEA Foundation).

It maps each duty and required skill in the role description to evidence from my work at NetHope, Connected Farmer (Vodacom Group) and Agri-wallet, and links to projects, published reports, media features and photos.

## Publish with GitHub Pages

Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)`.
The site will be at `https://gidrafwachira.github.io/GWBF_Portfolio/`.

## Structure

- `index.html`: the whole site (no build step)
- `assets/docs/`: published reports (Tana River case study, Yumbe report, Nigeria report)
- `assets/photos/`: add work photos here

## Adding photos to "Gidraf at work"

1. Put the image in `assets/photos/` (e.g. `tana-river-training.jpg`).
2. In `index.html`, find `const photos = [` near the bottom and add a line:
   `{src:"assets/photos/tana-river-training.jpg", caption:"Early warning training, Tana River, 2024"},`
