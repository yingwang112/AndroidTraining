LayoutAssignment for 3

<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="#eeeeee"
    tools:context=".MainActivity" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:background="#D3D3D3"
        android:padding="4dp"
        android:layout_margin="2dp">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_marginRight="70dp"
            android:layout_weight="3"
            android:orientation="vertical" >

            <TextView
                android:id="@+id/textViewName"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="right"
                android:layout_marginTop="10dp"
                android:layout_marginBottom="10dp"
                android:textSize="15sp"
                android:text="ドロイド君の画像ファイル"/>
            <TextView
                android:id="@+id/textViewPath"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="right"
                android:textSize="10sp"
                android:textColor="#708090"
                android:text="res/ic_launcher.png"/>
        </LinearLayout>
        <ImageView
            android:id="@+id/ImageView"
            android:layout_width="wrap_content"
            android:layout_height="80dp"
            android:background="#ffffff"
            android:src="@drawable/ic_launcher"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="5dp"
        android:padding="2dp"
        android:background="#dddddd"
        android:orientation="horizontal">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="xhdpi"
            android:textSize="10sp"
            android:textColor="#708090"/>
        <View
            android:layout_width="match_parent"
            android:layout_height="1dp"
            android:layout_weight="1"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="12,516 bytes"
            android:textColor="#708090"
            android:textSize="10sp" />
    </LinearLayout>
</LinearLayout>
