# jquery.audioplayer.js

This plugin focus on play audio on all browser, including iPad.
```
AudioPlayer('http://example.org/sound').play();

// or:

new AudioPlayer('http://example.org/sound').play();

// or:

var player=new AudioPlayer('http://example.org/sound');

var yourFunction=function(){
    // we have to preload audio in iPad in order to play it once needed.
    player.play();
}

```
Demo: https://jsfiddle.net/stupidong/to-do-later/

Enjoy it!

That's all folks!
