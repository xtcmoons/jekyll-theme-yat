bundle exec jekyll serve
jekyll build


# jekyll-theme-yat
[![Github Pages](https://github.com/jeffreytse/jekyll-theme-yat/workflows/Github%20Pages/badge.svg)](https://jeffreytse.github.io/jekyll-theme-yat)
[![Gem Version](https://badge.fury.io/rb/jekyll-theme-yat.svg)](http://badge.fury.io/rb/jekyll-theme-yat)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![Donate (Liberapay)](http://img.shields.io/liberapay/goal/jeffreytse.svg?logo=liberapay)](https://liberapay.com/jeffreytse)
[![Donate (Patreon)](https://img.shields.io/badge/support-patreon-F96854.svg?style=flat-square)](https://patreon.com/jeffreytse)
<a href="https://ko-fi.com/jeffreytse">
  <img height="20" src="https://www.ko-fi.com/img/githubbutton_sm.svg"
    alt="Donate (Ko-fi)" />
</a>

Hey, nice to meet you, you found this Jekyll theme. Here the yet another theme is a modern theme, and it's quiet clear, clean and neat for writers and posts.


<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/91842897-6a840b00-ec87-11ea-95ca-52abcc1ac063.png" alt="demo-screenshot" width="780px"/>

</p>

<h3 align="center">Night Mode</h3>

<p align="center">

  <img src="https://user-images.githubusercontent.com/9413601/94983351-760f6e00-0574-11eb-9494-5303ad6228dc.gif" alt="demo-screenshot" width="780px"/>

</p>

## Features

- Support beautiful __Night Mode__.
- Full layouts `home`, `post`, `tags`, `archive` and `about`.
- Uses font awesome 5 for icons.
- Beautiful Syntax Highlight using [hilight.js][hilight-js].
- RSS support using [Jekyll Feed][jekyll-feed] gem.
- Optimized for search engines using [Jekyll Seo Tag][jekyll-seo-tag] gem.
- Sitemap support using [Jekyll Sitemap][jekyll-sitemap] gem.
- Complex and flexible table support using [Jekyll Spaceship][jekyll-spaceship] gem.
- MathJAX and LaTeX optional support using [Jekyll Spaceship][jekyll-spaceship] gem.
- Media (Youtube, Spotify, etc.) support using [Jekyll Spaceship][jekyll-spaceship] gem.
- Diagram (PlantUML, Mermaid) support using [Jekyll Spaceship][jekyll-spaceship] gem.
- Google Translation support.
- New post tag support.

Also, visit the [Live Demo][yat-live-demo] site for the theme.

## Installation

There are three ways to install:

- As a [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes).
- As a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) (GitHub Pages compatible).
- Forking/directly copying all of the theme files into your project.

### Gem-based Theme Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-yat"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-yat
```

And then execute:

```bash
$ bundle
```

Or install it yourself as:

```bash
$ gem install jekyll-theme-yat
```

### Remote Theme Method with GitHub Pages

Remote themes are similar to Gem-based themes, but do not require `Gemfile` changes or whitelisting making them ideal for sites hosted with GitHub Pages.

To install:

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "github-pages", group: :jekyll_plugins
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
# theme: owner/name --> Don't forget to remove/comment the gem-based theme option
remote_theme: "jeffreytse/jekyll-theme-yat"
```

And then execute:

```bash
$ bundle
```

## GitHub Pages without limitation

GitHub Pages runs in `safe` mode and only allows [a set of whitelisted plugins/themes](https://pages.github.com/versions/). __In other words, the third-party gems will not work normally__.

To use the third-party gem in GitHub Pages without limitation:

Here is a GitHub Action named [jekyll-deploy-action](https://github.com/jeffreytse/jekyll-deploy-action) for Jekyll site deployment conveniently. 👍


## Usage

Add or update your available layouts, includes, sass and/or assets.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_data`, `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-yat.gemspec` accordingly.

## Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.

You can start by [opening an issue](https://github.com/jeffreytse/jekyll-theme-yat/issues/new) describing the problem that you're looking to resolve and we'll go from there.

## License

This theme is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php) © JeffreyTse.

<!-- External links -->
[jekyll]: https://jekyllrb.com/
[yat-git-repo]: https://github.com/jeffreytse/jekyll-theme-yat/
[yat-live-demo]: https://jeffreytse.github.io/jekyll-theme-yat/
[jekyll-spaceship]: https://github.com/jeffreytse/jekyll-spaceship
[jekyll-seo-tag]: https://github.com/jekyll/jekyll-seo-tag
[jekyll-sitemap]: https://github.com/jekyll/jekyll-sitemap
[jekyll-feed]: https://github.com/jekyll/jekyll-feed
[hilight-js]: https://github.com/highlightjs/highlight.js
