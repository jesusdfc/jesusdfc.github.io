
# Jesús de la Fuente's GitHub Pages Template

This repository is a template for creating a personal website using the **Minimal Mistakes** Jekyll theme on GitHub Pages. It is designed for individuals who want to showcase their CV, publications, projects, and other professional information in a simple and elegant format.

## Features
- **Customizable Layouts**: Based on the Minimal Mistakes theme, allowing for flexible and easy-to-use page layouts.
- **Dedicated Pages**: Includes pre-built templates for CV, publications, teaching, and talks.
- **Responsive Design**: The theme is fully responsive and works on all screen sizes.
- **Markdown-Based**: All content is written in Markdown, making it simple to edit and update.

## Folder Structure

```plaintext
.
├── _data                  # YAML/JSON files for storing structured data (e.g., navigation)
├── _includes              # Custom components (e.g., headers, footers)
├── _layouts               # Layout templates for different page types
├── _pages                 # Pre-built pages like CV, Talks, Publications, etc.
├── _sass                  # Custom styles
├── _site                  # Compiled site (generated during local builds)
├── assets                 # Images, CSS, JavaScript files
│   └── files              # PDF files (e.g., CV)
├── docs                   # Additional documentation (optional)
├── .github                # GitHub-specific configurations (e.g., workflows)
├── _config.yml            # Main configuration file for Jekyll
├── Gemfile                # Ruby gems and dependencies
├── Gemfile.lock           # Locked versions of dependencies
└── index.html             # Homepage of the site
```

## Usage

### 1. Fork the Repository
Click on the "Fork" button at the top-right corner of the repository page to create your own copy of this template.

### 2. Customize `_config.yml`
Modify the `_config.yml` file to update your site’s details:
- **title**: Your name or the title of your website.
- **author**: Replace the author details with your information (name, bio, location, and social links).
- **remote_theme**: Ensure the theme is set to `mmistakes/minimal-mistakes@latest`.

### 3. Add Your Content
- **Homepage (`index.html`)**: Customize the homepage with a brief introduction and links to other sections.
- **Assets**: Add your images, CSS, and PDF files (like your CV) in the `assets` folder.
- **Pages**: Modify the existing templates in `_pages` to add your CV, publications, teaching experiences, etc. You can use Markdown to create new pages if needed.

### 4. Local Development
To build and preview your site locally:
1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/).
2. Install [Bundler](https://bundler.io/):
   ```bash
   gem install bundler
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
4. Install dependencies:
   ```bash
   bundle install
   ```
5. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```
   Your site should be available at `http://localhost:4000`.

### 5. Deploy on GitHub Pages
1. Push your changes to your GitHub repository.
2. Ensure GitHub Pages is enabled in the repository settings:
   - Go to **Settings** > **Pages**.
   - Set the source to the `main` or `master` branch.
3. Your site will be live at `https://yourusername.github.io/`.

## Example Pages
- **CV**: `/cv/`
- **Publications**: `/publications/`
- **Teaching**: `/teaching/`
- **Talks**: `/talks/`

## Troubleshooting
- If you encounter issues while building the site, ensure all dependencies are installed, and try running `bundle update` to refresh them.
- For `minimal-mistakes-jekyll` theme issues, refer to the [theme documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

## Credits
This template is based on the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme. Created by **Jesús de la Fuente Cedeño**.
