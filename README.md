#Introduction

Plugin to display your stickers (logos, images) of your favorite brands in the sidebar of your Octopress site.

Live example at <a href="http://polynec.com">polynec.com</a>


##Installation:

1. Copy `stickers.html` to your `source/_includes/custom/asides` directory.
2. Copy `stickers.rb` to your `plugins` directory.
3. Optionally update your `_config.yml` file to include a `stickers_title` variable defaults is `"I support"`. Example below which is also in the provided _config.yml file:

        # Stickers  
        stickers_title: "I support"

4. Add `stickers.html` to your default_asides variable in the `_config.yml` settings file. Example:

        default_asides: [custom/asides/stickers.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]

5. Create folder in your `source/images/` directory named `stickers`. Following path should exist in your project - `source/images/stickers/`. This is a place where you going to place your stickers. 


## Usage
To add stiker to you Octopress site, simply drop images into this directory `source/images/stickers/`. Size of images meters. Therefore, put properly cropped images. If all images have the same size, than you aside bar look more accurate. There are some prepared stickers for you in this repository. Take a look in folder `stickers`.

## Make sticker as a link
To turn your stickers into a link to some website, rename your image to follow format {website}.{extension} For example, if you want your sticker to be linked to `http://linux.org/` than name your image to `linux.org.jpg` or `linux.org.png`. `http://` will be prepended and image will be wraped in amchor tag where `href` attribute equals to `http://linux.org/`.

_For now plugin is stupid and if it sees more than two dots in the name of the image file it thinks that this is website and a domain. I will build an URL out of it and wrap your sticker into link to not existing website. So, be carefull!_


## Sticker database
If you want to add your sticker to this repository, then consider these simple requirements. Sticker is an image `88 X 88` pixels high and width, `png` format preferable. If you want your sticker to be rendered as a link to a website, then name your image as advised. 



_Please feel free to submit your pull requests. I would appreciate if anybody would finish todos, which you can find in the source code_ 

