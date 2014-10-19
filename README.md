DGFastImageSize
======================

Retrieve image dimensions in no-time at all. High performance image dimension reader for iOS / ObjC.

If you need to know the dimensions of an image (local file) and you need it fast - this is the library for you.
It will parse the headers of any PNG, JPEG, TIFF, GIF, BMP and ICNS file, and read the dimensions without reading the whole file.
It will also rotate the dimensions correctly according to orientation EXIF tags.

This is a great alternative if you tried using `UIImage` to read an image's dimensions and found out that you have to do it on another thread because it takes too long... With `DGFastImageSize` you do not have to go multithreaded - you can know the size immediately without performance impact.

Special thanks to David W. Stockton for doing some work on ICNS format support. (Did some work on TIFF also, but that turned out to be a duplicate of the EXIF code which we already had, but thanks anyway!)


This was originally in my other repository https://github.com/danielgindi/drunken-danger-zone/


## Me
* Hi! I am Daniel Cohen Gindi. Or in short- Daniel.
* danielgindi@gmail.com is my email address.
* That's all you need to know.

## Help

If you like what you see here, and want to support the work being done in this repository, you could:
* Actually code, and issue pull requests
* Spread the word
* 
[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CHRDHZE79YTMQ)

## License

All the code here is under MIT license. Which means you could do virtually anything with the code.
I will appreciate it very much if you keep an attribution where appropriate.

    The MIT License (MIT)
    
    Copyright (c) 2013 Daniel Cohen Gindi (danielgindi@gmail.com)
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

