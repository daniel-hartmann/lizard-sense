lizard-sense
============

=== Installation

sudo apt-get install python-pyaudio


=== Usefull Stuff

gst-launch-1.0 audiotestsrc wave=2 freq=440 ! audioconvert ! tee name=t ! queue ! alsasink t. ! queue ! libvisual_lv_scope ! videoconvert ! xvimagesink

