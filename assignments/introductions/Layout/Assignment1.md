LayoutAssignment for 1

<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity" >

    <EditText
        android:id="@+id/editText1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:ems="10" >
        <requestFocus />
    </EditText>
    <LinearLayout
        android:id="@+id/line1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"> 
    	<Button
	        android:id="@+id/b1"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="1" />
        <Button
	        android:id="@+id/b2"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="2" />
        <Button
	        android:id="@+id/b3"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="3" />
        <Button
	        android:id="@+id/b4"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="4" />
        <Button
	        android:id="@+id/b5"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="5" />
    </LinearLayout>
    <LinearLayout
        android:id="@+id/line2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"> 
    	<Button
	        android:id="@+id/b6"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="6" />
        <Button
	        android:id="@+id/b7"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="7" />
        <Button
	        android:id="@+id/b8"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="8" />
        <Button
	        android:id="@+id/b9"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="9" />
        <Button
	        android:id="@+id/b0"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
                android:layout_weight="1"
	        android:text="0" />
        
    </LinearLayout>
    <LinearLayout
        android:id="@+id/line3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"> 

    	<Button
    	    android:id="@+id/bplus"
    	    android:layout_width="match_parent"
    	    android:layout_height="wrap_content"
    	    android:layout_weight="1"
    	    android:text="+" />

        <Button
            android:id="@+id/bminus"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="-" />

        <Button
	        android:id="@+id/bequal"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="=" />
        <Button
	        android:id="@+id/bclear"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="C" />
        <Button
	        android:id="@+id/bmultiply"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="*" />
        <Button
	        android:id="@+id/bdivide"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="/" />
        <Button
	        android:id="@+id/bdot"
	        android:layout_width="match_parent"
	        android:layout_height="wrap_content"
	        android:layout_weight="1"
	        android:text="." />
    </LinearLayout>

</LinearLayout>
