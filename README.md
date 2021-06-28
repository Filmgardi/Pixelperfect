# Pixelperfect
Pixel perfect helps you design layouts according to the resolution of your users' device

Follow the steps below to implement : 
  ```
	dependencies {
	        implementation 'com.github.Filmgardi:Pixelperfect:Tag'
	}
```

The usage scale is between 1 and 100 and its Dimen ID starts with _wpp
How to use it is as follows :
```
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="@dimen/_wpp100_0"
    android:layout_height="@dimen/_wpp50_0"
    android:layout_marginHorizontal="@dimen/_wpp2_0">

    <TextView
        android:layout_width="@dimen/_wpp75_0"
        android:layout_height="@dimen/_wpp5_8"
        android:layout_marginRight="@dimen/_wpp2_0"
        android:gravity="center"
        android:textColor="@color/black"
        android:textSize="@dimen/_wpp3_6"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
