# heroku-buildpack-fonts-segoe-ui

This buildpack makes it easy to install Segoe UI font on Heroku [stacks](https://devcenter.heroku.com/articles/stack).

## Install

```bash
# Add the buildpack
heroku buildpacks:add --index 1 https://github.com/DenverCoder1/heroku-buildpack-fonts-segoe-ui

#Deploy
git push heroku master
```

## Building

```bash
tar -czvf fonts.tar.gz ./fonts/
```
