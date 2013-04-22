Practice Report for 1.4
1. (実習)Android SDK 内の、下記の 2 つのディレクトリにあるコマンドを列挙してください。
* sdk/tools/
android
apkbuilder
ddms
dmtracedump
draw9patch
emulator
emulator-arm
emulator-mips
emulator-x86
emulator64-arm
emulator64-mips
emulator64-x86
etc1tool
hierarchyviewer
hprof-conv
jobb
lint
mksdcard
monitor
monkeyrunner
proguard
traceview
uiautomator
zipalign

* sdk/platform-tools
aapt
adb
aidl
api
dexdump
dx
fastboot
llvm-rs-cc

2. (実習)上記のディレクトリにパスを通し、下記のコマンドを実行してください。
* adb devices
90201687n:‾ ying.wang$ adb devices
List of devices attached 
015d4906073ffc19	device

* adb shell
90201687n:‾ ying.wang$ adb shell
shell@android:/ $ 

3. (実習)adb shellコマンドを使って、Android 内のファイルシステムにアクセスし、下記の項目を確認してください。
90201687n:‾ ying.wang$ adb shell
shell@android:/ $ cd  /data/data/
shell@android:/data/data $ ls
opendir failed, Permission denied
255|shell@android:/data/data $ 

shell@android:/ $ cd sdcard/Android/data/com.                                  
com.android.providers.media/            com.google.android.gallery3d/     
com.google.android.apps.currents/       com.google.android.music/         
com.google.android.apps.magazines/      com.google.android.videos/        
com.google.android.apps.maps/           com.google.android.youtube/  



















































