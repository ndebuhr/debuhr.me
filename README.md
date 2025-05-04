# Neal DeBuhr Personal Website

> Source code for the [debuhr.me](https://debuhr.me) website

## Background

This website is built with [Hugo](https://gohugo.io/) and deployed to [Google Cloud Storage](https://cloud.google.com/storage).

## Develop

Run a development server
```
hugo serve -D
```

## Build

Get the theme as a submodule
```
git submodule init
git submodule update
```
Build the site
```
hugo --minify
```

## Deploy

The deployment is automated, and triggered on commit pushes to master. The site is built and deployed to Google Cloud Storage via GitHub Actions.

## License

MIT © Neal DeBuhr