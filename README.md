# Webpage_To_PROGMEM
This is an upgraded version of Automatic webpage to PROGMEM. This version encorporates minification of the webpage files so that minimum amount of PROGMEM is used.

Dependencies:  
* API endpoints used for minification which can change over time.
* Internet connection for minification
  
Failsafe:  
* There is a try and except block that just ensures that even if the minification fails the header files are updated with latest changes
* New API's can be easily updated as there is a dictionary that can be modified
