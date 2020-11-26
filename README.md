# Structured-Improv
Pure data project created as part of Music 2D course

Initial set up

1. Make sure audio output is set up to preferred speakers/headphones in stereo
2. Add required libraries
3. Switch on DSP
4. Add the preferred MIDI keyboard as MIDI input( I’ve set up the ‘ctlin’ objects for each slider
according to the MIDI keyboard I used)
5. Open the patch
6. Change the ‘ctlin’ arguments based on the preferred dials/knobs that you are going to use
for live control.
7. Change the live control options for the chord tone based on the keyboard you use (see the
central area of the patch. Change 33,64 and 35 based on what the shift+1/shift+2/shift+3
ASCII values are for your keyboard, since the symbols corresponding to them change
according to keyboard)

External Libraries required –
  Cyclone-v0.3c1
  
How to use - 
To start the patch, click on the ‘PLAY’ message box next to the ‘START HERE’ comment on the top of
the patch. Once the drums, chords and bass have started playing, the patch has attained its basic
structure, and the live control is left up to the user.

Live Control –
1. Press the following keys to mute/ unmute instruments
    q – primary synth
    w – secondary synth
    e – drums
    r – bass
    t – chords
    y – voice

2. Dials and knobs to control the volume of each instrument, master volume(red), master low
  pass filter(red), modulation depth of frequency mod of bass(yellow)(left side), amplitude
  modulation frequency of the voice(grey)(left bottom)
  
3. Press ‘z’ to activate double high hats while the drums are playing. 
  
4. Press shift+1/shift+2/shift+3 to toggle between different chord tones.
  
5. Comment boxes on the patch to
    o Reset patch
    o Mute all
    o Play All
    o Reset Bass tone by resetting modulation depth
    o Reset all instruments to default volume(right side of mixer)
    
6. Bang to fade out all instruments over a span of 12.8 s.
