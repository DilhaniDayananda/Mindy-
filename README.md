# Mindy-
Small quiz application
Dilhani Dayananda


Itz my name

******interface 1******

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.swan.mindyrush2.MainActivity">

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:background="@android:color/holo_blue_light"
        android:orientation="vertical"
        app:layout_constraintTop_toTopOf="parent"
        android:layout_marginTop="0dp"
        app:layout_constraintBottom_toBottomOf="parent"
        android:layout_marginBottom="0dp"
        android:layout_marginLeft="0dp"
        app:layout_constraintLeft_toLeftOf="parent"
        android:layout_marginRight="0dp"
        app:layout_constraintVertical_bias="0.4"
        app:layout_constraintRight_toRightOf="parent">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="100dp"
                android:layout_height="50dp"
                android:layout_marginLeft="200dp"
                android:text="Score :"
                android:textSize="30sp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/textView7"
                android:layout_width="50dp"
                android:layout_height="50dp"
                android:text="3"
                android:textSize="30sp"
                android:textStyle="bold" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="150dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="60dp"
                android:layout_marginRight="60dp"
                android:gravity="center_vertical"
                android:orientation="horizontal"
                android:textAlignment="center">

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="1"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="+"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="3"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="="
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:adjustViewBounds="false"
                    android:textAlignment="center"
                    app:srcCompat="@android:drawable/ic_menu_help" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="25dp"
                android:layout_marginRight="25dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/button6"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="4"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button5"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="5"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="6"
                    android:textSize="30sp" />
            </LinearLayout>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="150dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="60dp"
                android:layout_marginRight="60dp"
                android:gravity="center_vertical"
                android:orientation="horizontal"
                android:textAlignment="center">

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="8"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="/"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="2"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="="
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:adjustViewBounds="false"
                    android:textAlignment="center"
                    app:srcCompat="@android:drawable/ic_menu_help" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="25dp"
                android:layout_marginRight="25dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/button6"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="7"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button5"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="4"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="3"
                    android:textSize="30sp" />
            </LinearLayout>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="150dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="60dp"
                android:layout_marginRight="60dp"
                android:gravity="center_vertical"
                android:orientation="horizontal"
                android:textAlignment="center">

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="10"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="*"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="3"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:text="="
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:adjustViewBounds="false"
                    android:textAlignment="center"
                    app:srcCompat="@android:drawable/ic_menu_help" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="25dp"
                android:layout_marginRight="25dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/button6"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="13"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button5"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="3"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="20dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="30"
                    android:textSize="30sp" />
            </LinearLayout>
        </LinearLayout>

    </LinearLayout>
</android.support.constraint.ConstraintLayout>





















******interface 2******



<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.swan.mindyrush2.Main2Activity">

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginBottom="0dp"
        android:layout_marginLeft="0dp"
        android:layout_marginRight="0dp"
        android:layout_marginTop="0dp"
        android:background="@android:color/holo_blue_light"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.4">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="100dp"
                android:layout_height="50dp"
                android:layout_marginLeft="200dp"
                android:text="Score :"
                android:textSize="30sp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/textView7"
                android:layout_width="50dp"
                android:layout_height="50dp"
                android:text="5"
                android:textSize="30sp"
                android:textStyle="bold" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="30dp"
            android:orientation="vertical"></LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:layout_marginLeft="30dp"
            android:layout_marginRight="30dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="20dp"
                android:gravity="center"
                android:orientation="horizontal"
                android:textAlignment="gravity">

                <TextView
                    android:id="@+id/textView10"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:layout_weight="1"
                    android:text="2"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView11"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:layout_weight="1"
                    android:text="*"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="8"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="+"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="3"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="="
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:adjustViewBounds="false"
                    android:textAlignment="center"
                    app:srcCompat="@android:drawable/ic_menu_help" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="25dp"
                android:layout_marginRight="25dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/button2"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="19"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button6"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="16"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="22"
                    android:textSize="30sp" />
            </LinearLayout>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:orientation="vertical"></LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:layout_marginLeft="30dp"
            android:layout_marginRight="30dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="20dp"
                android:gravity="center"
                android:orientation="horizontal"
                android:textAlignment="gravity">

                <TextView
                    android:id="@+id/textView10"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:layout_weight="1"
                    android:text="50"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView11"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:layout_weight="1"
                    android:text="/"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView4"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="2"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView3"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="-"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView2"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="8"
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <TextView
                    android:id="@+id/textView"
                    android:layout_width="40dp"
                    android:layout_height="50dp"
                    android:text="="
                    android:textAlignment="center"
                    android:textSize="30sp" />

                <ImageView
                    android:id="@+id/imageView"
                    android:layout_width="50dp"
                    android:layout_height="50dp"
                    android:adjustViewBounds="false"
                    android:textAlignment="center"
                    app:srcCompat="@android:drawable/ic_menu_help" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="25dp"
                android:layout_marginRight="25dp"
                android:orientation="horizontal">

                <Button
                    android:id="@+id/button2"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="25"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button6"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="17"
                    android:textSize="30sp" />

                <Button
                    android:id="@+id/button4"
                    android:layout_width="10dp"
                    android:layout_height="wrap_content"
                    android:layout_weight="1"
                    android:text="15"
                    android:textSize="30sp" />
            </LinearLayout>
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="30dp"
            android:orientation="vertical"></LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="150dp"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/imageView3"
                android:layout_width="match_parent"
                android:layout_height="130dp"
                app:srcCompat="@mipmap/ic_launcher" />
        </LinearLayout>

    </LinearLayout>
</android.support.constraint.ConstraintLayout>







******interface 3******

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/background_light"
    tools:context="com.example.swan.mindyrush2.Main3Activity">

    <LinearLayout
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:background="@android:color/background_light"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.401"
        tools:layout_constraintRight_creator="1"
        tools:layout_constraintLeft_creator="1">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="match_parent"
                android:layout_height="100dp"
                app:srcCompat="@android:drawable/star_big_on" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:orientation="horizontal"
            android:weightSum="1">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="wrap_content"
                android:layout_height="50dp"
                android:layout_weight="0.41"
                android:text="Your Score is "
                android:textAlignment="textEnd"
                android:textColorLink="@color/colorPrimaryDark"
                android:textSize="30sp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/textView5"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_weight="0.41"
                android:text="5 ."
                android:textSize="30sp"
                android:textStyle="bold" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:orientation="vertical">

            <TextView
                android:id="@+id/textView8"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Thanks for playing our game."
                android:textAlignment="center"
                android:textSize="24sp"
                android:textStyle="italic" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="250dp"
            android:layout_height="match_parent"
            android:layout_marginLeft="70dp"
            android:gravity="center_vertical"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button"
                android:layout_width="40dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Try Again" />

            <ImageButton
                android:id="@+id/imageButton"
                android:layout_width="10dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                app:srcCompat="@android:drawable/btn_dialog" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="110dp"
            android:orientation="vertical">

            <RatingBar
                android:id="@+id/ratingBar"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:layout_marginLeft="70dp"
                android:layout_marginTop="40dp" />
        </LinearLayout>

    </LinearLayout>
</android.support.constraint.ConstraintLayout>


