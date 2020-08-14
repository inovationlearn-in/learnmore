#get ready



<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="match_parent"
    tools:context="MainActivity">
    
    <View
        android:layout_width="1dp"
        android:layout_height="match_parent"
        android:layout_alignRight="@id/reset"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="25dp"
        android:layout_marginBottom="130dp"
         android:background="@android:color/darker_gray" />
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">
      <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <TextView
                android:id="@+id/display"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_margin="32dp"
                android:layout_weight="1"
                android:text="TEAM A"
                android:textColor="#616161"
                android:textSize="14sp" />
            <TextView
                android:id="@+id/display1"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_marginTop="32dp"
                android:layout_marginLeft="32dp"
                android:layout_weight="1"
                android:text="TEAM B"
                android:textColor="#616161"
                android:textSize="14sp" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <TextView
                android:id="@+id/team_a_score"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginLeft="55dp"
                android:layout_weight="1"
                android:text="0"
                android:textColor="#000000"
                android:textSize="56sp" />
            <TextView
                android:id="@+id/team_b_score"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginLeft="55dp"
                android:layout_weight="1"
                android:text="0"
                android:textColor="#000000"
                android:textSize="56sp" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <Button
                android:id="@+id/increase3"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="yes"
                android:text="+3" />
            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="yes1"
                android:text="+3" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <Button
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="no"
                android:text="+2" />
            <Button
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="no1"
                android:text="+2" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <Button
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="don"
                android:text="FREE POINT" />
            <Button
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_margin="16dp"
                android:layout_weight="1"
                android:onClick="don1"
                android:text="FREE POINT" />
        </LinearLayout>
    </LinearLayout>
    <Button
        android:id="@+id/reset"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:onClick="reset"
        android:layout_marginBottom="45dp"
        android:text="RESET" />
</RelativeLayout>*/
