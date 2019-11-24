# http://talentupafrica.com/ Website Project Setup

## Getting Started:

To use this you'll need the following installed:

- [NodeJS](http://nodejs.org) -

This is a gulp based SASS project. This site's CSS is generated using Sass:
including:

- JS (lint, minify, and concat)
- SASS (compile)
- CSS (minify)
- Autoprefixer (Vendor Prefixes)
- Images (image compression)
- BrowserSync (css injection)

## Setup

1. `$ git clone git@github.com:codeo-za/yumbi-corporate-site.git` or download it into a directory of your choice.
2. Then run `$ npm install` inside that directory. (This should install all the plugins needed)

## Usage

1. To start the browser syncing and file watching, just run `$ gulp` in the project directory.
2. Folders and file paths can be changed in gulpfile.js

## SASS file structure

```
├── assets          #Folder with files after compiling
├── src             #Folder with sources
├── LICENSE
├── README.md
├── gulpfile.js     #File with gulp tasks
├── index.html      #Main application
└── package.json    #File with dependencies

```

In `package.json` you can find all the dependencies.
In `src` folder you can find all sources for the project (images, sass , javascript files).

## `assets` folder structure

```
├── fonts                       #Folder for storing fonts
├── js                          #Folder for javascript files
├── images                      #Folder for storing images
├── sass                        #Folder for storing sass folders/files
   ├── abstracts
      ├── _mixins.scss          #Sass mixins
      ├── _variables.scss       #Sass variables that we can use in our scss files
    ├── base
      ├── _animations.scss       #Sass functions
      ├── _typography.scss
      ├── _fonts.scss
      ├── _base.scss
      ├── _utilities.scss
   ├── components               #Global Reusable Presentational Components
      ├── _forms.scss           #Sass styles for form
      ├── _navbar.scss
   ├── layout                   #Global layout footer/header
   ├── pages                    #Global styles for pages
   ├── main.scss               #Main scss file (can be used for importing another files)
```
