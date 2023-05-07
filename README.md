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

# Layout Login

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/container"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    tools:context=".ui.login.LoginActivity">


    <TextView
        android:id="@+id/judul"
        android:layout_width="100dp"
        android:layout_height="37dp"
        android:text="Sign In"
        android:textAlignment="center"
        android:textSize="25sp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="-2dp"
        tools:layout_editor_absoluteY="85dp" />

    <TextView
        android:id="@+id/judul"
        android:layout_width="100dp"
        android:layout_height="20dp"
        android:text="Register"
        android:textAlignment="center"
        android:textSize="15sp"
        android:textStyle="bold"
        tools:layout_editor_absoluteX="272dp"
        tools:layout_editor_absoluteY="16dp" />

    <EditText
        android:id="@+id/username"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="200dp"
        android:hint="@string/prompt_email"
        android:inputType="textEmailAddress"
        android:text="Username Or Email"
        android:selectAllOnFocus="true"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />


    <EditText
        android:id="@+id/password"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:hint="@string/prompt_password"
        android:imeActionLabel="@string/action_sign_in_short"
        android:imeOptions="actionDone"
        android:inputType="textPassword"
        android:selectAllOnFocus="true"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/username" />

    <Button
        android:id="@+id/login"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="start"
        android:layout_marginTop="5dp"
        android:layout_marginBottom="60dp"
        android:enabled="false"
        android:text="@string/action_sign_in"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/password"
        app:layout_constraintVertical_bias="0.2" />

    <ProgressBar
        android:id="@+id/loading"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginTop="64dp"
        android:layout_marginBottom="64dp"
        android:visibility="gone"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/password"
        app:layout_constraintStart_toStartOf="@+id/password"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.3" />

</androidx.constraintlayout.widget.ConstraintLayout>


