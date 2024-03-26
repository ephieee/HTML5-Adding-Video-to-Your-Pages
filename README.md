# HTML5-Adding-Video-to-Your-Pages

<video>
The <video> element has a number of attributes which allow you to control video playback:
src
This attribute specifies the path to the video. (The example video is in H264 format so it will only work in IE and Safari.)
poster
This attribute allows you to specify an image to show while the video is downloading or until the user tells the video to play.
preload
This attribute tells the browser what to do when the page loads. It can have one of three 
values: 
none
The browser should not load the video until the user presses play.
auto
The browser should download the video when the page loads.
metadata
The browser should just collect information such as the size, first frame, track list, and duration.
width, height
These attributes specify the size of the player in pixels.
controls
When used, this attribute indicates that the browser should supply its own controls for playback.
autoplay
When used, this attribute specifies that the file should play automatically.
loop
When used, this attribute indicates that the video should start playing again once it has ended.


<!DOCTYPE html>
<html>
  <head>
   <title>Adding HTML5 Video</title>
  </head>
 <body>
  <video src="video/puppy.mp4" 
         poster="images/puppy.jpg" 
         width="400" height="300" 
         preload
         controls
         loop>
 <p>A video of a puppy playing in the snow</p>
 </video>
</body>
</html>
