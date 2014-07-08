We Are Robot
============

A generative audio patch for [Patchblocks](http://patchblocks.com). Plays a random sequence of notes over an alternating base note and optional sub-bass.

The patch comprises three pulse (square wave) oscillators routed through a low pass filter to the analogue and digital audio outputs.

* Oscillator 1 plays a random melody with quarter notes selected from the pentatonic scale.
* Oscillator 2 also plays quarter notes and alternates between one and two octaves below the tonic note.
* Oscillator 3 plays at tempo three octaves below the tonic note. 

A feedback delay can be applied to the bass (Oscillator 2). Delay time is at double tempo.

Tempo is set to 60bpm within the patch itself. 

Controls
--------
Left Knob: Set tonic note in range C4 - B4  
Right Knob: Filter cut off  
Left Button: Switch delay on bass in/out  
Right Button: Switch sub-bass in/out

Left LED indicates delay on/off.
Right LED indicates sub-bass on/off with flashing tempo.

Licence
-------
Licensed under the [GPL v2](http://choosealicense.com/licenses/gpl-v2/) license. A copy is included in this repository.