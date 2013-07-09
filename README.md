#Introduction

Plugin to display your stickers (logos, images) of your favorite brands in the sidebar of your Octopress site.

Live example at <a href="TODO">TODO</a>


##Installation:

1. Copy `stickers.html` to your `source/_includes/custom/asides` directory.
2. Copy `stickers.rb` to your `plugins` directory.
3. Optionally update your `_config.yml` file to include a `stickers_title` variable defaults is `"I support"`. Example below which is also in the provided _config.yml file:

        # Stickers  
        stickers_title: "I support"

4. Add `stickers.html` to your default_asides variable in the `_config.yml` settings file. Example:

        default_asides: [custom/asides/stickers.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]

5. Create folder in your `source/images/` directory named `stickers`. Folowing path should exist in your project - `source/images/stickers/`. This is a place where you going to place your stickers. 


## Usage
To add stiker to you Octopress site, simply drop images in directory `source/images/stickers/`. Size of images metters. Therefore, put properly croped images.


_Please feel free to submit you commits. I would appreciate if anybody would finish todos, which you can find in the source code_ 