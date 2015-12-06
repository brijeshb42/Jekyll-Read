# Jekyll-Read Theme

A jekyll theme built on top of default jekyll theme and inspired by [Read WordPress theme](http://themes.pixelwars.org/read-wp/).

## Features:

* Responsive Layout
* Sitemap
* Atom feed
* Mailchimp Newsletter subscription
* Disqus Commenting
* Google Analytics
* Scheme.org Formatting
* Featured image for posts
* Minimal configuration

## Installing

* Download `zip` from the latest [release](https://github.com/brijeshb42/Jekyll-Read/releases).
* Change values in `_config.yml` as required. This file is commented wherever required.
* Change the value in the `CNAME` file if you have your own domain.
* Change the value of the `url` variable to your blog's URL (eg: `http://githubusername.github.io`).
* Uncomment and add a value to `disqus` variable if you want to have disqus commenting enabled.
* Uncomment and add values to `ga_id` and `ga_domain` to add Google Analytics.
* Add a Mailchimp Newsletter form submission URL to `mailchimp` to add a newsletter subscription form.
* There's a file `projects.yml` in `_data` directory by default. You can add `title` and `url` values to it to add a **Project** submenu in the top navigation. Delete this file to remove the submenu.
* Now install `jekyll` and `jekyll-paginate` gems to test the site locally.
* Run `jekyll serve -w` in the theme's directory to run the server and goto [http://127.0.0.1:4000](http://127.0.0.1:4000) to check the changes.
* If everything works well, push your changes to github.
