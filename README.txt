Whose brain is this?  Offline version
=====================================

To play: open index.html in a web browser (double-click it). Chrome, Edge,
Firefox and Safari all work, and no internet connection is needed.
Keep index.html next to the videos/ folder; the page looks for its videos there.

For a booth
- Press F11 (Windows/Linux) or Ctrl+Cmd+F (Mac) to go full screen.
- The game returns to the start screen after 3 minutes without a touch.
- "Start over" (top right) resets it at any time.

Changing things
Open index.html in a text editor and look for the SETTINGS block near the top
of the script:
- IDLE_RESET_SECONDS  change the idle timeout, or set it to 0 to switch it off
- MEDIA               which video file is used for each screen
- EXP                 all the wording for each experiment

Videos (videos/)
  hd_*       mouse head-direction cells, foraging
  reach_*    macaque area 2, reaching task
  film_*     mouse visual cortex, natural movie
  *_activity      scrolling raster (rounds 1 and answers)
  *_shape         grey manifold (round 2)
  *_shapeColour   coloured manifold (answers)
All are H.264 MP4. The HD grey manifold is inverted to a black background, and
the area2 and Allen rasters have their blank lead-in trimmed.

Fonts: Bricolage Grotesque and Atkinson Hyperlegible, embedded in index.html,
used under the SIL Open Font License (licenses/).
