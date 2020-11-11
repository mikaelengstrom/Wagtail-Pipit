# Changelog

## 8.0.1 (2020.11.11)

- Fix issue where syncscripts where nog working in docker mode (Martin Sandström)
- Add guide on how to use static site generation (Martin Sandström)
- Fix issue where `api/wagtail.js` `getAllPages` did not work (Martin Sandström)


## 8.0.0 (2020.11.08)

- Replace Create React App with Next.js (Martin Sandström, Mikael Engström)
- Replace Hypernova with Next.js (Martin Sandström, Mikael Engström)
- Update deploy scripts to support Next.js (Mikael Engström)
- Add new "backend-developer-guide" (Martin Sandström)
- Improve docker performance and refactor docker-compose structure (Mikael Engström)
- Add npm shortcut for creating new containers (Martin Lindvall)
- Drop external file logging (Martin Sandström)
- Replace class components with functional components (morrme)
- Add doumentation for running python locally (Martin Sandström)
- Add support for locally running python in syncscripts (Martin Sandström)
- Fix: Improve mypy coverage (Andreas Bernacca, Martin Sandström)
- Fix: Rebuild customuser migrations (Martin Sandström)
- Fix: Change so `serve()` always return json data
- Fix: Drop `django-sslserver` in favor of Nginx ssl handling
- Fix: Use /wt/ namespace for wagtail app
- Fix: Add wagtail background job to provisioning (Martin Lindvall)
- Fix: Update deployment docs (Martin Lindvall)
- Fix: Change default deploy user to "deploy" (Mikael Engström)
- Fix: Override environment variables if they exist (Martin Lindvall)
- Fix: Update Wagtail to 2.11.1
- Fix: Update Django to 3.1.2
- Fix: Update DRF
- Fix: Replace Boto with Boto3 (Martin Lindvall)
- Fix: Add optional slack notification on release (Martin Sandström)
- Fix: Add default cache for renditions (Martin Sandström)
- Fix: Rename web.env to python.env


## 7.0.0 (XXXX.XX.XX) - SKIPPED

- Replace React-Sass-Starterkit with Create React App (Martin Sandström)
- Replace Hastur SSR service with Hypernova (Martin Sandström)
- Add Storybook for component preview (Martin Sandström)
- Add meta preview with wagtail-meta-preview (Andreas Bernacca, Martin Sandström)
- Add provisioning for SSR service (Andreas Bernacca)
- Remove class containers in favor of function components in scaffold CLI (Andreas Bernacca)
- Change postgres to new image (mdillon is deprecated), and use postgres 12 with postgis 2.5 (Andreas Bernacca)
- Fix: Add ability to send slack notifications from CircleCI (Andreas Bernacca)
- Fix: Adopt pattern where --reuse-db is default and --create-db overrides behaviour (Martin Sandström)
- Fix: Retain pip cache in requirements cache on CI (Martin Sandström)
- Fix: Add missing field to image serializer (Andreas Bernacca)
- Fix: Adopt policy for limiting test collection (Martin Sandström)
- Fix: Always show the 10 slowest tests in CI (Martin Sandström)
- Fix: Fix broken canonical value in template (Martin Sandström)
- Fix: Drop deprecated SiteMiddleware. Fixes #189 (Martin Sandström)
- Fix: Use the new pip resolver when installing packages (Martin Sandström)
- Fix: Ignore tests marked as slow in dev (Martin Sandström)
- Fix: Upgrade Wagtail to 2.10
- Fix: Upgrade Python to 3.8
- Fix: Upgrade Sentry SDK