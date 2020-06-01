# xylophone-android
App example of Xylophone in Android

# classe used
SoundPool - The SoundPool class manages and plays audio resources for applications.

# methods used
load(...)
play(...)

# path of audio files
res/raw/

# to pass parameters by xml button 'onclick', use 'tag'
  <Button
        style="@style/KeyStyle"
        android:id="@+id/a_key"
        android:background="@color/blue"
        android:layout_marginLeft="25dp"
        android:layout_marginRight="25dp"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:onClick="play"
        android:tag="A"/>
