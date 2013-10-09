protobuf-pod
============

Google Protobuf library (c++) as Cocoa Pod, easy to import to your project

Original Google Protobuf project site:
https://code.google.com/p/protobuf/

Inspiration:
http://www.kotancode.com/2012/10/14/using-google-protocol-buffers-in-objective-c-on-ios-and-the-mac/

It is just original Google Protocol Buffers 2.4.1 C++ code, without test classes. 
Work on XCode5 for iOS7. 
For iOS 6.1 you need to change config.h to include <tr1/unordered_map> instead of <unordered_map> and change namespace to 
tr1::unordered_map. I could not find the way to check iOS version by some defines, so there should be some custom in a projekt.
If you need support for iOS 6.1 or earlier, create a pull request or let me know.
