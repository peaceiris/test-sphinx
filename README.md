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

### Custom Domain

`CNAME` file will be generated by the [html_baseurl](https://github.com/peaceiris/test-sphinx/blob/48a9a3bf9888f61ace5adc369e3e87a860a06ef2/source/conf.py#L25).

cf. [sphinx.ext.githubpages – Publish HTML docs in GitHub Pages — Sphinx documentation](https://www.sphinx-doc.org/en/master/usage/extensions/githubpages.html#module-sphinx.ext.githubpages)
