# Maintainers.dev Website

This repository holds the content and code for the [maintainers.dev](https://maintainers.dev) website. The website is built using the [hugo static site generator](https://gohugo.io/).

### Directories

The following is a non-exhaustive list of the directories and their uses in this project:

- `archetypes` - Content templates for Hugo.
- `art` - Source artwork files for the site.
- `content` - Main content (articles, posts).
- `data` - Additional data for Hugo.
- `layouts` - Site layouts for Hugo. Managed mostly at a theme level instead.
- `static` - Static files for site content.
- `themes/maintainers` - The Hugo theme used for the site.

### Building

As a prerequisite, you'll need [hugo](https://gohugo.io/) installed on your system and accessible via command line.
Since the website is fairly plain Hugo, you can use hugo commands to build the site:

```bash
# Build the site to a `public` folder.
hugo

# Start a server and build upon changes
hugo serve
```

Alternatively, NPM scripts are used provide common development actions:

```bash
# Start server in development mode, including draft/future posts
npm run dev

# Build site for production
npm run build
```

### Media & Git LFS

This project uses [git lfs](https://git-lfs.com/) to manage media binary files efficiently via standard git flows. You'll have to make sure you have this installed to pull down the project with media files.

If intending to contribute, with added media files, then GitHub has a quirk in that you cannot push LFS files to a fork. Instead you'd need to request access to the main project and push a branch directly on the main repo.

### Article Style Guide

Articles on the site should try to follow these rules:

- Tone should be in a semi-formal friendly tone, adapting to the intended audience experience level.
- Articles should be small and digestible, targeting a few paragraphs. New articles should be favoured over creating sections within a single article.
- Two sections may trail the article:
  - Common Questions - Links formatted as questions, leading to other articles.
  - Further Reader - Additional external resources, or internal resources that do not fit into "Common Questions".