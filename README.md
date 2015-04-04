# Yet Another Modernist Hexo Theme

> Theme for [Hexo]. This theme based on [modernist theme hexo] which based on [modernist theme] for GitHub Pages.

[Demo the Theme]

## Install

```
git clone git://github.com/drwx/yamht.git themes/yamht
```

**Modernist requires Hexo 2.4 and above.**

## Enable
Modify `theme` setting in `_config.yml` to `yamht`.

## Update

```
cd themes/yamht
git pull
```

## Configuration

``` yaml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
archive_date_format: MMM DD
fancybox: true

# Comment Plugin
duoshuo_shortname:

# Miscellaneous
google_analytics:
favicon: /favicon.ico
```

- **menu** - Navigation menu
- **rss** - RSS link
- **archive_date_format** - Date format in archives page.
- **fancybox** - Enable [Fancybox]
- **duoshuo_shortname** - [Duoshuo] ID
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

[Hexo]: http://zespia.tw/hexo/
[modernist theme]: https://github.com/orderedlist/modernist
[modernist theme hexo]: https://github.com/heroicyang/hexo-theme-modernist
[Demo the Theme]: http://riveris.me/
[Duoshuo]: http://duoshuo.com
[Fancybox]: http://fancyapps.com/fancybox/
