titanium-ios-imageutils
=======================

Image utilities module for Titanium appcelerator.

PNG To JPG:
-----------
Example usage:

    var png_file = Titanium.Filesystem.getFile('image.png');
    var png_blob = png_file.read();
    var imageutils = require("it.extrategy.imageutils");
    var compression_ratio = 0.8;
    var jpg_blob = imageutils.png2jpg(png_blob, compression_ratio);

Feel free to add functions or improve the library. Pull requests are welcome.
