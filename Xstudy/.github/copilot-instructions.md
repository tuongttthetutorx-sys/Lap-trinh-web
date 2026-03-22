# Copilot Instructions for Xstudy

## Project Overview
Xstudy is a simple static HTML website, currently consisting of a single `index.html` file. It appears to be the foundation for a study or educational tool, with Vietnamese language support.

## Architecture
- **Single-page application**: The entire site is contained in `index.html`
- **No external dependencies**: Pure HTML5 without CSS, JavaScript, or frameworks
- **Language**: Vietnamese (`lang="vi"` in HTML tag)

## Key Patterns
- Use HTML5 doctype: `<!doctype html>`
- Include standard meta tags: charset UTF-8, viewport for responsiveness
- Structure: `<html>`, `<head>`, `<body>` with semantic elements like `<h1>`, `<h2>`
- Example from codebase:
  ```html
  <h1>hello</h1>
  <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h2>
  ```

## Development Workflow
- No build process required - edit `index.html` directly
- No testing framework - manual verification in browser
- No package manager or dependencies

## Conventions
- Title format: "Xstudy" (project name)
- Content language: Primarily Vietnamese, with potential for mixed Latin placeholder text
- Keep structure minimal and semantic

## Adding Features
- For new pages: Create additional `.html` files in root directory
- For styling: Add `<style>` tags or link external CSS files
- For interactivity: Add `<script>` tags or external JS files
- Maintain HTML5 standards and semantic markup

## File Organization
- Root level: HTML files
- Future directories: Consider `.github/` for this instructions file, `css/`, `js/`, `assets/` as project grows</content>
<parameter name="filePath">c:\Users\ADMIN\OneDrive\Desktop\THE TuTorX\Xstudy\.github\copilot-instructions.md