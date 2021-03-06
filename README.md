# SSDQ wiki
[![Build Status](https://travis-ci.com/ssdq/wiki.svg?branch=master)](https://travis-ci.com/ssdq/wiki)

The wiki for Serious Sam speedruns.

## Contributing
At its most basic, you can simply edit files through GitHub's online editor. Make sure to check the preview before submitting a pull request.

For larger changes you may want to build the site locally first. Install [mkdocs](https://github.com/mkdocs) and the [windmill](https://github.com/gristlabs/mkdocs-windmill) theme.
```
pip install mkdocs mkdocs-windmill
```

You can then run `mkdocs serve` to launch a local, auto-updating, server.

Note that if you're using Python 3.8 you will run into [mkdocs issue #1885](https://github.com/mkdocs/mkdocs/issues/1885). To fix it manually replace your `serve.py` with the updated version in the repo.
