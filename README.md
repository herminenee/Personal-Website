# Huiqin (Hermine) Ni — Personal Website

Source code for my personal website: **[hermineni.com](https://hermineni.com)**.

The website brings together my research, publications, engineering and teaching experience, personal essays, campus photography, and biography.

## Files

- `dist/index.html` — page content, sections, navigation, and links.
- `dist/styles.css` — layout, colors, typography, and responsive styles.
- `dist/Huiqin_Ni_CV.pdf` — the current public CV.
- `dist/images/` — my portrait and five original photographs.
- `.openai/hosting.json` — the existing Sites hosting configuration.

## Preview locally

No build step or additional packages are needed. With Python installed, run this command from the repository folder:

```sh
python3 -m http.server 8000 --directory dist
```

On Windows, you can use `py -m http.server 8000 --directory dist`.

Open **http://localhost:8000** in your browser. Press `Ctrl+C` in the terminal to stop the server.

## Edit the website

1. Edit `dist/index.html` to change text, links, or sections.
2. Edit `dist/styles.css` to change the design.
3. Replace images in `dist/images/` or update their filenames in the HTML. Keep image dimensions and alternative text accurate.
4. Replace `dist/Huiqin_Ni_CV.pdf` to update the downloadable CV.
5. Preview the changes locally, then commit them to GitHub.

## Live hosting

The live website is hosted with ChatGPT Sites at **https://hermineni.com**. This repository stores a copy of its current source.

**GitHub commits do not automatically update the live website.** Publish the updated source through Sites to update the custom domain. This upload does not change the domain or hosting provider.

## Writing

My essays are on **[Substack](https://substack.com/@hermineni)**.

This source snapshot includes the Writing & Reflection section and campus photography gallery published on October 5, 2026.
