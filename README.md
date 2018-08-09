# blender-keyframetools

Some handy tools for working with keyframes in Blender. Inspired by Alan Camilo's animBot.

## Limitations

This software is in its very very very very very very early stages. It is offered here because people on Twitter were all like "wow this looks awesome i want to try it".

* **Only in development for 2.79b, does not work in 2.8**
* The tools currently only works on bone keyframes. **They do not work on object keyframes**.

## Functions

You can call a pie menu with the Shift+Z hotkey in the Graph Editor. You can also use Space Bar search. (2.8 is not supported yet.)

### Graph Editor

#### Keyframe manipulating tools

All of these should work with multiple bone channels. **They do not work on object animation**. (Yet.)

* **Flatten Keyframes**: Non-interactively flattens selected keyframes to a straight line between the first and last keyframe of the selection. Useful for tidying up. Works on multiple channels.
* **Flatten/Exaggerate Keyframes**: Interactively flattens or exaggerates selected keyframes along a straight line between the first and last keyframe of the selection. Useful for making a motion smaller or bigger. Also works on multiple channels.
* **Ease Keyframes**: Interactively create an ease in or ease out for a selection of keyframes. Useful for tidying up an ease pattern. Also works on multiple channels.

#### Shortcut tool

* **Place Cursor and Pivot**: Places the 2D Cursor at the selection and changes Pivot Center to 2D Cursor. Ctrl+G but better. May keymap this to Ctrl+Shift+G soon.

## Roadmap

These are the current priorities as of version 0.0.4

### Coming Additions

* Smooth Rough tool from animBot (will be called Dampen/Excite)
* More stuff depending on what Looch thinks is useful :)

### Coming Fixes

* All: Make existing tools work with object-level animation, not just bones
* Ease: Do something more helpful with out-of-bounds keys 

Work on Blender 2.8 compatibility will begin after 2.8 API is declared stable by the Blender devs. 

## Acknowledgements

Thanks to

* Luciano "Looch" Muñoz for guidance and encouragment 
* Alan Camilo for inspiring us with animBot
