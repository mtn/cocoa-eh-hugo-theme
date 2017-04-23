# Cocoa Enhanced

[![MIT License](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000?style=plastic)](https://github.com/fuegowolf/cocoa-eh-hugo-theme/blob/master/LICENSE)

**Cocoa Enhanced** is a clean, fast and responsive [Hugo](http://gohugo.io) [theme](https://github.com/spf13/hugoThemes/) with cool typography. The main goal of this theme is to be simple and fast but highly customizable.

You can use this theme either for your blog or your personal website. A demo is available [here](https://kodewolf.com).

> This is a fork from the original [Cocoa](https://www.github.com/nishanths/cocoa-hugo-theme) theme, with some improvements.

[![screenshot](https://raw.githubusercontent.com/fuegowolf/cocoa-eh-hugo-theme/master/images/screenshot.png)](https://raw.githubusercontent.com/fuegowolf/cocoa-eh-hugo-theme/master/images/screenshot.png)

## Table of Contents

* [Features](#features)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [License](#license)

## Features

Simple but complete, here are the main features of this theme :

* Possibility to have sections with a header and a list of articles.
* Possibility to have single pages.
* Homepage with latest and best posts.
* Syntax highlighting with `hightlightjs`.
* Progressive images.
* Twitter cards support.
* Disqus support.

#### Typography

The **typography** is what makes Cocoa-EH look cool, here are the fonts used :

* *Nexa Bold* for the blog name, a strong and opinionated font
* *Raleway* for the titles, light but clearly visible
* *Merriweather* for the text, an awesome sans serif font to read without difficulties
* *Ubuntu Mono* for the code

#### Blazing fast

Everything is made here to make the theme **really fast** to load : inline CSS, deferred Javascript, fonts loaded in an asynchronous way with replacement fonts when they're not loaded, etc. ... Even with a GPRS connection, your blog is readable.

> With gzip enabled, this theme takes less than **400**ms to load entirely, and the content is readable at only **50**ms. Also scores 99/100 on Pagespeed.

### Differences from the original Cocoa

This theme is less minimalist than the original Cocoa, with some new features :

* Displays a logo on the side of the header, and there is a title different from the author name.
* Very modular with sections and single pages.
* Group articles by month and year.
* Progressive images.
* Fonts are different : stronger and sharper, with a clear identity.
* The font size in articles is higher, the text justified and lines are more spaced.
* More features.

## Getting Started 

From the root of your Hugo site, clone the theme into `themes/cocoa-eh` by running:

````
git clone https://github.com/fuegowolf/cocoa-eh-hugo-theme.git themes/cocoa-eh
````

Then, generate your site's files by running:

````
hugo -t cocoa-eh
````

If you want a simple blog you can just use the `exampleSite`, however if you desire a more complex website you can build it with the [wiki](https://github.com/fuegowolf/cocoa-eh-hugo-theme/wiki).

## Contributing

Pull requests, bug fixes, and new features are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request on GitHub

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/fuegowolf/cocoa-eh-hugo-theme/blob/master/LICENSE.md) file for more details.
