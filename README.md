# Cocoa Enhanced

A consistent and responsive [Hugo](http://gohugo.io) [theme](https://github.com/spf13/hugoThemes/) with clean typograhy. This is a fork from the original [Cocoa](https://www.github.com/nishanths/cocoa-hugo-theme) theme, with some improvements.

A [Demo](https://kodewolf.com) is available.

#### Features

* Responsive
* Suited for blogging and personal webpages
* Disqus support
* Built-in support for 404 pages
* Syntax highlighting with hightlightjs
* Logo and title in the header for a clear identity
* Possibility to have sections with a header and a list of articles
* Possibility to have single pages

#### Differences from the original Cocoa

This theme is less minimalist than the original Cocoa, with some new features :

* Displays a logo on the side of the header, and there is a title different from the author name.
* Very modulable with sections and single pages.
* Group articles by month and year
* Fonts are different : stronger and sharper, with a clear identity.
* The font size in articles is higher, the text justified and lines are more spaced.
* On mobile : display the date next to article's titles.

<img src="https://raw.githubusercontent.com/fuegowolf/cocoa-eh-hugo-theme/master/images/screenshot.png" width="800">

# Table of Contents

* [Getting Started](#getting-started)
* [Usage](#usage)
* [Screenshots](#screenshots)
* [Changelog](#changelog)
* [Contributing](#contributing)
* [License](#license)

## Getting Started 

From the root of your Hugo site, clone the theme into `themes/cocoa-eh` by running:

````
git clone https://github.com/fuegowolf/cocoa-eh-hugo-theme.git themes/cocoa-eh
````

Then, generate your site's files by running:

````
hugo -t cocoa-eh
````

## Usage

#### config.toml

Please see the sample [`config.toml`](https://github.com/fuegowolf/cocoa-eh-hugo-theme/blob/master/exampleSite/config.toml) in `exampleSite/`.

Note that if you already use cocoa but have updated to Hugo 0.18, you must lowercase every params of your existing `config.toml`. (like in the sample)

#### Blog posts

The core of this theme is a **Blog**. The last 5 months with articles will be displayed on the [homepage](#homepage), and all articles will be available in the `blog` section.

If you want to add a post, just type :

````
hugo new blog/your-new-post.md
````

#### Homepage

The homepage is meant to display few articles and the `home.md` post, which should be in the root of the folder. If you don't want to display something special on the front page, just don't create this file. If you want to add text before the article list :

````
hugo new home.md
````

#### Sections

You can add **Sections** like Projects or Talks by adding a directory with the name of the section. They will be automatically in the header.

* If you only want a list with articles, just create an article :

````
hugo new projects/my-project.md
````

* If you want to add a header to you section, with some markdown too, create an article with the same name as your section.

````
$ hugo new projects/projects.md
````

#### Single pages

If you want to add a small page like an About one, just create an article in the root. It will be automatically added to the header too.

````
$ hugo new about.md
````

#### Example site

An example site is available in `exampleSite/`.

## Changelog

> v0.5.0

- Add an automatic way to add sections
- Add the possibility to add a header to a section list page
- Add an automatic way to add single pages
- Group blog articles by month and year
- Add a homepage with the possibility of adding a small text and few articles
- Update hightlightjs to v9.9.0
- Few deletions of obsolete lines

> v0.4.0

- Add logo and a title in header instead of only the author name
- Change pages from the navigation
- Delete useless icons from the bottom
- Change fonts and style the text (font size, justify ...)
- Improve mobile design by adding dates, removing grey background and adapt font

And more.

> v0.3.0

- Change color from orange to blue; improve colors elsewhere
- Change `div.section` to `section`
- Rename  `posts` directory to `blog`
- Add ability to specify extra CSS files in `config.toml`
- Removed `WebFontsFile` feature from `config.toml`
- Remove the initials displayed on top right of single post pages
- Update example site

> v0.2.0

* Added Disqus support. To enable Disqus, add `disqusshortname = "XYZ"` to `config.toml`. More details: <http://gohugo.io/extras/comments/>.
* In the posts list, replaced date with bullets at smaller screen widths.

> v0.1.0

* Initial release

## Contributing

Pull requests, bug fixes, and new features are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request on GitHub

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/fuegowolf/cocoa-eh-hugo-theme/blob/master/LICENSE.md) file for more details.
