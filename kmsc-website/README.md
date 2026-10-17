# KMSC Website (HTML + CSS only, no JavaScript)

Sample redesign for Karatoa Multimedia School & College, Bogura. Reference: https://kmsc.edu.bd/

## Run in VS Code
1. Open the `kmsc-website` folder in VS Code.
2. Install the "Live Server" extension.
3. Right-click `index.html` -> "Open with Live Server".

## Publish on GitHub Pages
1. Create a GitHub repository and upload everything inside `kmsc-website`.
2. Settings -> Pages -> Source: "Deploy from a branch" -> `main` / root -> Save.
3. Your site appears at `https://USERNAME.github.io/REPOSITORY/`.

## Customize
- Colors, fonts, spacing: `:root` in `assets/css/style.css`.
- Mobile/tablet rules: `assets/css/responsive.css`.
- Text, links, images: follow the HTML comments in each page.
- Replace `assets/images/logo.svg`, `placeholder.svg`, and add `assets/images/hero/hero.jpg`.

## Important notes
- All contact info, names, statistics, notices, and photos are PLACEHOLDERS. Replace them only with verified official content.
- Forms (admission, contact, results, student information) are frontend demonstrations. Set the form `action` to a real backend or form service to receive data.
- Result search needs a connected database or authorized result service. No fake results are shown.
- Search form uses GET; point `action` to a real search endpoint.
- No dynamic filtering, counters, or live updates exist (no JavaScript).
