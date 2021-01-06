# Glocal Box

Glocal Box is a virtual donation box to live solidarity in times of global & local crisis.
Use glocal box to donate for your local company while shopping online?


### Getting started
This site is build with **Bulma (CSS Framework)** and **Jekyll (static HTML generator based on ruby)**. To optimize Dev Environment, prettier and ESlint is used. Simply get started: clone + run command:
```sh
npm install
```

**Build the site and make it available on a local server
```
bundle exec jekyll serve --livereload
```

### Using Netlify CMS

Netlify CMS is compatible with any static site buide like Hugo or Jekyll etc.
Install it's package by using: `npm install netlify-cms-app --save`

Afterwards do some configs:
1. add a `admin` folder to the root of the prpject
2. add a `index.html` to basically wire everything up the the Netlify CMS script
3. add a custom `config.yml`

Within the `config.yml` you can specify which sites of your website should be considered by the CMS `index.html`.
In this case, I created a `blog.html` and severeal authors within the `_authors` folder to play araound with the CMS.

