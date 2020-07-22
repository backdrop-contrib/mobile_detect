Mobile Detect (2.8.34)
======================

This module is a wrapper for the [Mobile Detect library](https://github.com/serbanghita/Mobile-Detect), 
and you should only need to install it if another module requires it. It does 
not provide any new functionality on its own.

Installation
------------

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

Developers
------------

If your module requires the library provided by this wrapper, you can access the
JavaScript by:

- Requiring this module as a dependency in your module
- Loading the file as follows: `include_once (backdrop_get_path('module', 'mobile_detect') . '/library/Mobile_Detect.php');`

Issues
------

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/mobile_detect/issues)

Current Maintainers
-------------------

- [Laryn Kragt Bakker](https://github.com/username/), [CEDC.org](https://CEDC.org) 

Credits
-------

- [Laryn Kragt Bakker](https://github.com/username/), [CEDC.org](https://CEDC.org) 


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
