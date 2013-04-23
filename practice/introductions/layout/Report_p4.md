Report for ScrollView Practice
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/ScrollView1"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical" >

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="hello_world!My name is Android.This app is written in Java,and running on Dalvik VM,not Sun VM.Nice to see you!Have fun:)"
            android:textSize="30dp" />

        . . . . . . 

	<TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="hello_world!My name is Android.This app is written in Java,and running on Dalvik VM,not Sun VM.Nice to see you!Have fun:)"
            android:textSize="30dp" />
        <Button
            android:id="@+id/button1"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Button" />

    </LinearLayout>

</ScrollView
