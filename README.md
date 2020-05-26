# Piano
#### Piano TimePass Application lot of stuff remaining
#### hope you make a cool application by this structure :)

### Contain 8 different sound effects but in low intensity

![Screenshot_20200526-202439_PianoApp](https://user-images.githubusercontent.com/61186175/82917610-454d7580-9f91-11ea-8b8d-3f363a1b4873.jpg)

```

        if(Build.VERSION.SDK_INT >= Build.VERSION_CODES.LOLLIPOP) // Checking the version if true soundpool class call 
        {

            soundPool = new SoundPool.Builder().setMaxStreams(5).build();
        }else{
                    soundPool = new SoundPool(5, AudioManager.STREAM_MUSIC,0); //Else soundpool with audio manager call
             }


```

### Then simple make onclick method to call play member function of class Soundpool


```

        Button_Name.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {

                soundPool.play(sound_a,1,1,0,0,1); // Memberfunction call
            }
        });


```

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://stackoverflow.com/users/13288156/itsfrz) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/ItsFRZ/Piano/blob/master/LICENSE) [![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ItsFRZ)

