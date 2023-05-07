#Layout Loading Screen
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="500dp"
        android:layout_height="200dp"
        app:srcCompat="@drawable/img" />

    <TextView
        android:id="@+id/judul"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="MARKO Store"
        android:textAlignment="center"
        android:layout_marginTop="200dp"
        android:textSize="30sp"
        android:textStyle="bold"
        />

    <TextView
        android:id="@+id/judul2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Fashion Lifestye"
        android:layout_below="@id/judul"
        android:textAlignment="center"
        android:textSize="25sp"/>

</RelativeLayout>

![1](https://user-images.githubusercontent.com/101499377/236686815-8d37a7f6-4353-4914-a1e6-cb850b6949ed.png)

    
