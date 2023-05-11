<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation = "vertical"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginTop="48sp"
        android:fontFamily="sans-serif-condensed-medium"
        android:text="@string/unit_converter_3002"
        android:textColor="@color/black"
        android:textSize="40sp" />

    <TextView
        android:id="@+id/Text"
        android:layout_width="234dp"
        android:layout_height="54dp"
        android:layout_gravity="center"
        android:layout_marginStart="20sp"
        android:layout_marginTop="40sp"
        android:layout_marginEnd="20sp"
        android:layout_marginBottom="20sp"
        android:fontFamily="sans-serif-condensed-medium"
        android:text="@string/enter_the_kg_value_below"
        android:textColor="@color/black"
        android:textSize="20sp"
        tools:ignore="TextSizeCheck" />


    <EditText
        android:id="@+id/number"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginStart="20sp"
        android:layout_marginTop="30sp"
        android:layout_marginEnd="20sp"
        android:hint="Value in kg"
        android:inputType="number"
        android:minHeight="48dp"
        android:textColor="@color/black"
        tools:ignore="VisualLintTextFieldSize" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_margin="30sp"
        android:text="@string/convert"/>

    <TextView
        android:id="@+id/text"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/values_in_pounds"
        android:layout_gravity="center"
        android:textSize="20sp"
        android:textColor="@color/black"
        android:layout_marginStart="20sp"
        android:layout_marginBottom="20sp"
        android:layout_marginEnd="20sp"
        android:layout_marginTop="40sp"
        android:fontFamily="sans-serif-condensed-medium"/>


</LinearLayout>
