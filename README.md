# API Vimeo js

```js
var playVimeo = $('.js-play-vimeo');
var Player = new Vimeo.Player($selector, options);

// Button play for Vimeo
playVimeo.click(function(event) {
  event.preventDefault();
  Player.play();
});
```

Play
```
Player.on('play', function() {
  console.log('Played the video!');
});
```

Pause
```
Player.on('pause', function() {
  console.log('Pause the video!');
});
```

📌 View repository Javascript — [GitHub](https://github.com/vimeo/player.js)

📌 View documentation developer — [Developer vimeo](https://developer.vimeo.com/)
 
