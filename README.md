# Neal DeBuhr Personal Website

> Source code for the [debuhr.me](https://debuhr.me) website

## Background

This website is built with [Hugo](https://gohugo.io/) and deployed to [Cloudflare Workers](https://workers.cloudflare.com/).

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

The deployment is automated, and triggered on commit pushes to master.  [Cloudflare Workers via GitHub Actions](.github/workflows/cloudflare-workers-dev.yml) is the associated GitHub Actions workflow.

## License

MIT © Neal DeBuhr