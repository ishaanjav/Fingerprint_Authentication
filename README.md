<img align="right" src="https://github.com/ishaanjav/Fingerprint_Authentication/blob/master/Fingerprint%20App.png" width="270">

# Fingerprint Authentication


**This app is simply meant to serve as a demo and guide of how to do fingerprint authentication in Android using the device's fingerprint reader.** The content of this app can be applied for a variety of purposes such as:
- Allowing only authorized users to access certain features of an app by requiring them to scan their finger.
- Serving as a verification system for visitors entering a house by requiring them to place their finger on the fingerprint reader. 

Essentially, the app is meant to model how to implement fingerprint authentication in an Android app. This feature can then be adapted into other apps for a variety of uses. *For my more
extensive GitHub projects, you can check out [this repository](https://github.com/ishaanjav/Face_Analyzer) on [Analyzing Faces](https://github.com/ishaanjav/Face_Analyzer) 
by using the Microsoft Face API.*

____

<img align="left" src="https://github.com/ishaanjav/Fingerprint_Authentication/blob/master/Animated%20Example.gif" width="290" height = "570">

## Usage
The app consists of a single button which is only used to reset the app once the person has been identified by placing their finger on the fingerprint reader. If the fingerprint cannot be identified by the device, then the app displays a message stating that `"Authentication Failed"`. Otherwise, the app will display a message of success and the user can press the `"Reset"` button to restart the process.

**Please note that in order to test this app, your device must:**
- **have a fingerprint reader.**
- **have a fingerprint already registered through the device's settings.**

Once these requirements have been met, the app can use the `FingerprintManager` and `KeyguardManager` classes to match a fingerprint agaist the existing fingerprints on the device. Feel free to make any modifications to the app once you have cloned it or use the code for  other apps.

## Other Repositories
While this is one of my simpler, demo Android apps, I do have some other repositories that serve more useful purposes and make use of APIs like the [Microsoft Face API](https://azure.microsoft.com/en-us/services/cognitive-services/face/), [Kairos API](https://www.kairos.com/docs/), [Google Maps SDK](https://developers.google.com/maps/documentation/android-sdk/intro) and more. Below is a list of some of those repositories:

- [**Face Analyzer**](https://github.com/ishaanjav/Face_Analyzer): The purpose of this Android app is to utilize the Microsoft Face API to not only detect individual faces in an image, but also for each face provide information such as emotions, the estimated age, gender, and more. [README](https://github.com/ishaanjav/Face_Analyzer/blob/master/README.md)



