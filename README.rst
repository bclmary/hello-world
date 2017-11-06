###############
 ReST Readme
###############


:Date:    2017-11-06
:Version: 1
:Author:  BCL Mary

Header 1
========

The area of a circle is :math:`A_c = (\pi/4) d^2`.

The area of a circle is :math:`A_c = \frac{\pi}{4} d^2`.

.. math::
    A_c = \frac{\pi}{4} d^2
    :label: equ1

Header 2
========

Poulpes:

* petit poulpe with ``inline code``
* `grand poulpe`_ as an hyper-ref

Some quote
 
 my quote

Some python code bloc

.. code:: python

  def my_fn(a):
   return a**2

.. code-block:: python

  def dummy(x):
   return x+1


Generic code bloc
::
 
 Some stuff


.. _`grand poulpe`: https://en.wikipedia.org/wiki/Cthulhu
