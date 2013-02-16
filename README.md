Lang Alert
===========
This program plays a sound when typing, for the current input language.
Intended for multi-lingual users, this program helps to avoid typing in the wrong language.

Currently only supports the Windows platform.

**Note:** this is not a keylogger. Your keystorkes are not saved.

Version
-------
0.1

License
-------
GPL v3

Dependencies
-------
  - Python 2.6
  - [Python for Windows extensions] [pywin32]
  - [pyHook] [pyhook]

Credits
-------
This program contains code from the [PyKeyLogger project] [pykeylogger].

TODO
-------
  - One alert per window (currently alerts for each keystroke)
  - Keep language codes in a configuration file
  - Keep language alert sound files in configuration
  - Support Linux (X11)

  [pywin32]: http://sourceforge.net/projects/pywin32
  [pyhook]: http://sourceforge.net/projects/pyhook/
  [pykeylogger]: http://pykeylogger.sourceforge.net  
