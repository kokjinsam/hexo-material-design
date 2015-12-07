# Material Design Theme for Hexo

## Installation

### Install

``` bash
$ git clone https://github.com/sammkj/hexo-material-design.git themes/material-design
```

### Enable Material Design Theme

Modify `theme` setting in `_config.yml` to `material-design`.

### Update

``` bash
cd themes/material-design
git pull
```

## Configurations

``` yml
# Material Design Configuration

# Header
isFull: false
background:  # background image for header
logo:  # logo for header
navigations: 
  Home: /
  About: /about
  

# Main
groupByYear: true		# Article list grouped by year
thumbnail: true		#thumbnail for cover
makeCards: true		#set style for articles. List articles in card-form or list-form
randomCardSize: true  #randomly generate small and large cards
randomCardColor: true  #randomly generate color for cards

# Sidebar
social_media:
  twitter:
  facebook:
  google-plus:
  github:
  weibo:
  rss:
widgets:
- recent_posts
- category
- archive
- tag
- tagcloud
- links
```

