# Faces for [webtrees](https://www.webtrees.net/)

[![Latest Release](https://img.shields.io/github/release/UksusoFF/webtrees-faces.svg)](https://github.com/UksusoFF/webtrees-faces/releases/latest)
[![Code Climate](https://lima.codeclimate.com/github/UksusoFF/webtrees-faces/badges/gpa.svg)](https://lima.codeclimate.com/github/UksusoFF/webtrees-faces)
[![Support Thread](https://img.shields.io/badge/support-forum-brightgreen.svg)](https://www.webtrees.net/index.php/en/forum/2-open-discussion/30219-how-to-mark-individuals-on-group-photo)

This module provide easy way to mark people on group photo.

## Warning

All data stored in database and can't be exported as part of GEDCOM files.

## System requirements
Same as [webtrees#system-requirements](https://github.com/fisharebest/webtrees#system-requirements).

Tested with 2.0 version and bundled themes.

## Installation
1. Make database backup
1. Download the [latest release](https://github.com/UksusoFF/webtrees-faces/releases/latest).
1. Upload the downloaded file to your web server.
1. Unzip the package into your `webtrees/modules_v4` directory.
1. Rename the folder to `faces`.
1. Go to the control panel (admin section) => Module administration => Enable the `Faces` module and save your settings.

### Old version
You can use [2.2.1 version](https://github.com/UksusoFF/webtrees-faces/releases/tag/v2.2.1) with webtrees 1.7.x version.

## Usage

For mark people on image you must click by (+) button, select area and enter something id.

As id you can enter person id that exist in tree (like I1) or just any string for others mark.

### Google Picasa

Module can show Google Picasa face tags.

This feature disabled by default. For enable go to module settings and check "Read XMP data".

Read more:
* [fisharebest/webtrees/issues/744](https://github.com/fisharebest/webtrees/issues/744)
* [AvPicFaceXmpTagger](http://www.anvo-it.de/wiki/avpicfacexmptagger:main)
* [XMP, IPTC/IIM, or Exif; which is preferred?](https://www.carlseibert.com/xmp-iptciim-or-exif-which-is-preferred/)

### MyHeritage Family Tree Builder

If you wish import data from [MyHeritage Family Tree Builder](https://www.myheritage.com/family-tree-builder) please check additional script [miqrogroove/face-tag-import](https://github.com/miqrogroove/face-tag-import). 

## Result

![pnwim](https://cloud.githubusercontent.com/assets/1931442/23299146/d33eb9d0-fa99-11e6-96f1-d07c89fc6f0f.png)

## Todo
* Save original photo title
* Delete relation to individuals
* Import/export module data
* Import from MyHeritage Family Tree Builder ([#1714](https://github.com/fisharebest/webtrees/issues/1714), [#2358](https://github.com/fisharebest/webtrees/issues/2358))

## Vendor dependencies
* [ImageMapster](https://github.com/jamietre/imagemapster) 
* [imgAreaSelect](https://github.com/odyniec/imgareaselect)
* [mobile-detect.js](https://github.com/hgoebl/mobile-detect.js)
