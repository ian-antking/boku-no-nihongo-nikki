# Boku-no-Nihongo-Nikki

This is a personal blog where I write about my journey learning Japanese. The blog includes language study notes, thoughts on daily life, and interesting words I come across.

## Setup

To get started with this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/boku-no-nihongo-nikki.git
   cd boku-no-nihongo-nikki
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   hexo server
   ```

   Visit `http://localhost:4000` in your browser to view the site.

## Deployment

This site is automatically deployed using GitHub Actions. Each push to the `main` branch triggers the build and deployment process to GitHub Pages.

## Custom Domain

The site is accessible at `blog.antking.co`.

## Optimising images

```bash
magick "$image" -resize 1600x1600\> -strip -quality 85 "$output"
```
