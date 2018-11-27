# OBS-Youtube-Player
Designed for OBS Browser source to display/play a song/playlist fully automaticly with customs params.

## Usage : (copy Youtube link at "watch?v=XXXXX" or "watch?v=XXXXX&list=XXXXX")
exemple : obs-youtube-player.html?watch?v=XXXXX&list=XXXXX&volume=55&w=800&h=600&hide=true

## Features :
  **volume :** Volume of the video player : &volume=VALUE (0 to 100, default is 45)\
  **w:** Width of the video player : &width=VALUE (default is 535) \
  **h:** Height of the video player : &height=VALUE (default is 300)\
  **hide:** Hide the video player : &hide=true|false (default is false)\
  **loop:** Loop video/playlist when finished : &loop=true|false (default is true)\
  **random:** Randomize next song on playlist : &random=true|false (default is true)\
  **fondu:** Enable the volume "fondu" on song start & end : &fondu=true|false (default is true)\
  **debug:** Enable debug mode & show info on console : &debug=true|false (default is false)

## Built-in features by defaults :
  autoplay = enabled, 
  Video controls (play,next, etc..) = hidden, 
  Fullscreen button = hidden, 
  Video info = hidden, 
  Loop mode = enabled, 
  Randomize = enabled, 
  Video annotation = disabled, 
  and more....
  
