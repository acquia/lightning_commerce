# <img src="lightning_commerce.png" width="32"> Acquia Lightning for Commerce
[![Build Status](
https://travis-ci.org/acquia/lightning-commerce.svg?branch=master
)](
https://travis-ci.org/acquia/lightning-commerce
)

Acquia Lightning for Commerce distribution is built on the top of popular
Drupal Lightning. We're focusing on providing effortless way for testing
Acquia Commerce Manager. 

## Installing Acquia Lightning for Commerce
The preferred way to install Acquia Lightning for Commerce is using our
[Composer-based project template](
https://github.com/acquia/lightning-commerce-project
).
It's easy!

```
$ composer self-update
$ composer create-project acquia/lightning-commerce-project MY_PROJECT
```

If you don't want to use Composer, you can install Acquia Lightning for
Commerce the traditional way by downloading a tarball from 
Acquia Lightning for Commerce's [GitHub releases page](
https://github.com/acquia/lightning-commerce/releases
).
(Please note that the tarball generated by Drupal.org's packager does not
include required Composer dependencies and should not be used without following
the special instructions found there.)

From version 1.6.0, we require at least PHP7.1.

## What Acquia Lightning for Commerce Does
Acquia Lightning for Commerce provides all feature of Drupal Lightning. Extra 
features are focused on seamless integration with Acquia Commerce Manager and 
easy set up of sales demos:
 - ACM demo module - easy setup of ACM modules and demo content on the top of
that.
 - ACM demo theme - theming for effective presentation of all available
commerce features. 

## Known Issues
 - Minicart block font color is same as background color in demo theme - you
can either remove theming for minicart block entirely or override it in your
theme.
 - For other possible issues please check [Drupal Lightning](
 https://github.com/acquia/lightning#known-issues
 ).  

## Contributing
Issues and contributions are welcomed on our [GitHub](
https://github.com/acquia/lightning-commerce
).
Please check our [contribution guide](
https://github.com/acquia/lightning-commerce/blob/master/CONTRIBUTING.md
) first.


## Copyright and license
Acquia Lightning for Commerce
   
Copyright &copy; 2018 Acquia Inc.

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
