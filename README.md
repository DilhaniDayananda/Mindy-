-----home interface-----


Activity_home.xml

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/holo_purple"
    tools:context="com.example.swan.mindyrush2.Home">


    <ImageButton
        android:id="@+id/ImageButton"
        android:layout_width="78dp"
        android:layout_height="97dp"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_marginBottom="8dp"
        android:layout_marginRight="171dp"
        android:layout_marginTop="8dp"
        android:layout_weight="1.68"
        android:src="@mipmap/start"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.366" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="295dp"
        android:layout_height="57dp"
        android:layout_below="@+id/ImageButton"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:text="Press the image to start your quiz"
        android:textAppearance="?android:attr/textAppearanceSmall"
        android:textColorLink="@color/colorAccent"
        android:textSize="18sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.506"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.598" />


</android.support.constraint.ConstraintLayout>





</android.support.constraint.ConstraintLayout>





