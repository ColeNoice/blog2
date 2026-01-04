# My Hugo Blog

This blog is automatically synced from my Obsidian notes and built with Hugo.

## Theme

- **PaperMod**

## Workflow

1. Write notes in Obsidian
2. Set `share: true` in front matter for posts you want to publish
3. Push to Obsidian repository
4. GitHub Actions automatically syncs and builds the blog
5. Blog is deployed to GitHub Pages

## Local Development

```bash
# Install Hugo
# https://gohugo.io/installation/

# Clone this repository
git clone <your-repo-url>
cd <repo-name>

# Initialize theme submodule
git submodule update --init --recursive

# Run local server
hugo server -D
```

## Publishing

Just push your changes to the main branch, and GitHub Actions will handle the rest!
