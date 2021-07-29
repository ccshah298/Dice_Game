# Dice_Game
Dice examples game

Android Studio (Recommended)
(These instructions were tested with Android Studio version 2.2.2, 2.2.3, 2.3, and 2.3.2)

Open Android Studio and select File->Open... or from the Android Launcher select Import project (Eclipse ADT, Gradle, etc.) and navigate to the root directory of your project.
Select the directory or drill in and select the file build.gradle in the cloned repo.
Click 'OK' to open the the project in Android Studio.
A Gradle sync should start, but you can force a sync and build the 'app' module as needed.
Gradle (command line)
Build the APK: ./gradlew build
Eclipse
Download the latest Android SDK from Maven Central
Note: We publish both an AAR and a JAR; you may use whichever is more convenient based on your infrastructure and needs.
Running the Sample App
Connect an Android device to your development machine.

Android Studio
Select Run -> Run 'app' (or Debug 'app') from the menu bar
Select the device you wish to run the app on and click 'OK'
Gradle
Install the debug APK on your device ./gradlew installDebug
Start the APK: <path to Android SDK>/platform-tools/adb -d shell am start io.keen.client.android.example/io.keen.client.android.example.MyActivity
