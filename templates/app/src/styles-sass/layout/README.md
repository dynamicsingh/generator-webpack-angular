# BYS-front

## SASS

Préconisations https://sass-guidelin.es/?utm_source=CSS-Weekly&utm_campaign=Issue-145&utm_medium=RSS#architecture

### LAYOUT FILE

The layout/ folder contains everything that takes part in laying out the site or application. This folder could have stylesheets for the main parts of the site (header, footer, navigation, sidebar…), the grid system or even CSS styles for all the forms.

_grid.scss
_header.scss
_footer.scss
_sidebar.scss
_forms.scss
_navigation.scss

The layout/ folder might also be called partials/, depending on what you prefer.

### Structure

sass/
|
|– layout/
|   |– _navigation.scss   # Navigation
|   |– _grid.scss         # Grid system
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|   …                     # Etc.