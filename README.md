2048-chemistry-android
============

This is the android port of the 2048 Chemistry http://2048alphabet.com/chemistry/ game made by Misho M. Petkovic https://plus.google.com/u/0/+MishoMPetkovic/ 

It's nothing fancy, just a webview that loads the localy stored html files of the original game. 
App require full internet access permissions and with a quick access icon for my smartphone.

Feel free to contribute with pull requests to the original project by Gabriele or to this one if you have any android 
specific improvements in mind.

Play store link: https://play.google.com/store/apps/details?id=com.Misho.Chemistry

##Building

If you want to build from source just do 

    git clone https://github.com/uberspot/2048-android.git
    cd 2048-chemistry-android/
    git submodule update --recursive 

##Using
Please change AdMob Adunit ID to your AdunitID ads:adUnitId="ca-app-pub-XXX"

https://github.com/mishop/2048-chemistry-android/blob/master/res/layout/activity_main.xml#L26


##Thanks
Gabriele Cirulli (Original Game) https://github.com/gabrielecirulli/2048 

Paul Sarbinowski (Android Port webview) https://github.com/uberspot/2048-android

##License

2048-android is licensed under the [MIT license.](https://github.com/mishop/2048-chemistry-android/blob/master/LICENSE)
