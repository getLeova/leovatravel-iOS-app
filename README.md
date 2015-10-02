# iOS App source for Cordova
Source code for the Leova iOS demo app ( https://getleova.onesevene.com ) 

iOS:

What You Need:

1. Mac with OS X
2. Xcode 7.0 or higher
3. Cordova CLI

Steps to install APP on an iPhone:

1. Download the zip file on your Mac
2. Extract it to folder
3. Open up the folder and go to Leova > platforms > ios
4. Open up the LeovaTravel.xcodeproj file in xcode
5. Build and deploy the project on your iPhone
6. If you get a Security issue, go to setting on your iPhone
7. In settings go to General and select Profile
8. Under Developer app, select the email id verify the app

This iOS app uses iSpeech (http://www.ispeech.org/) as the speech recognizer. The iSpeech recognizer is free (all you've gotta do is get a free developer account) but it's accuracy is not as great as the one google offers in Android and Chrome. Leova helps mitigate some of the errors in speech recognition using machine learning specifically for iSpeech.