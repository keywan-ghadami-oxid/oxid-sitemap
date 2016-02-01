# Google Sitemap Exporter

improved Google Sitemap Exporter for Oxid eShop, based on https://github.com/OXIDprojects/google_sitemap

it embraces common code best practices:
- composer
- semver
- tests
- travis
- dependency injection
- namespaces

## Requirements
- Oxid eShop >= 4.9.6
- PHP >= 5.5

## Installation

- run 'composer require ivoba/oxid-sitemap' in modules dir
- copy content of *modules/vendor/ivoba/oxid-sitemap/copy_this* to your shop
- edit sitemap_xml.php to your needs, if necessary
- take care that your target file is writeable by the webserver

## Usage

call http://yourshop.biz/sitemap_xml.php

if you need lower urls set the 3rd param to true: SiteMapGenerator($config, $queries, true)

## Caution
As oxid-esales/eshop is not on packagist by now, its not listed as composer dependency.  

## License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

