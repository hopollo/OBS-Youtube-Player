# OBS-Youtube-Player
Designed for OBS Browser source to display/play a song/playlist fully automaticly with customs params.

# Disclaimer : 
Due to Chrome policy about autoplay (and OBS brower source is a "chrome"), you will have to press play on the first video.

## Usage : add ? at the end of the link and copy Youtube link at "watch?v=XXXXX" or "watch?v=XXXXX&list=XXXXX")
exemple : https://obsyoutubeplayer.netlify.com/?watch?v=lSqnqSSXTUI&list=RDlSqnqSSXTUI&volume=10&random=true&loop=true

## Features :
  **volume :** Volume of the video player : &volume=VALUE (0 to 100, default is 45)\
  **w:** Width of the video player : &width=VALUE (default is 535) \
  **h:** Height of the video player : &height=VALUE (default is 300)\
  **hide:** Hide the video player : &hide=true|false (default is false)\
  **loop:** Loop video/playlist when finished : &loop=true|false (default is true)\
  **random:** Randomize next song on playlist : &random=true|false (default is true)\
  **fondu:** Enable the volume "fondu" on song start & end : &fondu=true|false (default is true)\
  **debug:** Enable debug mode & show info on console : &debug=true|false (default is false)

## Built-in features by default :
  autoplay = enabled, 
  Video controls (play,next, etc..) = hidden, 
  Fullscreen button = hidden, 
  Video info = hidden, 
  Loop mode = enabled, 
  Randomize = enabled, 
  Video annotation = disabled, 
  and more....
  
