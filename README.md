# Academic website of Thi-Minh-Thu Vu

A lightweight, responsive academic website built with Jekyll for GitHub Pages. Personal metadata is centralized in `_data/profile.yml`; publications and news are maintained as structured YAML data.

## Local development

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`. To test the production build without serving it:

```bash
bundle exec jekyll build
```

## Deployment with GitHub Pages

1. Create a public repository named `<username>.github.io` (for this account, `ThiMinhThuVu.github.io`).
2. Push this repository to the `main` branch.
3. In **Settings → Pages**, set **Source** to **GitHub Actions**.
4. The included workflow builds the site for pushes to `main` and deploys it to `https://<username>.github.io/`. Pull requests run the build without deploying.

The configuration uses an empty `baseurl`, which is correct for a user site. If this is deployed as a project site instead, set `baseurl: "/repository-name"` and `url: "https://<username>.github.io"` in `_config.yml`.

## Personalization

- **Name, title, affiliations, location, email, and profile links:** edit `_data/profile.yml`.
- **Profile photo:** the current image is `images/avatar.jpg`. Replace that file to update the portrait, or change `profile_image` in `_data/profile.yml` to use a different path.
- **Navigation:** edit `_data/navigation.yml`.
- **Publications:** edit `_data/publications.yml`. Leave unknown link fields empty; buttons appear only for non-empty URLs.
- **News:** edit `_data/news.yml`.
- **Teaching:** edit `_data/teaching.yml`.
- **Research and projects:** edit `_pages/research.md` and `_pages/projects.md`.
- **Home page:** edit `index.md`.
- **Colors and layout:** edit `assets/css/main.scss`.
- **Favicon:** add an icon under `images/` and uncomment the favicon line in `_layouts/default.html`.

## Repository structure

```text
.
├── _config.yml
├── _data/                 # profile, navigation, publications, teaching, news
├── _includes/             # reusable header, sidebar, publication list
├── _layouts/default.html
├── _pages/                # research, publications, projects
├── assets/css/main.scss
├── images/                # avatar fallback and future profile photo
├── index.md
├── 404.html
└── Gemfile
```

## Content integrity

Only confirmed publications are listed. Do not add publication links, affiliations, roles, dates, results, rankings, or awards unless they are verified.
