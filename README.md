# SmartMirror
Smart Mirror Project

## Youtube Demo coming soon

## 1. Tools:        
#### 1. Hardware
  * 2 way acrylic/glass Mirror
  * mirror frame (will need to construct this yourself)
  * raspberry pi 3/b
  * 8/16gb sd card
  * speaker (bluetooth also works)
  * mouse/keyboard
  * usb mic
  * pi camera v2/noir
  * lcd/led monitor (monitors have better quality than tvs for this purpose)
  * power cables for the above
 
#### 2. Software
  * Raspbian Jessie 
  * Magic Mirror ^ 2 open source
  * Alexa Lamba Function
  * Alexa Custom Skills
  * Google Custom Search Api
  * Youtube Search Api
  
## 2. Features:
  * Pi Camera motion detection so shuts off after 5 min of inactivity perfect for saving energy (for v2 would recommend using PIR sensors but have spare cameras, also may work with unused Xbox Kinect)
  * Amazon Alexa Voice Service, has the ability to integrate with Google and Youtube search api so she can display images and videos within an frame in the mirror
  * Basic functionality with custom features such as modified Apple/Google calendar pulls, modified weather display 
  * Displays Spotify current song, perfect when Alexa plays music for you in the morning
  
## 3. Issues/Future updates:
  * Spotify will not display music when initiated from Alexa but via the spotify app (this is known) but also there is a delay with the display at times, need to debug
  * Depending on the monitor many times it will flag that there is no signal, this can be anoying to look at so Samsung monitors tend to leave that warning out
  * Alexa blindspots? tba
