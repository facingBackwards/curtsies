Welcome to the Curtsies documentation
=====================================
.. |shoes| image:: http://ballingt.com/assets/curtsies-tritone-small.png
.. |curtsiestitle| image:: http://ballingt.com/assets/curtsiestitle.png

|curtsiestitle|

Curtsies is a library for interacting with the terminal.

:py:class:`~curtsies.formatstring.FmtStr` objects are strings formatted with
colors and styles displayable in a terminal with `ANSI escape sequences <http://en.wikipedia.org/wiki/ANSI_escape_code>`_.
:py:class:`~curtsies.formatstringarray.FSArray` objects contain multiple such strings
with each formatted string on its own row, and :py:class:`~curtsies.formatstringarray.FSArray`
objects can be superimposed on each other
to build complex grids of colored and styled characters through composition.

Such grids of characters can be rendered to the terminal in alternate screen mode
(no history, like ``Vim``, ``top`` etc.) by :py:class:`~curtsies.window.FullscreenWindow` objects
or normal history-preserving screen by (:py:class:`~curtsies.window.CursorAwareWindow` objects.
User keyboard input events like pressing the up arrow key are detected by an
:py:class:`~curtsies.input.Input` object. See the :doc:`quickstart` to get started using
all of these classes.

.. toctree::
   :maxdepth: 2

   quickstart
   examples
   FmtStr
   FSArray
   window
   Input
   about


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
