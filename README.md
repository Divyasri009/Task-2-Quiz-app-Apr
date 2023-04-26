<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/teal_200"
    android:padding="24dp"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/total_question"
        android:text="Total Questions "
        android:layout_centerHorizontal="true"
        android:textSize="20dp"/>


    <TextView
        android:id="@+id/question"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_above="@+id/choice_layout"
        android:layout_marginStart="20dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:text="This will be the question"
        android:textAlignment="center"
        android:textColor="@color/white"
        android:textSize="24dp"
        android:textStyle="bold"
        tools:ignore="UnknownId" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/choice_layout"
        android:layout_centerInParent="true"
        android:orientation="vertical">

        <Button
        android:id="@+id/ans_B"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:backgroundTint="@color/white"
        android:minHeight="48dp"
        android:text="Ans B"
        android:textColor="@color/black" />

    <Button
        android:id="@+id/ans_C"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:backgroundTint="@color/white"
        android:text="Ans C"
        android:textColor="@color/black" />

    <Button
        android:id="@+id/ans_D"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:backgroundTint="@color/white"
        android:text="Ans D"
        android:textColor="@color/black" />

    <Button
        android:id="@+id/ans_A"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:backgroundTint="@color/white"
        android:minHeight="48dp"
        android:text="Ans A"
        android:textColor="@color/black" />

    </LinearLayout>


    <Button
        android:id="@+id/submit_btn"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/choice_layout"
        android:layout_marginTop="40dp"
        android:backgroundTint="@color/black"
        android:minHeight="48dp"
        android:text="Submit"/>

</RelativeLayout>
