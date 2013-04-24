RelativeLayout Report

1. RelativeLayoutPractice for 1
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="20dp"
    tools:context=".MainActivity" >

    <Button
        android:id="@+id/b1"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignParentLeft="true"
        android:layout_alignParentTop="true"
        android:text="1"/>
    <Button
        android:id="@+id/b2"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/b1"
        android:layout_toRightOf="@+id/b1"
        android:text="2"/>
    <Button
        android:id="@+id/b3"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/b2"
        android:layout_toRightOf="@+id/b2"
        android:text="3"/>
    <Button
        android:id="@+id/b4"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/b1"
        android:layout_below="@+id/b1"
        android:text="4"/>
    <Button
        android:id="@+id/b5"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/b4"
        android:layout_below="@+id/b4"
        android:text="5"/>

    <Button
        android:id="@+id/b7"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignParentLeft="true"
        android:layout_alignParentBottom="true"
        android:text="7"/>

    <Button
        android:id="@+id/b8"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/b7"
        android:layout_toRightOf="@+id/b7"
        android:text="8"/>
 
    <Button
        android:id="@+id/b9"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/b7"
        android:layout_above="@+id/b7"
        android:text="9"/>

    <Button
        android:id="@+id/b6"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:text="6" />

</RelativeLayout>


2. RelativeLayoutPractice for 2
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="20dp"
    tools:context=".MainActivity" >

    <LinearLayout
        android:id="@+id/LinearLayout1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" >

        <Button
            android:id="@+id/b1"
            android:layout_height="wrap_content"
            android:layout_width="0dp"
            android:layout_weight="1"
            android:text="1" />

        <Button
            android:id="@+id/b2"
            android:layout_height="wrap_content"
            android:layout_width="0dp"
            android:layout_weight="1"
            android:text="2" />

        <Button
            android:id="@+id/b3"
            android:layout_height="wrap_content"
            android:layout_width="0dp"
            android:layout_weight="1"
            android:text="3" />
    </LinearLayout>

    <LinearLayout
		android:id="@+id/LinearLayout2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@+id/LinearLayout1" >

        <Button
            android:id="@+id/b4"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="4" />
        <LinearLayout
            android:id="@+id/LinearLayout3"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="3"
            android:orientation="vertical" >

            <Button
                android:id="@+id/b5"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="5" />
            <Button
                android:id="@+id/b6"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="6" />
            
        </LinearLayout>
    </LinearLayout>
</RelativeLayout>
