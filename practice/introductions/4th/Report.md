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
90201687n:sdk ying.wang$ ./platform-tools/adb devices
List of devices attached 
emulator-5554	device

* adb shell
90201687n:‾ ying.wang$ ./Downloads/adt-bundle-mac-x86_64-20130219/sdk/platform-tools/adb shell
root@android:/ #
root@android:/ # su shell
root@android:/ $ 

3. (実習)adb shellコマンドを使って、Android 内のファイルシステムにアクセスし、下記の項目を確認してください。

root@android:/ $ cd /data/data/
root@android:/data/data $ ls
opendir failed, Permission denied

*I don't know why*
root@android:/ $ cd sdcard/                                                    
sh: cd: /sdcard: Permission denied

root@android:/ $ su 
root@android:/ # cd sdcard/
root@android:/sdcard # ls
root@android:/sdcard # 






















































