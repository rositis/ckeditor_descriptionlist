CKEditor Description List
=========================
This modules adds description list plugin into the WYSIWYG editor,
that provides the ability to create a definition list such as dl,
dt and dd html tags.

This module is a backport of the CKEditor Description List from Drupal 8/9 to
Backdrop CMS.

* For a full description of this module, visit the project page:
  https://www.drupal.org/project/ckeditor_descriptionlist

* To submit bug reports and feature suggestions, or track changes:
  https://www.drupal.org/project/issues/ckeditor_descriptionlist


Requirements
------------
This module requires the [Description list plugin](https://github.com/Reinmar/ckeditor-plugin-descriptionlist)

Installation
------------
1. Download the plugin from https://github.com/Reinmar/ckeditor-plugin-descriptionlist

2. Place the plugin in the root libraries folder (/libraries/ckeditor-plugin-descriptionlist).

3. Install and enable the **ckeditor_descriptionlist** module using the official [Backdrop CMS modules installation instructions](https://docs.backdropcms.org/documentation/extend-with-modules).

4. Configure your CKEditor toolbar to include Description List buttons. Go to the
Text Formats and editors settings 'Admin -> Configuration -> Content -> Formats'
and add the following buttons : Tag dl, Tag dd, Tag dt to the CKEditor-enabled text
format desired.

How to Use
----------
While editing a textfield, highlight the text you want formatted using a Definition
List and click on the appropriate button in the toolbar.

Dependencies
------------
Views

Documentation
-------------
Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/block_refresh/wiki/Documentation

Issues
------
Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/ckeditor_descriptionlist/issues

Current Maintainers
-------------------
- Ryan Ositis (https://github.com/rositis)

Credits
-------
- Ported to Backdrop CMS by [Ryan Ositis](https://github.com/rositis).
- Maintained for Drupal by [Tsymi](https://www.drupal.org/u/tsymi).

License
-------
This project is GPL v2.0 software.
See the LICENSE.txt file in this directory for complete text.
