SpeechRecognitionPlugin
=======================
Cordova plugin for SpeechRecognizer


This is an extension of https://github.com/macdonst/SpeechRecognitionPlugin 

There were bugs in this plugin for  Android Java which has been fixed in this version.

Following issues are fixed  in Android:-

1. SpeechRecognizer object was not destroyed which was causing memory leakage.
2. Meaningful errors are sent back from Java.
3. Begin speech event is triggered correctly for listening.

No changes has been done to ios and it should work as described in the extension.

This has been tested using Ionic 2 application.

To install the plugin use 

cordova plugin add https://github.com/vijtad/SpeechRecognizer

