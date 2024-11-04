<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="horizontal"
    android:padding="16dp">

    <EditText
        android:id="@+id/inputNumber"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter Number"
        android:inputType="text" />

    <Spinner
        android:id="@+id/inputBase"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />

    <Button
        android:id="@+id/convertButton"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Convert" />

    <TextView
        android:id="@+id/outputResult"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:paddingTop="16dp"
        android:textSize="18sp" />
</LinearLayout># -project-2
