Footnotes
=========

The plugin allows to add footnotes in an easy way to a text. There is no need for numbering the footnotes.

The footnotes have a link to go back to the previous reading position.

The plugin uses Footnoted from Jacob Heftmann:

https://github.com/jheftmann/footnoted

Installation and use with EasyMDE
---------------------------------

* Download the ZIP archive to your PC.
* Unzip the archive.
* Load the directory `/footnotes` in the extracted ZIP archive in the directory `/bl-plugins` on your server.
* Load the file `plugin.php` in the directory `/easymde` in the extracted ZIP archive in the directory `/bl-plugins/tinymce` on your server.
* There will be two new symbols in the toolbar of the editor. The first one is for adding the code for the footnote after the text, the second one for adding the code for the part with the references below the text. Please add your references between the `<li>` and `</li>` in the list of the references.

Versions
--------

1.0, August 2, 2020
- Addition of the file plugin.php for EasyMDE.
- Removal of jQuery script.

0.1, July 15, 2017
- Release.
