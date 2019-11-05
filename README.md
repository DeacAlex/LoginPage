# LoginPage
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">


    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/search"
        android:layout_gravity="center"
        android:layout_marginTop="90dp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="MyLoginApp"
        android:layout_gravity="center"
        android:layout_marginTop="20dp"
        android:textSize="40dp"
        android:textStyle="bold"
/>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <ImageView
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:src="@drawable/login"
            android:layout_marginLeft="30dp"/>

        <EditText
            android:layout_width="200dp"
            android:layout_height="wrap_content"
            android:hint="Username"/>

    </LinearLayout>
    <LinearLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="horizontal">

<ImageView
    android:layout_width="48dp"
    android:layout_height="48dp"
    android:src="@drawable/key"
    android:layout_marginTop="20dp"
    android:layout_marginLeft="30dp"/>
    <EditText
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:hint="Password"/>

    </LinearLayout>
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginTop="40dp"
        android:text="Login"
        />
</LinearLayout>
