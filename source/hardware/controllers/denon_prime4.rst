Denon DJ Prime 4
================

The Prime 4 is a standalone, 4-deck DJ console featuring 4 USB inputs, XLR + RCA outputs, 2 dedicated microphone inputs, independent Zone output, and a 10.1" touchscreen, all powered by Engine DJ OS. The Prime 4 also offers Computer Mode, which allows it to be used as a fully-featured controller for Mixxx.

.. versionadded:: 2.4.0

Useful links
------------

- `Denon Prime 4 Mapping - Forum Thread <https://mixxx.discourse.group/t/denon-prime-4-mapping/22404/35>`_
- `Denon DJ's Product Page <https://www.denondj.com/prime-4-prime4xus>`_
- `Prime 4 User Guide <https://cdn.inmusicbrands.com/engine/v2.4.0-86b546b6/PRIME%204%2C%20PRIME%202%2C%20PRIME%20GO%2C%20SC%20LIVE%204%2C%20SC%20LIVE%202%20-%20User%20Guide%20-%20v2.4.0.pdf>`_
- `Engine DJ OS + Windows Driver Download <https://www.denondj.com/downloads>`_

Compatibility
-------------

- **Windows** users need to `download the latest Prime 4 Windows Driver <https://www.denondj.com/downloads>`_ for Computer Mode to work properly with their computer.
- **MacOS** users should be able to use the Prime 4 out-of-the-box.
- **Linux** users should be able to use the Prime 4 out-of-the-box.

User Variables
--------------

User variables can be set to suit individual needs inside the :file:`Denon-Prime-4-scripts.js` mapping file:

- ``deckColors`` - Customize the colour of each deck, shown on the Load and Deck Toggle buttons, and the jog wheel LEDs.
- ``skipButtonBehaviour`` - Changes the behaviour of the Track Skip buttons. ``skip`` makes them jump to the start/end of the current deck's loaded track, and ``seek`` rapidly seeks through the current deck's loaded track.
- ``wheelSensitivity`` - Changes the sensitivity of the jog wheels.
- ``rateRanges`` - Allows the user to define their own set of pitch fader ranges to cycle through with SHIFT + the Pitch Bend buttons.
