FrameLayoutPractice

1. Report for Practice1
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/FrameLayout1"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity" >

   <ImageView
        android:layout_width="72dp"
        android:layout_height="72dp"
        android:background="@drawable/ic_launcher" />
    
    <ImageView
        android:layout_width="72dp"
        android:layout_height="72dp"
        android:layout_gravity="right"
        android:background="@drawable/ic_launcher" />
    
    <ImageView
        android:layout_width="72dp"
        android:layout_height="72dp"
        android:layout_gravity="center"
        android:background="@drawable/ic_launcher" />
    
    <ImageView
        android:layout_width="72dp"
        android:layout_height="72dp"
        android:layout_gravity="bottom"
        android:background="@drawable/ic_launcher" />
    
    <ImageView
        android:layout_width="72dp"
        android:layout_height="72dp"
        android:layout_gravity="right|bottom"
        android:background="@drawable/ic_launcher" />
</FrameLayout>

2. Report for Practice2
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:gravity="center_horizontal"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="20dp"
    tools:context=".MainActivity">
    <FrameLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">
   
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:src="@drawable/ic_launcher"/>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center_vertical"
            android:text="hello_world!My name is Android"/>
    </FrameLayout>
    <FrameLayout
        android:layout_width="60dp"
        android:layout_height="60dp">
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@drawable/ic_launcher"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="top"
            android:layout_marginLeft="5dp"
            android:layout_marginTop="5dp"
            android:src="@drawable/ic_launcher"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="top"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:src="@drawable/ic_launcher"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="top"
            android:layout_marginLeft="15dp"
            android:layout_marginTop="15dp"
            android:src="@drawable/ic_launcher"/>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="top"
            android:layout_marginLeft="20dp"
            android:layout_marginTop="20dp"
            android:src="@drawable/ic_launcher"/>
    </FrameLayout>

    <FrameLayout
        android:layout_width="match_parent"
        android:layout_height="100dp">
	    <FrameLayout
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:background="@drawable/shape"
	        android:layout_gravity="left"
	        android:padding="20dp"
	        android:layout_marginLeft="20dp"
	        android:layout_marginTop="20dp">
	        <TextView 
	            android:layout_width="match_parent"
	            android:layout_height="match_parent"
	            android:text="hogehoge"/>
        </FrameLayout>
        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@drawable/ic_launcher"/>
    </FrameLayout>
</LinearLayout>
