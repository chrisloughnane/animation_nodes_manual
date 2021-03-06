Animate Color
=============

Description
-----------

This node mixes between two colors where the factor for mixing is the time mapped to an input interval *Duration*.

.. image:: images/animate_color_node.png
   :width: 160pt

Inputs
------

- **Time** - A time or the factor for mixing.
- **Start** - A value to start the animation with or the first input for mixing.
- **End** - A value to end the animation with or the second input for mixing.
- **Interpolation** - An Interpolation(Function) to evaluate the time at (Linear will just use the input time).
- **Duration** - The duration of the animation or the interval to map the time to or the value the time is divided by.

Outputs
-------

- **Time** - The different between the input time and the duration (Isn't affected by the input interpolation).
- **Result** - The value of the animation evaluated at the input time or the result of mixing.

Advanced Node Settings
----------------------

- N/A

Examples of Usage
-----------------

.. image:: gifs/animate_color_node_example.gif
