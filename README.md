# oasis-mbzuai.github.io

Website for **OASIS @ MBZUAI**: Oracles, Assurance, and Safety for Intelligent Systems.

Plain Jekyll with no custom plugins, so GitHub Pages builds it as-is.

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://127.0.0.1:4000
```

## What to edit

| File | Holds |
|---|---|
| `_config.yml` | Lab name, tagline, contact details |
| `_data/nav.yml` | Top navigation |
| `_data/research.yml` | Research themes and their representative papers |
| `_data/people.yml` | Faculty, PhD students, MSc students, alumni |
| `_data/publications.yml` | Selected publications, hand-maintained |
| `assets/css/main.css` | All styling; light and dark palettes at the top |

## Deploying

Create the `oasis-mbzuai` GitHub organisation (or user), push this repository as
`oasis-mbzuai.github.io`, and enable Pages with source *Deploy from a branch →
main → /*. The site is then live at <https://oasis-mbzuai.github.io>.
