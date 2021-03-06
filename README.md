# Poet
[Preview](http://www.lolimay.cn)

An elegant [hexo](https://hexo.io/) theme based on [Poem](https://github.com/codpoe/hexo-theme-Poem/). More info and help can be found in [Codpoe/hexo-theme-poet](https://github.com/codpoe/hexo-theme-poet/).

![](https://images.lolimay.cn/18-10-10/5096232.jpg)

## Installation
1. Download Poet
```
cd <your-blog-root-directory>
git clone https://github.com/lolimay/hexo-theme-poet.git themes/poet
```
2. Switch theme

You can switch hexo theme setting in `_config.yml`.

## Configuration
The default configuration:

```yaml
# If you have any problem about this theme, 
# please let me kown it via email or GitHub issue.
# Thanks!

# primary config
name: Poet ## Your name shown on the header and the drawer
description: Always believe that something wonderful is about to happen ## Introduce yourself
keywords: Blog, Tech
site_name: Poet's Blog ## Your site name shown on the first screen
site_description: Life is a Poet ## Introduce your site
logo: https://i.loli.net/2017/08/31/59a79b0b3ffd8.gif ## The logo on the header and the drawer

# first_screen
## 1.
## On the first screen, you can choose to show the image or the color-gradient.
## 2.
## The links part of first screen: you can add any link, 
## just like <GitHub: [your github url]>.
## note: the key of the link will be the word shown on the screen.
first_screen:
  open: true
  img: https://ws3.sinaimg.cn/large/006tNc79gy1fiyf9ncv1tj31kw11odmz.jpg
  gradient:
    left: '#3a6186'
    right: '#89253e'
  dark: true ## If the style of your image or color is dark, set it to true, else false.
  links:
    Gmail: codpoe.me@gmail.com
    Weibo: https://weibo.com
    GitHub: https://github.com

# header
header:
  menu: ## the menu on the header and the drawer, you can customize it.
    home: /
    category: /categories
    archive: /archives
    about: /about
  links: ## the links on the header and the drawer, you can customize it.
    wechat:
      name: Wechat
      img: https://ws3.sinaimg.cn/large/006tKfTcgy1fj8st9kjdwj308w08wq3v.jpg ## your wechat qrcode
    weibo:
      name: Weibo
      url: https://weibo.com
    github:
      name: GitHub
      url: https://github.com

# copyright
copyright: 
  time: 2017 ## The time of copyright in the footer

# disqus
## You can find more infomation on https://disqus.com/.
disqus:
  open: false ## Toggle whether your site open the disqus
  shortname: ## Your disqus shortname
```