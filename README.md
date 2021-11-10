## TIDAL - Discord Rich Presence plug-in  (UNOFFICIAL)


Unofficial plug in to obtain Discord Rich Presence.

Feel free to report any bugs or make suggestions.

<br>

**If you like the project and want to buy me a glass of milk :)**

[Support me using paypal](https://www.paypal.me/KharonIX)
## Example Screenshot

When playing a song with hifi audio quality.

![alt text](./assets/music_playing.PNG)
![alt text](./assets/tidal_music_playing.PNG)

When playing a song with master audio quality.

![alt text](./assets/master_playing.PNG)
![alt text](./assets/tidal_master_playing.PNG)

or you have paused playback

![alt text](./assets/music_paused.PNG)



## Instructions
The new version doesn't require connection with last-fm, 'cause I reversed engineered TIDAL API,  get the data from the window name of the app.

1.  Download the latest release from [here](https://github.com/rares9301/tidal_rich_presence_master/releases)
(windows and osx are supported).

2.  Run the binary, enjoy.

3.  *Optional*: Place the exe in windows start-up folder to start when computer starts. For OSX select that option from by right clicking the app on taskbar.


The program registers an icon on the taskbar, where you can see the song playing and temporary disable *rich presence*.

![alt text](./assets/taskbar.jpg) ![alt text](./assets/down_there.PNG)

P.S. Remember to make sure you have Game Activity enabled!

![example of Game Activity tab inside of Discord Settings](./assets/activity_status.PNG)


## Build Instructions

To build the executable you'll need either msvc on windows or clang on osx. For windows I had problems with gcc either conflicting with discord lib on (debug) and http not have <mutex>.


### Disclaimer: This project is Unofficial and it's not published from TIDAL.com.

Kudos to:
+ https://github.com/rares9301
for their awesome work.



> ### “I don’t like expending more effort than I have to.” -Ayanokouji Kiyotaka
