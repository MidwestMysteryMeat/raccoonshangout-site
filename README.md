# raccoonshangout.com

Website for A Raccoon's Hangout, a vanilla PvE Project Zomboid server (`play.raccoonshangout.com:16261`).

Built with [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme. Every push to `main` is built and published to GitHub Pages by `.github/workflows/deploy.yml`.

## Edit

- Pages are Markdown files in `content/`.
- Header menu: `config/_default/menus.en.toml`.
- Colors and layout: `config/_default/params.toml`.

## Preview locally

```
git clone --recurse-submodules https://github.com/MidwestMysteryMeat/raccoonshangout-site
cd raccoonshangout-site
hugo server
```
