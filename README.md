# Hexoblado
A dark theme for the [Hexo](https://hexo.io/) blog framework.

## Screenshots

![Screen Shot 2019-12-25 at 19 59 03-fullpage](https://user-images.githubusercontent.com/1938043/71450057-6ef03f80-275a-11ea-84fc-fa1ea860859d.png)
![Screen Shot 2019-12-25 at 21 06 05-fullpage](https://user-images.githubusercontent.com/1938043/71450056-6dbf1280-275a-11ea-957c-eed9d85b598e.png)

## Installation
Download the theme, and copy the Hexoblado folder inside your theme's folder.

```
cd <blog-folder>
git clone https://github.com/dobladov/Hexoblado.git themes/hexoblado
```

Add the theme in the `_config.yml` file.

```
theme: hexoblado
```

## Features

+ Rss
+ Custom Menu
+ Social Icons
+ Social Share
+ Configurable Logo and Favicon
+ Responsive design
+ Multiple lang
	+ Es
	+ En

## Configuration

### RSS

```
cd <blog-folder>
npm install hexo-generator-feed
```

Add this to your blog `_config.yml`

``` yml
feed:
  type: atom
  path: atom.xml
  limit: 20
  hub:
 ```
  
### Favicon

Change the value of `favicon:`

```
favicon: "img/favicon.png"
```

  
### Menu Items

Add new items into the theme `_config.yml`

``` yml
menu:
  Home: index.html
  About: about/
  Projects: projects/
  "<i class='fa fa-archive'></i>": archives/
  "<i class='fa fa-rss'></i>": atom.xml
```

### Social Icons

Add new items into the theme `_config.yml` with the name of the [Font Awesome](https://fortawesome.github.io/Font-Awesome/icons/) icon name.

``` yml
social:
  twitter: "https://twitter.com/dobladov"
  github: "https://github.com/dobladov"
  pinterest-p:
  facebook:
  google-plus:
  youtube:
  instagram:
  linkedin:
  tumblr:
```

### Footer text

Change the value of `footerText:` on  the theme `_config.yml`

### Google Analytics

Add your google Analytics to `googleAnalytics:` in `_config.yml`

## ToDo

+ Open Data
+ Fancybox Gallery
