
<html>
  <head>
    <style>
      * { 
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        background: none;
      }
    </style>
  </head>
  <body>
    <div id="info"></div>
    <div id="player"></div>

    <script async src="https://www.youtube.com/iframe_api"></script>

    <script>
      function info(txt) { return document.querySelector('#info').innerHTML = txt; }

      var url = new URL(window.location.href);
      var songID = url.searchParams.get('watch?v');
      var listID = url.searchParams.get('list');
      var volume = url.searchParams.get('volume') || 45;
      var width = url.searchParams.get('w') || 535;
      var height = url.searchParams.get('h') || 300;

      var hideVideo = false || url.searchParams.get('hide');
      if (hideVideo) { document.querySelector('#player').style.display = 'none'; }

      console.log(`insert : video = ${songID} | list = ${listID}`);

      function onYouTubeIframeAPIReady() {
        var player = new YT.Player('player', {
        width: width,              
        height: height, 

        playerVars: {
          autoplay: 1,        // Auto-play the video on load
          controls: 0,        // Show pause/play buttons in player
          showinfo: 0,        // Hide the video title
          modestbranding: 1,  // Hide the Youtube Logo
          loop: 1,            // Run the video in a loop
          fs: 0,              // Hide the full screen button
          cc_load_policy: 0,  // Hide closed captions
          iv_load_policy: 3,  // Hide the Video Annotations
          autohide: 1         // Hide video controls when playing
        },

        events: {
          'onReady': function() {
            
            // Get/Set volume params
            if (volume !== null) {
              player.setVolume(volume);
            } else {
              info(`Volume not specified, default (${volume}%) is applied, add "&volume=20" at the end of the link to change it.`);
              player.setVolume(volume);
            }

            // Get video type
            if (listID != null) {
              player.cuePlaylist({
                listType: 'playlist',
                list: listID
              });
            } else {
              player.cueVideoById(songID);
            }

          },
          'onStateChange': function (event) {
            switch(event.data){
              case -1:  // Not started
                info('Unable to start playing, the video might be unaivailable or double-check the link you just entered');
                break;
              case 0:   // Stopped
                console.log('Stopped');
                  player.playVideo(); 
                break;
              case 1:   // Playing
                document.querySelector('#info').innerHTML = '';
                console.log('Playing... ');
                onAir();
                break;
              case 2:   // Pause
                console.log('Paused...');
                onAir();
                break;
              case 3:
                console.log("Loading...");
              case 5:   // In queue
                console.log('In queue...');
                  onAir();
                break
              default:
                console.log("default Play");
                onAir();
            }
          }
        }
      });

      function onAir() {
        var state = player.playVideo();
        var loop = player.setLoop(true);
        var shuffle = player.setShuffle(true);
        console.log(`On air ${state.data}, loop:${loop.data}, shuffle:${shuffle.data}`);
      }
    }
    </script>
  </body>
</html>
