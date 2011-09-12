What is IOS Boilerplate
-----------------------

Is a code base for iOS projects. Current version provides

  - BaseViewController with methods for secure handling of async http requests
  - ImageManager: a class for downloading images asynchronously
  - FastCell (inspired on [Atebits implementation](http://nickharris.wordpress.com/2010/06/17/fast-uitableviewcell-with-a-uiwebview/)) is a base class for implementing custom UITableViewCells with fast scrolling.
  - DictionaryHelper: an NSDictionary helper with methods for safe handling of collections
  - StringHelper: an NSString helper with methods for manipulating NSStrings. Including: trim, sha1 and urlEncode method.
  - DataHelper: an NSData helper with one method: hexString. It is used inside StringHelper to calculate the sha1 hash hexstring representation of a given string

The project contains some examples with the use of those utility classes:

  - Example that fetches a JSON object through an async HTTP request, and shows a progress HUD.
  - Example that fetches a single image with ImageManager
  - Example that combines FastCells with async image loading using ImageManager.
  - Example of variable height table cells using FastCell.
  - ViewController that uses MapOverlays and the Google Maps API to show the directions between two points.
  - Search bar that autocompletes locations.

Some screenshots:

![Demo menu](https://github.com/gimenete/iOS-boilerplate/raw/master/shots/demo-menu.png)

![Async cell images demo](https://github.com/gimenete/iOS-boilerplate/raw/master/shots/async-cells.png)

![Directions demo](https://github.com/gimenete/iOS-boilerplate/raw/master/shots/directions.png)


IOS Boilerplate includes some third party software:

  - [ASIHTTPRequest](http://allseeing-i.com/ASIHTTPRequest/)
  - [SVProgressHUD](https://github.com/samvermette/SVProgressHUD)
  - [JSONKit](https://github.com/johnezang/JSONKit)