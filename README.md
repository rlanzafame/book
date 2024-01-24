# Robert's Book

This is a Jupyter Book to collect ideas and share them at [rlanzafame.github.io/book/](https://rlanzafame.github.io/book/)



Created venv (need to revert to lower Python level for plotly case).

```
source .venv/Scripts/activate
```

use `ghp-import` to deploy to gh-pages, [as described here in option 2](https://jupyterbook.org/en/stable/publish/gh-pages.html#option-2-automatically-push-your-build-files-with-ghp-import).

```
ghp-import -n -p -f ./book/_build/html
```