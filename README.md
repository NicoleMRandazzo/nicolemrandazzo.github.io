# Nicole M. Randazzo
## Major in Biomedical Engineering

## Features



#

This command builds the site locally on port 4000, you can quickly revise design changes thanks to `livereload`.

## Editing

### Posts

* Add, update, or remove a post in the *Posts* collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Collections
To display products, Supply uses a collection called ```product```
You will find a series of product samples in the `_products` collection folder. By design, all the products are on display on the home page, in Supply, that is `ìndex.html`.
You can manually create pages based on this index to [sort your products or any other collection by custom variable](/custom-variables/).

You can also add your products in regular posts, using the Gumroad [overlay](/gumroad-overlay/), [embed](/gumroad-embed/), and [hyperlinks](/gumroad-hyperlink/) method, thanks to an include snippet.

Write something like:

```html
{% raw %}<a href="https://gum.co/supply class="no-underline pv2 grow db"><img class="w-100" src="/images/screenshot.png"></a>

{% include gumroad-overlay.html id="supply" %}{% endraw %}
```

to get a product display like this:

<a href="https://gum.co/supply" class="no-underline pv2 grow db"><img class="w-100" src="/images/supply-overlay.png"></a>

## Copyright / License
*Supply* is designed by [alternatyves](https://alternatyves.com/) and licensed under the [MIT license](https://github.com/YJPL/Supply/blob/master/LICENSE).

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/YJPL/Supply/pulls)

Please use and [contribute to *Supply* ](https://github.com/YJPL/Supply/pulls).

<a href="https://www.buymeacoffee.com/alternatyves/" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/T6T013TB72)

## Who is using this?

- [x] [templates.supply](https://templates.supply)

Are you using Supply? [Let me know!](https://github.com/YJPL/supply/edit/master/README.md)
