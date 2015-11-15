<a href="http://www.ffuenf.de" title="ffuenf - code • design • e-commerce"><img src="https://github.com/ffuenf/Ffuenf_Common/blob/master/skin/adminhtml/default/default/ffuenf/ffuenf.png" alt="ffuenf - code • design • e-commerce" /></a>

Ffuenf_CategoryProductSortBackend
=================================
[![GitHub tag](https://img.shields.io/github/tag/ffuenf/Ffuenf_CategoryProductSortBackend.svg)][tag]
[![Build Status](https://img.shields.io/travis/ffuenf/Ffuenf_CategoryProductSortBackend.svg)][travis]
[![Code Climate](https://codeclimate.com/github/ffuenf/Ffuenf_CategoryProductSortBackend/badges/gpa.svg)][codeclimate_gpa]
[![Test Coverage](https://codeclimate.com/github/ffuenf/Ffuenf_CategoryProductSortBackend/badges/coverage.svg)][codeclimate_coverage]
[![PayPal Donate](https://img.shields.io/badge/paypal-donate-blue.svg)][paypal_donate]
[tag]: https://github.com/ffuenf/Ffuenf_CategoryProductSortBackend
[travis]: https://travis-ci.org/ffuenf/Ffuenf_CategoryProductSortBackend
[codeclimate_gpa]: https://codeclimate.com/github/ffuenf/Ffuenf_CategoryProductSortBackend
[codeclimate_coverage]: https://codeclimate.com/github/ffuenf/Ffuenf_CategoryProductSortBackend
[paypal_donate]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=J2PQS2WLT2Y8W&item_name=Magento%20Extension%3a%20Ffuenf_CategoryProductSortBackend&item_number=Ffuenf_CategoryProductSortBackend&currency_code=EUR

This extension for Magento Community Edition allows changing products sort order within category by drag & drop.

Platform
--------

The following versions are supported and tested:

* Magento Community Edition 1.9.2.2
* Magento Community Edition 1.9.2.1
* Magento Community Edition 1.9.2.0
* Magento Community Edition 1.8.1.0
* Magento Community Edition 1.7.0.2
* Magento Community Edition 1.6.2.0

Other versions are assumed to work.

Requirements
------------

|                                                                     | PHP 5.3        | PHP 5.4        | PHP 5.5           | PHP 5.6       | PHP 7.0       |
| ------------------------------------------------------------------- | -------------- | -------------- | ----------------- | ------------- | ------------- |
| [EOL](https://secure.php.net/supported-versions.php) / STABLE / RC  | EOL            | EOL            | STABLE            | **STABLE**    | RC            |
| automated tests on [travis]                                         | allow failure  | allow failure  | **required pass** | allow failure | allow failure |

Magento Community Edition officially supports PHP 5.4 and PHP 5.5.

Non-official compatibility to PHP 5.6 may be reached by following the tips on [Use of iconv.internal_encoding is deprecated](https://magento.stackexchange.com/questions/34015/magento-1-9-php-5-6-use-of-iconv-internal-encoding-is-deprecated).

Installation
------------

Use [modman](https://github.com/colinmollenhour/modman) to install:
```
modman init
modman clone https://github.com/ffuenf/Ffuenf_Common
modman clone https://github.com/ffuenf/Ffuenf_CategoryProductSortBackend
```

Deinstallation
--------------

Use [modman](https://github.com/colinmollenhour/modman) to clear all files and symlinks:
```
modman clean Ffuenf_CategoryProductSortBackend
```
see `uninstall.sql` to clear all entries of this extension from your database.

Development
-----------
1. Fork the repository from GitHub.
2. Clone your fork to your local machine:

        $ git clone https://github.com/USER/Ffuenf_CategoryProductSortBackend

3. Create a git branch

        $ git checkout -b my_bug_fix

4. Make your changes/patches/fixes, committing appropriately
5. Push your changes to GitHub
6. Open a Pull Request

License and Author
------------------

- Author:: Achim Rosenhagen (<a.rosenhagen@ffuenf.de>)
- Copyright:: 2015, ffuenf

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
