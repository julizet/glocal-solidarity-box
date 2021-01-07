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

### Config Netlify CMS

Netlify CMS is compatible with any static site buide like Hugo or Jekyll etc.
Install it's package by using: `npm install netlify-cms-app --save`

Afterwards do some configs:
1. add a `admin` folder to the root of the prpject
2. add a `index.html` to basically wire everything up the the Netlify CMS script
3. add a custom `config.yml`

Within the `config.yml` you can specify which sites of your website should be considered by the CMS `index.html`.
In this case, I created a `blog.html` and severeal authors within the `_authors` folder to play araound with the CMS.

### Using Netlify CMS

**Important:** when using `/admin`-login in development, the Netlify CMS will automaticall redirect to the deployed webpage. Means that every blog article, author or media which will be added or removed within *development mode* will also be added/deleted on the deployed version.

Follow these steps to add another blog article:
1. login to Netlify CMS by using this URL: [https://glocal-box.netlify.app/admin](https://glocal-box.netlify.app/admin)
2. Create an account with email and password or by using your GitHub account
3. create new blog article & click the `publish button`

By clicking the publish button a new netlify deploy is triggered. So please be patient and whait until deploy is ready.
Finish