## test-sphinx

An example to deploy [sphinx](https://www.sphinx-doc.org/) website to GitHub Pages with [the GitHub Pages Action](https://github.com/peaceiris/actions-gh-pages).
### Clone and Build

```sh
git clone https://github.com/peaceiris/test-sphinx.git
cd test-sphinx
pipenv sync --dev
pipenv run make html
```

The project was generated as follows.

```
pipenv install --dev sphinx
pipenv run sphinx-quickstart
```
