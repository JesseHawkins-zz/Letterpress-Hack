Letterpress-Hack
================

Detects the letters in a Letterpress game and finds the best words to play.

Goal:

1. load screenshot and break it into individual tiles
2. detect the background color and letter of each tile
3. group the found letters by background color
4. send these letters to http://www.letterpresscheat.net [permission to use their site?]
5. return various results depending on goal: consume gray, steal light red, make more dark blue.



REVISION HISTORY
================

0.1
 - First commit!
 - Issues with some letters (such as "V" and "R") not matching perfectly against their binarized version.
 - Logic need to account for a "checkboard" pattern that overlays the gray tiles.
 - Currently stuck at #3: group the found letters by background color
