# ArnoldPaquette_Tristan_IMD3901_A3

The game is quite simple. Its a guessing game where one person is selecting a color, and the other has to guess which color was selected.
How that plays out, is the person with the "controller" web page, has three colored tiles on their display. Once they click on one, their selection is sent to the person with the "color" web page, who will then attempt to guess which color was sent. If they guess right, a green box appears momentarily, and if they guess wrong, a red box appears. After the user on the receiving end makes a guess, they lost their chance for the color sent, and another color needs to be sent over by the first user in order for the second user to make another guess.

The integration of the example code went decently smoothly, and allowed me to build off of it to change and add features as I saw fit (well sort of). Getting the correct and incorrect boxes to appear, also worked without too much trouble

However, anytime I tried to use sockets outside of what was already in the example code, the emitter seemed to simply not work for reasons that are honestly beyond me. I wasn't able to figure out how to fix this, so instead I worked around the issue, and adjusted the scope of my project.
