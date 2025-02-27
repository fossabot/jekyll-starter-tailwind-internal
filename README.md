# Jekyll Starter Tailwind (Internal CSS)
A starter kit for using [Tailwind](https://tailwindcss.com) with [Jekyll](https://jekyllrb.com/) that includes:
* A barebones Jekyll starter theme
* A Gulpfile that does the following:

    * Compiles Tailwind
    * Strips out unused CSS using [Purgecss](http://www.purgecss.com/)
    * Runs [Autoprefixer](https://github.com/postcss/autoprefixer)
    * Minifies your CSS
    * Places CSS directly in `<head>`
    * Compiles Jekyll
    * Runs [Browsersync](https://www.browsersync.io/) for local development

Don't want to use internal CSS? Check out the [_regular_ version](https://github.com/taylorbryant/jekyll-starter-tailwind) of this starter kit.

## What is Tailwind?
>"Tailwind is a utility-first CSS framework for rapidly building custom user interfaces."
–[Tailwind](https://tailwindcss.com)

## What is Jekyll?
>"Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. Think of it like a file-based CMS, without all the complexity. Jekyll takes your content, renders Markdown and Liquid templates, and spits out a complete, static website ready to be served by Apache, Nginx or another web server. Jekyll is the engine behind GitHub Pages, which you can use to host sites right from your GitHub repositories."
–[Jekyll](https://jekyllrb.com/)

## Requirements
* [Bundler](http://bundler.io/)
* [Jekyll](https://jekyllrb.com/)
* [Node.js](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* [Ruby](https://www.ruby-lang.org/en/)

## Get started
* `bundle install` to install Ruby gems
* `npm ci` to install npm packages listed in `package-lock.json`
* `npm run start` to compile the site with development settings and run BrowserSync

## Build your site
* `npm run build` to compile the site for production

## Deploy
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/taylorbryant/jekyll-starter-tailwind-internal)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind-internal.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind-internal?ref=badge_shield)

Note: By default, Netlify uses `jekyll build` as the build command. Make sure to change this to `npm run build`.

## License
[MIT](https://github.com/taylorbryant/jekyll-starter-tailwind/blob/master/LICENSE.md)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind-internal.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind-internal?ref=badge_large)

## How you can help
Enjoying Jekyll Starter Tailwind (Internal CSS) and want to help? You can:
* [Create an issue](https://github.com/taylorbryant/jekyll-starter-tailwind-internal/issues/new) with some constructive criticism
* [Submit a pull request](https://github.com/taylorbryant/jekyll-starter-tailwind-internal/compare) with some improvements to the project