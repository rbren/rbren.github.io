# Repository Instructions

## Website Build Process

The website content is managed through Pug templates in the `views/` directory. The main template is `views/index.pug`. When making changes to the website content:

1. Edit the Pug template files in `views/` directory
2. Do NOT edit `index.html` directly as it is a generated file
3. After making changes to the Pug templates, rebuild the website by running:
   ```bash
   npm install  # if node_modules is not present
   npm run build
   ```
4. Commit both the Pug template changes and the generated `index.html`

This ensures that changes are properly maintained in the source templates and correctly compiled to the final HTML output.