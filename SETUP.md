# 🚀 Profile README setup

Your GitHub username is **`GuilhermeLeite20`**. To show a profile README, create a **public** GitHub repository with that **exact same name**: `GuilhermeLeite20/GuilhermeLeite20`.

1. Open https://github.com/new and create a public repository named **`GuilhermeLeite20`**. Leave it empty (do **not** generate another README).
2. Unzip this bundle, open a terminal in the extracted folder and run:

   ```bash
   git init
   git add README.md assets .github
   git commit -m "feat(profile): launch animated developer profile"
   git branch -M main
   git remote add origin https://github.com/GuilhermeLeite20/GuilhermeLeite20.git
   git push -u origin main
   ```

3. Open your new repository's **Actions** tab and enable workflows if prompted. Open **Generate contribution snake** and choose **Run workflow**.
4. The snake is published into an auto-generated `output` branch. Once the Action succeeds, the README automatically displays it. It refreshes on a daily schedule.
5. If the publishing step gets a permissions error, open **Settings → Actions → General → Workflow permissions** and allow **Read and write permissions**, when your repository settings permit it. The workflow also declares `contents: write`.

## What's inside

- `README.md`: your entire GitHub profile page, links, project highlights, skill logos, stats, timeline and animated snake embedding.
- `assets/terminal-hero.svg`: custom-made animated terminal-style header with neon gradients, cursor, scan and moving decoration.
- `assets/*.svg`: four custom project banners.
- `.github/workflows/snake.yml`: daily GitHub Actions build for the contribution snake, in light and dark modes.

## Notes

- GitHub strips JavaScript from README pages. The experience uses **animated SVG images, dynamic external cards, HTML/Markdown and links** instead. No fake buttons.
- The dynamic statistics use third-party services. They may be intermittently unavailable or delayed due to rate limits and caching.
- **GitHub top languages** mean languages detected across GitHub repositories, not your skill ranking.
- Do not delete the generated `output` branch if you want the snake to keep loading.
- You may replace `https://github.com/GuilhermeLeite20.png` with a custom portrait hosted in your own `assets/` directory.
- Your Guitarmony repository is **private**, so no private-source link is included.
- For future customization change the accent colors in the SVGs and badge URL parameters.
