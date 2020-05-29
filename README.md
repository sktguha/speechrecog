# speechrecog
<pre>
A simple demo of speech recognition based on iron man's video
As of now there is a small bug in the HTML file. So it is better to download the video file from https://www.dropbox.com/s/tl9w8dcnaho6j98/Iron%20Man%20Mark%20II%20Test%20Flight.mp4?dl=1
and serve it from localhost server and also change line 8 in im.html to that address , for example
var masterVideoSrc = 'localhost/iron_man.mp4';
Also the localhost server needs to serve pages through HTTPS , else voice recognition is very slow on HTTP and requires repeated permissions

https://rawcdn.githack.com/sktguha/speechrecog/9ce013376a957afec0dc85cc4eb98ec1f9e92054/im.html
https://rawgit.com/sktguha/speechrecog/master/im.html
The user has to speak the required words in place of iron man. They are shown instructions as speak "jarvis you there".
The video pauses at the points where iron man speaks, and on user speaking the required phrase, the video skips to the part where jarvis responds.
Currently the video is restarting at every seek. Instead of using html5 video player directly, it is better to use youtube api in future
</pre> 
