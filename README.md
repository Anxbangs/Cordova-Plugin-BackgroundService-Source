# Source code for the Background Service Plugin for Cordova #

This is the source code for my BackgroundService for use with Cordova.

Normally it will be easier for you to use the compiled versions, found at https://github.com/Red-Folder/Cordova-Plugin-BackgroundService

## Using the code ##

I use the code within an Android Library.  Copy the src & aidl folders into the root folder of your project.

Note that if you attempt to use this code directly within an application, you will be need to refer to additional files provided in https://github.com/Red-Folder/Cordova-Plugin-BackgroundService

## Cordova Versions ##

Cordova versions provide different plugin architecture.  To provide for this I have seperate wapper for each version.  This is represented by the various BackgroundServicePlugin.vx.x.x.java files.  

You will only want to include one of these in your project (delete the other versions) and then rename it to BackgroundServicePlugin.java.

## Depreciated Versions ##

Over time I will no longer maintain older versions.  These will be listed here.  The code is still be available, but may not compile or build without work.

* BackgroundServicePlugin.v1.8.1.java - For use with Cordova 1.8.1 - Depreciated 21st August 2013
* BackgroundServicePlugin.v2.0.0.java - For use with Cordova 2.0.0 - Depreciated 21st August 2013

## Further Information ##

Further information on the plugin can be found at:

* http://red-folder.blogspot.co.uk/2012/09/phonegap-android-background-service.html
* http://red-folder.blogspot.com/2012/09/phonegap-android-background-service_11.html

The below is a tutorial to create your own Twitter service:

* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-1.html
* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-2.html
* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-3.html

Please let me know your thoughts and comments.

## Licence ##

The MIT License

Copyright (c) 2013 Red Folder Consultancy Ltd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

