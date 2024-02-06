Views Filters Populate
======================

This module "populates" other filters on the view with the provided value,
allowing to use one exposed filter to search several others. It's similar to the
 Global: Combine fields filter available on Drupal 8 and on Views 7.x-3.4+ so
you'll only need this if you are aware of the differences.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- Create an OR group of filters for each of the fields that you want to search
  on; make sure you don't expose those filters and that you choose the
  appropriate operator that will accompany the value for each filter.

- Add another filter found on the 'Global' section called 'Populate filters'.

- Expose it and check the filters which you have previously added that you wish
  this exposed filter to populate, on our example they are first name, second
  name and last name. Remember that only supported and non exposed filters will
  be available for selection.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/views_filters_populate/issues).

Current Maintainers
-------------------

- [Eli Lisseck](https://github.com/elisseck), [Giant Rabbit](https://github.com/giant-rabbit).

Credits
-------

- Ported to Backdrop CMS by [Eli Lisseck](https://github.com/elisseck), [Giant Rabbit](https://github.com/giant-rabbit).
- Originally written for Drupal by [Ariel Barreiro](https://git.drupalcode.org/hanoii).
- Maintained for Drupal by [Ariel Barreiro](https://git.drupalcode.org/hanoii),
[Francisco Giudici](https://git.drupalcode.org/fgiudici), [Elliot Ward](https://git.drupalcode.org/Eli-T)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
