Assignment Report for 1.4
------

以下に、課題の回答を記入してください。

Android の基礎知識
======

4. `adb`コマンドを使って、下記の項目を実行してください（課題のファイルに、実行したコマンドを記録しておいてください）。

a. adb push filename /sdcard/...

90201687n:‾ ying.wang$ adb devices
List of devices attached 
015d4906073ffc19	device

90201687n:‾ ying.wang$ adb push wyfile01.txt /sdcard/
0 KB/s (11 bytes in 0.013s)

90201687n:‾ ying.wang$ adb shell
shell@android:/ $ ls sdcard/                                                   
Alarms/         Download/       Notifications/  Ringtones/      
Android/        Movies/         Pictures/       wyfile01.txt    
DCIM/           Music/          Podcasts/       

b. adb pull /sdcard/.../ local/...
90201687n:‾ ying.wang$ adb pull sdcard/bugreports/bugreport-2013-04-22-11-11-30.txt ./
3218 KB/s (4269724 bytes in 1.295s)

90201687n:‾ ying.wang$ ls
AndroidTraining				Public
AndroidTraining_bk			Sample02pn.apk
Desktop					abc.md
Documents				bugreport-2013-04-22-11-11-30.txt

c. adb install *.apk
90201687n:‾ ying.wang$ adb install Studyapk.apk 
1268 KB/s (196145 bytes in 0.150s)
	pkg: /data/local/tmp/Studyapk.apk
Success

d. adb uninstall packageName
90201687n:‾ ying.wang$ adb uninstall com.example.study001
Success

