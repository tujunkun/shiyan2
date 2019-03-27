代码:



    <Button
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="red"
        android:textSize="100dp"
        android:background="#F32121"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:gravity="center"
        android:text="orange"
        android:textSize="100dp"
        android:background="#FF5722"
        app:layout_constraintEnd_toStartOf="@+id/textView3"
        app:layout_constraintStart_toEndOf="@+id/textView"
        app:layout_constraintTop_toTopOf="parent" />
    <Button
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="yellow"
        android:textSize="100dp"
        android:background="#FFC107"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        />

    <Button
        android:id="@+id/textView4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="150dp"
        android:background="#38FF22"
        android:gravity="center"
        android:text="green"
        android:textSize="100dp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        />

    <Button
        android:id="@+id/textView5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="blue"
        android:textSize="100dp"
        android:background="#2259FF"
        app:layout_constraintStart_toEndOf="@id/textView4"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@id/textView6"
        />

    <Button
        android:id="@+id/textView6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginRight="150dp"
        android:background="#6422FF"
        android:gravity="center"
        android:text="indigo"
        android:textSize="100dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
         />
    <Button
        android:id="@+id/textView7"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="violet"
        android:textSize="100dp"
        android:background="#FF22F4"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />



    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">
    <Button
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:text="one,one" />
    <Button
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:text="one,two"/>
    <Button
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:text="one,three"/>
    <Button
        android:layout_width="0dp"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:text="one,four"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="two,one"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="two,two"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="two,three"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="two,four"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="three,one"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="three,two"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="three,three"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="three,four"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1">
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="four,one"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="four,two"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="four,three"/>
        <Button
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:text="four,four"/>
    </LinearLayout>





<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:stretchColumns="*"
    >
    <TableRow>
        <TextView
            android:text="open..."
            android:textSize="30dp"
            android:padding="5dp"/>
     <TextView
         android:text="ctrl-O"
         android:gravity="right"
         android:textSize="30dp"
         android:padding="5dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:text="Save..."
            android:textSize="30dp"
            android:padding="5dp"/>
        <TextView
            android:text="ctrl-s"
            android:textSize="30dp"
            android:gravity="right"
            android:padding="5dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:text="Save as..."
            android:textSize="30dp"
            android:padding="5dp"/>
        <TextView
            android:text="ctrl-shift-s"
            android:textSize="30dp"
            android:gravity="right"
            android:padding="5dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:text="Import..."
            android:textSize="30dp"
            android:padding="5dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:text="Export"
            android:textSize="30dp"
            android:padding="5dp"/>
        <TextView
            android:text="ctrl-E"
            android:textSize="30dp"
            android:padding="5dp"
            android:gravity="right"/>
    </TableRow>
    <TableRow>
        <TextView
            android:text="Quit"
            android:textSize="30dp"
            android:padding="5dp"/>
    </TableRow>
</TableLayout>




![image](https://github.com/tujunkun/shiyan2/blob/master/linearLayout.png)



![image](https://github.com/tujunkun/shiyan2/blob/master/constraintLayout.png)





![image](https://github.com/tujunkun/shiyan2/blob/master/tableLayout.png)
