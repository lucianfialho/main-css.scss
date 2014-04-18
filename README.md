# Main CSS

The main CSS elements of Ambitious Framework.


## Getting Started

1 - Access your project/assets folder and clone this repository

```bash
$ git clone git://github.com/ambitiousframework/main-css.git sass
```

2 - Profit!


## File Organization

    .
    ├── _all.scss
    ├── app
    │   ├── _layout.scss
    │   ├── _legacy.scss
    │   └── _responsive.scss
    ├── core
    │   ├── _config.scss
    │   ├── _functions.scss
    │   ├── _grid.scss
    │   ├── _mixins.scss
    │   └── _print.scss
    ├── general
    │   ├── _base.scss
    │   ├── _forms.scss
    │   ├── _reset.scss
    │   └── _tables.scss
    ├── helpers
    │   ├── _animation.scss
    │   ├── _browser.scss
    │   ├── _grid.scss
    │   ├── _icons.scss
    │   ├── _responsive.scss
    │   └── _sprites.scss
    ├── modules
    ├── style.scss
    └── vendors

#### `_all.scss`

This file is responsible to import all partials.

#### `app`

Folder that keep the styles for your application.

- `_layout.scss`: your Application Style goes here
- `_reponsive.scss`: your Application Responsive rules goes here
- `_legacy.scss`:your Legacy (old browser support) goes here

#### `core`

Folder that keep the Core Styles for the project

- `_config.scss`: inital Configuration
- `_mixins.scss`: Sass Mixins
- `_functions.scss`: Sass Functions
- `_grid.scss`: grid system constructor
- `_print.scss`: media query for print

#### `general`

Folder that keep the Scaffolding style.

- `_reset.scss`: CSS Normalize
- `_base.scss`: general structure
- `_tables.scss`: general table style
- `_forms.scss`: general form style

#### `helpers`

- `_grid.scss`: modular grid system
- `_browser.scss`: utils classes for the browser
- `_responsive.scss`: utils classes for responsive visibility rules
- `_icons.scss`: your font icons customization goes here
- `_sprites.scss`: Compass helper to generate sprite images
- `_animation.scss`: your CSS animations goes here

#### `modules`

Quando você está desenvolvendo um aplicativo web, é muito importante utilizar padrões e praticas para mantér um alto nível de modularização/componentização. Este diretório é reposnável por manter os seus módulos. Nomei-os de acordo com a nomenclatura dada na sua camada de comportamento (JavaScript).

Ex.:

    ./
    scripts
        modules
            comments.js
    styles
        modules
            comments.scss


#### `vendors`

External plugins and libs goes here.


## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
