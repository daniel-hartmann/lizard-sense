lizard-sense
============

Starting this project to create my own instrument to make some music

### TODO

- Interface to play (piano keys maybe) - QT, probably
- Use randomic stuff to generate sounds
- Waves are cool
- I'd like to make it multi platform (check pyaudio on windows and mac)
- Tests (boring...)

### Installation

sudo apt-get install python-pyaudio


### Usefull Stuff

gst-launch-1.0 audiotestsrc wave=2 freq=440 ! audioconvert ! tee name=t ! queue ! alsasink t. ! queue ! libvisual_lv_scope ! videoconvert ! xvimagesink

### Current Test Framework Status

Nothing to work nor test

### Bla

I could started something in html5 and js to run on ipad and android, but i prefer linux+python, so... Why am I writing this anyway?

