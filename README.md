# ios-twitter-sdk-example
An example iOS app that uses the Twitter SDK.

This isn't intended to be a working application.  I intend to use this
to perform static analysis against the generated binary IPA.  The resulting
app will be used as a test case for programmatic identification of iOS 
applications that leverage the Twitter SDK.

Instructions:
1) Install rvm
2) Install bundler
```
$ gem install bundler
```
3) Install cocoapods gem
``` 
$ bundle install
```
4) Install pods
```
$ pod install
```
5) Add FABRIC_API_KEY and BUILD_SECRET to ios-twitter-sdk-example.xcodeproj/project.pbxproj
6) Add FABRIC_API_KEY, "Consumer Key", and "Consumer Secret" to ios-twitter-sdk-example/AppDelegate.m
7) Build the project using XCode
