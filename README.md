# Guide to get started with MycroftAI for PM tools

## Install for android studio

1. Install Android Studio 
   - goto developer.android.com/studio and click Download Android Studio
   - select virtual device for testing and install
   - Open Android studio and download components (if first time using Android studio)
2. Install Mycroft into android studio
   - goto mycroft.ai/get-started and click download for Android to access the github repo
   - documentation here: https://mycroft-ai.gitbook.io/docs/using-mycroft-ai/get-mycroft/android
   - goto the Mycroft-Android repo (github.com/MycroftAI/Mycroft-Android)
   - Get the clone link from the Code dropdown
   - do a > git clone <path_to_repo> to clone the repo locally
   - do the same for MycroftCore-Android
   - Open Android Studio and import project into 
3. Install missing packages
   - There might be some warnings about missing packages, if so, open the SDK Pacakage manager and install the missing API versions. At the time of writing, it was API 29 and 28
4. Create Virtual device to test deployments
   - Click Virtual Device Manager and select a device to create. At the time of writing, Nexus 6 with API 29 were used. 
   - After the component is installed, it should show up as a virtual device in your list of devices. 
   - Launch the device by clicking the play button
5. Build the MycroftCore-Android project
   - Click Build > Rebuild project

## Install via Linux VM on Windows

1. 
