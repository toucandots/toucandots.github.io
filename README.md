# Agency Jekyll theme

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# Development Setup

## Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem
- Git

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd toucandots-website
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

## Development Commands

### Start Development Server

```bash
bundle exec jekyll serve
```

This will start a local development server at `http://127.0.0.1:4000` with auto-regeneration enabled.

### Start with Live Reload (if ports are available)

```bash
bundle exec jekyll serve --livereload
```

### Build for Production

```bash
bundle exec jekyll build
```

This generates the static site in the `_site/` directory.

### Clean Build

```bash
bundle exec jekyll clean
bundle exec jekyll build
```

## Project Structure

- `_config.yml` - Site configuration
- `_layouts/` - Page templates
- `_includes/` - Reusable components
- `_posts/` - Portfolio projects
- `apps/` - App-related pages
- `img/` - Images and assets
- `css/` - Stylesheets
- `js/` - JavaScript files
- `_site/` - Generated site (auto-generated, not committed)

## Adding Content

### Portfolio Projects

Add new projects as markdown files in `_posts/` directory.

### Apps

Add new app pages in the `apps/` directory structure.

## Deployment

The `_site/` folder contains the built website. Deploy its contents to your web server.

**Note:** The `_site/` folder is auto-generated and should not be committed to version control.

# How to use

###Portfolio

Portfolio projects are in '/\_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '\_config.yml'

Images are in '/img/team/'

# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)
