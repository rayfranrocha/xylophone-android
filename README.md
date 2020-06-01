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
<pre><code>
    < Button
        android:id="@+id/a_key"
        ...
        android:onClick="play"
        android:tag="A"/>
</code></pre>
  
