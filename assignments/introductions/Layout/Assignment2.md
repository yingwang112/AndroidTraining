LayoutAssignment for 2

<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity" >

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#DAA520"
        android:padding="4dp">
        <ImageView
            android:id="@+id/imageView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginRight="4dp"
            android:background="#FFFFFF"
            android:src="@drawable/ic_launcher"/>
        <LinearLayout
            android:id="@+id/linearLayout"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_alignTop="@+id/imageView"
            android:layout_alignBottom="@+id/imageView"
            android:layout_toRightOf="@+id/imageView">
                <TextView
                    android:id="@+id/textView1"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:background="#ff9900" />
                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:background="#ffffcc" />
        </LinearLayout>
    </RelativeLayout>
</FrameLayout>
