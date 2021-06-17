## test-sphinx

An example to deploy [sphinx](https://www.sphinx-doc.org/) website to GitHub Pages with [the GitHub Pages Action](https://github.com/peaceiris/actions-gh-pages).

```sh
pipenv sync --dev
pipenv run sphinx-build -b html source build
```
