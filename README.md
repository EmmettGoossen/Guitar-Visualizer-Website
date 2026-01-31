# guitar visualizer
entirely frontend score reader for guitar tabs

### Some History
This was created somewhere in my sophomore year of high school, it was only now uploaded to github

## Audio Synth
synth.js is responsible for handling the audio output for each tab

### supports synth letter alteration and audio play:

Note length
* Window.Synth.setNoteLength

Attack
* window.Synth.setAttack

Sustain
* window.Synth.setSustain

Volume
* window.Synth.setVolume

Play
* window.Synth.playNote

## Pitch Detect
pitchDet(Altered).js is a modified version of
https://cwilso.github.io/PitchDetect/.
for detecting pitch

## frontend
script.js handles all the frontend logic to mak the site work
