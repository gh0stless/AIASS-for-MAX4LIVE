#version history
###0.5.1  2020-05-08
- added an error indicator LED:
  user shoud check the max-console for more information, when blinking
  this feature needs at least version 0.8.1 of the sid-object
  flashs in a period of 125ms when sid-object not found 
  flashs in a period of 250ms when an fatal error from sid-object detected.