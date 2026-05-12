# Security

A curated list of security tools and CTF wargame challenges.

**Site:** <https://6fd58c.github.io/Security/>

## Adding a tool

Edit [`_data/tools.yml`](_data/tools.yml) and add an entry:

```yaml
- name: Shodan
  url: https://www.shodan.io/
  categories: [Search Engine, Server]
```

`categories` is a list, so a tool can appear in more than one section without duplication.

## Adding a category

Edit [`_data/categories.yml`](_data/categories.yml). The order in that file controls the order categories appear on the site. A category with no matching tools is skipped automatically.

## Adding a challenge

Edit [`_data/challenges.yml`](_data/challenges.yml).

## Site

The page is built by Jekyll on GitHub Pages. The layout lives in [`_layouts/default.html`](_layouts/default.html); the data-driven page is [`index.html`](index.html).
