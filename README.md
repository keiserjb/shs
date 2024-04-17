# Simple Hierarchical Select

The Simple Hierarchical Select module displays selected taxonomy fields as
hierarchical selects on node creation/edit forms and as exposed filter in views.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Configuration and Usage

* Create a new field (type "Term reference") and select
  "Simple hierarchical select" as widget type.

* Field settings
  - "Allow creating new terms"
    Terms may be created directly from within the dropdowns (user needs to have
    permission to create terms in the vocabulary).
  - "Allow creating new levels"
    If selected users with permission to create terms in the vocabulary will be
    able to create a new term as child of the currently selected term.
  - "Force selection of deepest level"
    Force users to select terms from the deepest level.

* Views (exposed filter)
  - add a new filter using the field set-up as "Simple hierarchical select" or
    use "Content: Has taxonomy terms (with depth; Simple hierarchical select)"
    as a new filter
  - use "Simple hierarchical select" as selection type
  - select "Expose this filter to visitors, to allow them to change it"
  - enjoy :)

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/shs/issues)

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/shs/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
- [Justin Keiser][https://github.com/keiserjb)
- Co-maintainers desired

## Credits

- Port to Backdrop (in process) by [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
- Maintained for Drupal by [Stefan Borchert](http://drupal.org/user/36942)
- Sponsored for Drupal by [undpaul](http://www.undpaul.de)


## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
