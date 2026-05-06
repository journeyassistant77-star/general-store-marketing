# General Store Marketing

WordPress block theme that powers [general-store.io](https://www.general-store.io).

## How deploys work

1. Push to `main` on this repo.
2. Git Updater (installed on the live WP site) detects the new commit.
3. WordPress pulls and applies the theme update.

No build step. No SFTP. The repo IS the theme.

## Local development

This is a WordPress theme — there is no standalone preview. To work on it locally you need a WP install (Local, LocalWP, or Docker) with the theme symlinked in `wp-content/themes/`.

## Stack

- WordPress block theme (Full Site Editing)
- `theme.json` for global styles
- `templates/` for page templates
- `parts/` for header/footer
