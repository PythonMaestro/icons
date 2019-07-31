<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/4.3/assets/brand/bootstrap-solid.svg" alt="Bootstrap logo" width="72" height="72">
  </a>
</p>

<h3 align="center">Bootstrap Icons</h3>

<p align="center">
  Official open source icon library for Bootstrap.
  <br>
  <a href="https://icons.getbootstrap.com/"><strong>Explore Bootstrap Icons »</strong></a>
  <br>
  <br>
  <a href="https://getbootstrap.com/docs/4.3/">Bootstrap</a>
  ·
  <a href="https://themes.getbootstrap.com/">Themes</a>
  ·
  <a href="https://blog.getbootstrap.com/">Blog</a>
</p>

## Install

```
npm i bootstrap-icons --save
```

## Development

Clone the repo, install dependencies, and start the Jekyll server locally.

```
git clone https://github.com/twbs/icons/
cd icons
gem install jekyll
npm i
jekyll serve
```

Then open http://localhost:4000 in your browser.

## Publishing

Docs are published via an npm script that builds the Jekyll site, creates a temporary Git repo, and force pushes that to our `gh-pages` branch. This circumvents issues with GitHub Pages not accepting third party plugins and symlinked directories.

```
npm run publish
```

## Todos

Help wanted if you have ideas how to tackle these!

- [ ] Update readme with install and usage guidelines
- [ ] Add npm script for reprocessing icons (HTML, attribute order, generate class names)
- [ ] Add copy to clipboard for SVG code in the docs
- [ ] Alternate distribution and usage methods (e.g., JS library, React components, etc)
- [ ] Publish to GitHub Package Registry
- [ ] Add GitHub Actions support for processing new icons from PRs?
