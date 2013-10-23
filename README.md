aws-sdk-ios
===========

AWS SDK framework for OS X. Created by modifying the official AWS SDK for iOS. This framework works for 64-bit machines, Mac OS X 10.7+. For more information on the AWS SDK for iOS, see the AWS web site:

http://aws.amazon.com/sdkforios

To build the AWS SDK for OSX, open the Xcode project src/AWSiOSSDK.xcodeproj. Build the framework target. The new framework directory will be placed in the top-level directory of the repo.

This is configured for 10.7. If you want to build against 10.8 or later, you'll need to change both the SDK targets in Build Settings and line 38 of src/Scripts/Framework.sh.
