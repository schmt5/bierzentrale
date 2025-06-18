# Bierzentrale CzechPoints

A website showcasing Czech beers available in Switzerland, deployed at [bierzentrale-czechpoints.ch](https://bierzentrale-czechpoints.ch/).

## About

This site promotes traditional Czech beers and their availability in Swiss locations (Bern and Zürich). It features high-quality beer originals from traditional Czech breweries.

## Development & Deployment

### Prerequisites

* Node.js installed
* Git configured
* Repository cloned locally

### Project Structure

```
bierzentrale/
├── dist/           # Deployable files (this gets deployed to GitHub Pages)
├── package.json    # Project configuration
├── README.md       # This file
└── [source files]  # Your editable content files
```

### How to Update Content

#### 1. Make Your Changes Locally

Edit your HTML, CSS, JavaScript, and image files locally. Make sure any changes you want to go live are placed in or copied to the `dist/` folder.

#### 2. Deploy to GitHub Pages

Once your `dist/` folder contains all the updated files:

```bash
npm run deploy
```

This command:
* Takes everything from the `dist/` folder
* Pushes it to the `gh-pages` branch
* Makes it live at both:
   * `https://schmt5.github.io/bierzentrale` (GitHub Pages URL)
   * `https://bierzentrale-czechpoints.ch/` (custom domain)

#### 3. Save Your Source Changes

Don't forget to commit your source changes to the main branch:

```bash
git add .
git commit -m "Update website content"
git push origin main
```
