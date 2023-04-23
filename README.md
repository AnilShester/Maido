# Responsive design

Responsive design uisng flexbox and grid. Implementing animation and styling using CSS/SASS.

# Table of contents

- [Technologies](#technologies)
- [Project structure](#project-structure)
- [Results](#results)
- [Getting Started] (#getting-started)

## Technologies

- HTML5
- CSS
- SASS

## Project structure

```
├───.vscode
├───assets
├───node_modules
│   ├───.bin
│   ├───anymatch
│   ├───binary-extensions
│   ├───braces
│   │   └───lib
│   ├───chokidar
│   │   ├───lib
│   │   └───types
│   ├───fill-range
│   ├───glob-parent
│   ├───immutable
│   │   └───dist
│   ├───is-binary-path
│   ├───is-extglob
│   ├───is-glob
│   ├───is-number
│   ├───normalize-path
│   ├───picomatch
│   │   └───lib
│   ├───readdirp
│   ├───sass
│   │   └───types
│   │       ├───legacy
│   │       ├───logger
│   │       ├───util
│   │       └───value
│   ├───source-map-js
│   │   └───lib
│   └───to-regex-range
└───src
    └───styles
        ├───components
        └───variables

```

## Result

Recreated the Maido website using HTML, CSS and SCSS only.

## Getting Started

Link to the [website] (https://astounding-licorice-9e8632.netlify.app/)

{
"name": "fs15_2-responsive-design",
"version": "1.0.0",
"description": "Responsive design uisng flexbox and grid. Implementing animation and styling using CSS/SASS.",
"main": "index.js",
"scripts": {
"compile": "sass src/styles/style.scss:src/style.css",
"compile:watch": "sass --watch src/styles/style.scss:src/style.css"
},
"repository": {
"type": "git",
"url": "git+https://github.com/AnilShester/fs15_2-responsive-design.git"
},
"author": "",
"license": "ISC",
"bugs": {
"url": "https://github.com/AnilShester/fs15_2-responsive-design/issues"
},
"homepage": "https://github.com/AnilShester/fs15_2-responsive-design#readme",
"dependencies": {
"sass": "^1.62.0"
}
}
