<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oriw-app/oriw-design/main/logo/oriw-wordmark-white.svg">
    <img src="https://raw.githubusercontent.com/oriw-app/oriw-design/main/logo/oriw-wordmark.svg" alt="Oriw" width="240">
  </picture>
</p>

# oriw.app

Website for Oriw, the fast, private, open-source whiteboard. Served on GitHub Pages at [oriw-app.github.io/oriw.app](https://oriw-app.github.io/oriw.app/); it moves to oriw.app once the domain is bought.

## Edit the site

The whole site is one file, `index.html`. Links to GitHub, releases and the security and contributing pages are set in one place: the `LINKS` list near the bottom of the file.

## Deploy

GitHub Pages serves the `main` branch root; `.nojekyll` serves files as-is. When oriw.app is bought, add a `CNAME` file containing `oriw.app` and point the domain's DNS at GitHub Pages (issue #2).

Icons (`favicon.svg`, `favicon.ico`, `apple-touch-icon.png`) and the link preview image (`og.png`) come from the logo kit in [oriw-design](https://github.com/oriw-app/oriw-design/tree/main/logo).

## License

Apache-2.0

## Part of Oriw

| Repo | What |
| --- | --- |
| [oriw](https://github.com/oriw-app/oriw) | The app (source opens with the 0.1.9 preview) |
| [oriw-design](https://github.com/oriw-app/oriw-design) | Design system and logo |
| [oriw.app](https://github.com/oriw-app/oriw.app) | Website |
| [oriw-templates](https://github.com/oriw-app/oriw-templates) | Community templates |

- **Roadmap:** [Oriw Roadmap](https://github.com/orgs/oriw-app/projects): what's planned for each release, across all repos.
- **Contribute:** read the [contributing guide](https://github.com/oriw-app/.github/blob/main/CONTRIBUTING.md). Issues use the labels `feature`, `bug`, `docs`, `chore`, `area: …` and `priority: …`.
- **Security:** report problems privately as described in the [security policy](https://github.com/oriw-app/.github/blob/main/SECURITY.md).
