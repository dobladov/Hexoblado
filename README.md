# Hexoblado
A dark theme for the [Hexo](https://hexo.io/) blog framework.

## Screenshots

![Home](https://my.mixtape.moe/qpvtsj.png)

![Archive](https://my.mixtape.moe/gpcwws.png)

![Social](https://my.mixtape.moe/agtyvw.png)

![Phone](https://my.mixtape.moe/gzwmfz.png)

## Installation
Download the theme, and copy the Hexoblado folder inside your theme's folder.

## Features

+ Rss
+ Custom Menu
+ Social Icons
+ Social Share
+ Configurable Logo and Favicon
+ Responsive design

## Configuration

### Select Theme
Select the theme in the `_config.yml` file

```
theme: hexoblado
```

### RSS

On your blog folder

```
npm install hexo-generator-feed
```

Add this to your blog `_config.yml`

feed:
  type: atom
  path: atom.xml
  limit: 20
  hub:
  
### Favicon

Change the value of `favicon:`

```
favicon: "img/favicon.png"
```

  
### Menu Items

Add new items into the theme `_config.yml`

```
menu:
	Home: index.html
	About: about/
	Projects: projects/
	"<i class='fa fa-archive'></i>": archives/
	"<i class='fa fa-rss'></i>": atom.xml
```

### Social Icons

Add new items into the theme `_config.yml` withe the name of the ![Font Awesome](https://fortawesome.github.io/Font-Awesome/) icon name.

```
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

## ToDo

+ Open Data
+ Google Analytics
+ Refactor ejs Templates
