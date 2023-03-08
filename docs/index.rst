Joy
===============================

Joy is a tiny creative coding library in Python.


**Source Code:** https://github.com/anandology/joy

.. replite::
   :kernel: python
   :height: 600px
   :prompt: Try Replite!
   :prompt_color: #dc3545

   from js import fetch

   URL = "https://raw.githubusercontent.com/anandology/joy/main/joy.py"
   res = await fetch(URL)
   text = await res.text()
   filename = 'joy.py'
   with open(filename, 'w') as f:
     f.write(text)

   from joy import *
