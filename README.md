# Middleman Quick Starter

![image.png (262.7 kB)](https://img.esa.io/uploads/production/attachments/1/2016/01/13/2/f3e470b2-2e8a-4300-b12f-4d359b708916.png)

## Features

- Middleman (3.4.1)
- [middleman-heroku-static-app](https://github.com/indirect/middleman-heroku-static-app)
- Compass
- jQuery
- Sass (Indented Syntax)
- Haml
- Bootstrap 3 (with customized variables)
- Font-awesome
- Customized buttons, navbar, forms
- CoffeeScript

## TODO

- Typography
- Customize breadcrumb
- Footer
- Middleman v4

## Usage

```
$ git clone http://github.com/taea/middleman-quick-starter.git mysite && cd mysite
$ bundle install && bundle exec middleman init .
$ git add . && git commit -m "brand new site"
$ heroku create && git push heroku master
$ heroku open
```

The only expectation is that `middleman build` will generate your site into `./build`. That's where Rack::TryStatic will look.

You can customize the 404 page that's served if TryStatic can't find a file by editing `source/404.html.erb`.
