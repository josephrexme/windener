# Windener Theme

Windener is a minimalistic theme for bloggers based on the default theme of the same-named [Cactus static site generator](//github.com/koenbok/Cactus) written in Python and [Nick Balestra](//github.com/nickbalestra/kactus)'s Jekyll port. Noteworthy features of this Hugo theme are the integration of a comment-system powered by Disqus, a customizable about page, support for RSS feeds, syntax highlighting for source code and sharing options for blog posts.


![Screenshot](https://cdn.rawgit.com/josephrexme/windener/60018193/images/screenshot.png)


## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/digitalcraftsman/hugo-cactus-theme.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### Configuration

Take a look inside the [`exampleSite`](//github.com/digitalcraftsman/hugo-cactus-theme/tree/dev/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

To use it, copy the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change strings as you like to customize your website.

Make sure to update the `themesDir` property in the config file to point to your site's theme folder otherwise an error will be thrown indicating the themes folder is unable to be found.

## License

This theme is released under the MIT license. For more information read the [license](https://github.com/josephrexme/windener/blob/master/LICENSE.md).

