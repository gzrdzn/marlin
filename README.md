I need to learn about this GitHub CLI: [install](https://github.com/cli/cli#installation), [docs](https://cli.github.com/).
Things are getting more complex. :|

# marlin
[Marlin](https://pixar.fandom.com/wiki/Marlin) is one of the main characters of "Finding Nemo". He is always trying to make sure Nemo is safe and becoming the best fish he can be. Hence, Marlin is always checking what works and what isn't working with Nemo.

# using [maestro](https://maestro.dev/)
Learn more [about Maestro here](https://docs.maestro.dev/). Maestro will need a mobile app to test and, for this example, I am using the Android Emulator.

## install emulator with android studio
Learn to [install the Emulator for Android Apps](https://developer.android.com/studio/run/emulator).  
Learn to [use the Emulator](https://docs.maestro.dev/getting-started/build-and-install-your-app/android).

## run test with maestro
Learn and run [sample test flow](https://docs.maestro.dev/getting-started/run-a-sample-flow).

When you run command `adb install sample.apk` and see this issue `command not found: adb`, then follow these instructions and download the [Android SDK Platform-Tools](https://developer.android.com/tools/releases/platform-tools) or follow these [instructions via SDK Manager](https://developer.android.com/studio/intro/update#sdk-manager). Take note, the location of the SDK Manager may have changed (like my version has the SDK Manager under the "Languages & Frameworks" section within Settings).

Make sure to select checkbox to install the missing "Android SDK Command Line Tools".
<img width="682" height="82" alt="android_tools_command_tools_screenshot" src="https://github.com/user-attachments/assets/d3fe7841-1047-458c-8e1a-b67bbd160a53" />


# purpose
Initial purpose is to test the "luckyfin" app.

# hope
Eventually, this is to test my application that helps the blind navigate the ocean.

# tutorials
## videos
* https://youtu.be/4hRdXBAgeaA?si=qOLxBO0gizIh__yL

# notes
## considerations
* [Espresso](https://developer.android.com/training/testing/espresso) | [Intro to Espresso](https://www.youtube.com/watch?v=lZ8Yx0Azx_A&list=PLuSTZ2_3-OB6CDAK_3KBRwr7xk7rzjW92) | this is the suggested tool by Android Developers for Android Developers (which means you know the codebase similar to unit tests).
## online references
* [reddit](https://www.reddit.com/r/softwaretesting/comments/1g5rder/automated_native_ios_android_app_testing_what_to/)
