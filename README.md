# Main CSS - Sass Version

The main CSS elements of Ambitious Framework.


## Getting Started

1 - Access your project/assets folder and clone this repository

```bash
$ git clone git://github.com/ambitiouswebkit/main-css.scss.git [folder]
```

2 - Profit!

> **Note:** [compass](http://compass-style.org) is required.


## Structure

    .
    ├── app
    │   ├── _helpers.scss
    │   ├── _layout.scss
    │   ├── _legacy.scss
    │   └── _responsive.scss
    ├── core
    │   ├── _config.scss
    │   ├── _grid.scss
    │   ├── _mixins.scss
    │   ├── _print.scss
    │   └── _settings.scss
    ├── general
    │   ├── _base.scss
    │   └── _reset.scss
    ├── helpers
    │   ├── _animation.scss
    │   ├── _buttons.scss
    │   ├── _forms.scss
    │   ├── _globals.scss
    │   ├── _grid.scss
    │   ├── _icons.scss
    │   ├── _images.scss
    │   ├── _inputs.scss
    │   ├── _links.scss
    │   ├── _lists.scss
    │   ├── _responsive.scss
    │   ├── _sprite.scss
    │   ├── _tables.scss
    │   └── _types.scss
    ├── modules
    ├── vendors
    ├── _all.scss
    └── style.scss

#### `_all.scss`

This file is responsible to import all partials.

#### `app`

Folder that keep the styles for your application.

- `_layout.scss`: your Application Style goes here
- `_reponsive.scss`: your Application Responsive rules goes here
- `_legacy.scss`:your Legacy (old browser support) goes here
- `_helpers.scss`: custom helpers goes here

#### `core`

Folder that keep the Core Styles for the project

- `_config.scss`: inital Configuration
- `_settings.scss`: variables
- `_mixins.scss`: mixins
- `_grid.scss`: grid system constructor
- `_print.scss`: media query for print

#### `general`

Folder that keep the Scaffolding style.

- `_reset.scss`: CSS Normalize
- `_base.scss`: Base Structure

#### `helpers`

- `_animation.scss`: CSS animations goes here
- `_buttons.scss`: helper classes for buttons
- `_forms.scss`: helper classes for forms
- `_globals.scss`: global classes
- `_grid.scss`: modular grid system
- `_icons.scss`: font icons customization goes here
- `_images.scss`: helper classes for images
- `_inputs.scss`: helper classes for inputs
- `_links.scss`: helper classes for links
- `_lists.scss`: helper classes for lists
- `_responsive.scss`: helper classes for responsive visibility rules
- `_sprite.scss`: helper to generate sprites
- `_tables.scss`: helper classes for tables
- `_types.scss`: helper classes for types

#### `modules`

When you are developing a web application, it's very important to use standards and best practices to keep a high level of modularization. This folder is responsible for keeping your ui components. Name it according to the nomenclature given in your behavior layer (JavaScript). This will keep the standard nomenclature and structure for both layers.

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
