NSDictionary-OMRuntime
======================

Additional methods for NS(Mutable)Dictionary to support array subscripting syntax for SDK's before iOS 6. 

Xcode 4.4 does support the new modern Objective-C runtime features for `NSNumber`, `NSArray` and `NSDictionary`. All but subscripting (like `myArray[42]` instead of `[myArray objectAtIndex:42]` and `myDict[@"name"]` instead of `[myDict valueForKey:@"name"]`). This only is available with the iOS 6.0 SDK for Xcode 4.5.
With this category you can enable this for iOS 5.1 and earlier for Xcode 4.4.


See also [NSArray+OMRuntime](https://github.com/dhoogenb/NSArray-OMRuntime) for a category for NSArray.

#License
This Code is released under the BSD License by [Obvious Matter](http://www.obviousmatter.com).