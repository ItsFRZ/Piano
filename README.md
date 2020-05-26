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










```

  Copyright [2020] [Faraz Sheikh]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

```
