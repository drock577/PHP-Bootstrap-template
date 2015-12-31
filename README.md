# [PHP Bootstrap Template](https://github.com/Tikal-Interactive/PHP-Bootstrap-template#)
This is a basic bootstrap template I currently use for [my webiste](http://template.thesheriff.me). This version will constantly be changing in order to accomidate the growing needs of my site. This is a simple bootstrap design for PHP integration.

## Table of contents
- [Overview](#overview)
- [Version](#version)
- [Commiting](#comiting)
- [License](#License)


## Overview
A very simple Bootstrap Template for the PHP framework. Bootstrap V 3.1.1 is included as doesn't contain any edits.
All modifications to the template are happening in index.css & index2.css. These CSS files are called in the template/includes folder. The tempate/includes folder also holds the folders Bootstrap, JQuerry, and php subfolders. Bootstrap and JQuerry are the files sent with the V3.1.1 version of Bootstrap.

## PHP Subfolder
The PHP subfolder in Template/includes holds the following files...

###footer.php
This file is the footer of the website, used throughout. Making modification to this file will be carried over between all php files.

###header.php
Like the footer.php this file is the header of hte website, used throughout. Again, modifications to this file will be used on all php files.

###includebottom.php
This file will be included in under the footer, and above the body tag in a normal PHP document. This exists incase you want to make mutiple copies like bellow. Here you can make copies to call new JS files or add specific functions to one page only. Where scripts should be called after all content is loaded. Mostly Javascript files.

###includeindex.php & includeindex2.php
These two files server the same purpose. There just calling a different CSS file. This is where you should included files that should be called before any content loaded.  This file includes the websites meta data, favicon, title, and CSS links.

## Version
The current version is currently considered Version 1.

## License
This is currently released under the [MIT](https://github.com/Tikal-Interactive/PHP-Bootstrap-template/blob/master/LICENSE).
