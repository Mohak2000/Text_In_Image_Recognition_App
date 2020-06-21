# Text_In_Image_Recognition_App
This app is used to detect text present in the image by scanning the image
1.Implemented on Android Studio supported by java and version Appcompat androidx
2.Supported by Firebase ML Vision library version 15.0.0
3.Versions :- minSdkVersion 21,targetSdkVersion 29, compileSdkVersion 29, buildToolsVersion "29.0.3"

Step-1 Intitially, there is a button named capture image which Actions to image capture
Step-2 And then image previews on the image view at the main screen 
Step-3 Then upon clicking the button named Detect Text
Step-4 The FirebaseVisionTextDetector plays its role and detects the text
Step-5 Text found out is displayed in the Text View if not then a Toast message is displayed "No text found in the image"
