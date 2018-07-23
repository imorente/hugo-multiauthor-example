# Multi-author example Hugo site

Ever wondered how to create an author page in [Hugo](https://gohugo.io/) that displays
the author’s name, their bio, and a list of their articles, like Wordpress does?

Me too! This repository is an example site based on the
[Victor Hugo](https://github.com/netlify/victor-hugo) boilerplate that shows
how it can be done.

You can see the example live at https://hugo-multiauthor-example.netlify.com/

## Usage

### System Requirements

* [git](https://git-scm.com)
* [NodeJS](nodejs.org) 8 or greater
* [yarn](yarnpkg.com)

### Setup

Clone this repository and run:

```bash
yarn
```

This will take some time and will install all packages necessary to run Victor
Hugo and its tasks.

### Development

To run the site locally in development mode:

```bash
yarn start
```

Then visit http://localhost:3000/ *- or a new browser windows popped-up already -*
to preview your new website. BrowserSync will automatically reload the CSS or
refresh the whole page, when stylesheets or content changes.

### Build

To build a static version of the website run:

```bash
yarn build
```

See [package.json](package.json#L7) or the included gulp file for all tasks.

## Deploying to Netlify

- Push your clone to your own GitHub repository.
- [Create a new site on Netlify](https://app.netlify.com/start) and link the repository.

Now Netlify will build and deploy your site whenever you push to git.

You can also click the Deploy to Netlify button below – Netlify will clone
this repo into your account and deploy it for you.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/imorente/hugo-multiauthor-example)


## Enjoy!! 😸
