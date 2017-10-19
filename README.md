# cordova_erreur_license

* What went wrong:
A problem occurred configuring root project 'android'.
> You have not accepted the license agreements of the following SDK components:
  [Android SDK Platform 26].
  Before building your project, you need to accept the license agreements and complete the installation of the missing components using the Android Studio SDK Manager.
  Alternatively, to learn how to transfer the license agreements from one workstation to another, go to http://d.android.com/r/studio-ui/export-licenses.html

Resolution

➜  myApp git:(master) ✗ export ANDROID_HOME=/home/sekour/android-sdk-linux/                                       
➜  myApp git:(master) ✗ export PATH=${PATH}:/home/sekour/android-sdk-linux/platform-tools:/home/sekour/android-sdk-linux/tools
➜  myApp git:(master) ✗ source ~/.bash_profile  
