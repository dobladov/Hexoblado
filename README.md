# Hexoblado
A dark theme for the [Hexo](https://hexo.io/) blog framework.

## Screenshots

![image](https://user-images.githubusercontent.com/1938043/71450368-e88b2c00-2760-11ea-811b-3d5bad168dda.png)
![Screen Shot 2019-12-25 at 21 49 47-fullpage](https://user-images.githubusercontent.com/1938043/71450348-a8c44480-2760-11ea-8630-ec7562b58120.png)

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
