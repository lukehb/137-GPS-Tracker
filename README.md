# 137-GPS-Tracker
An Android GPS tracker that allows the user to annotate their current location/time-stamp as either stopped or moving.

## Why would you want a GPS tracker where the user has to manually annotate stops/moves?
There exists plenty of algorithms that examine a GPS trail and determine whether the entity is moving or stopped at each recording. However, to compare the effectiveness of such algorithms a ground truth is needed - and that is what this app provides. The user can travel some distance and manually indicate whether they are stopped or moving and then this annotated trail is stored by the app. With this ground truth trace we can evaluate whether the algorithms accurately recover the stops and moves of the user.

## How to install?
You can download the source and use android studio to build the .apk and install it to your Android device, or you can install the pre-built .apk I have provided.

[**Pre-built .apk**](https://github.com/lukehb/137-GPS-Tracker/releases)

### How to install - using the pre-built .apk?
+ **[Simplest way]** Using your Android device [download the .apk](https://github.com/lukehb/137-GPS-Tracker/releases), then go to your downloads folder tap on the .apk and install it.
+ **Or** [Download the .apk](https://github.com/lukehb/137-GPS-Tracker/releases) to your computer and run ```adb install gps_tracker.apk```.
+ **Or** [download the .apk](https://github.com/lukehb/137-GPS-Tracker/releases) to your computer, then transfer it onto the device, then install an [.apk installer](https://play.google.com/store/search?q=apk%20installer&hl=en) to your device and use that to install it.

## Where are the recorded trails stored and how do I get them?
They are stored on the root of the device under a folder called "trails". To collect the trails plug your device into your computer, then change it to file transfer mode, and then finally copy the files to your computer.
