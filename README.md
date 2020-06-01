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

# In activity
    public void play(View v) {
        String tag = v.getTag().toString();
        mSoundPool.play(map.get(tag), 1, 1, 1, 0, 1);
    }
  
