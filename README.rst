==================
Oblique Strategies
==================

.. image:: https://badge.fury.io/py/obliquestrategies.svg
    :target: https://badge.fury.io/py/obliquestrategies

Over One Hundred Worthwhile Dilemmas
====================================

Created by Brian Eno and Peter Schmidt, first published in 1975
===============================================================

This work is forked from `CrossNox's Programming Excuses <https://github.com/CrossNox/programmingexcuses>`_

Delving deep into the history and development of `David Bowie's Heroes <https://www.youtube.com/watch?v=lXgkuM2NhYI>`_ I found out that during the recording of the album, Brian Eno made use of his set of cards: Oblique Strategies.



In 1975, the magnificent `Brian Eno <https://www.youtube.com/watch?v=lCCJc_V8_MQ>`_ and `Peter Schmidt <http://www.rtqe.net/ObliqueStrategies/images/Schmidt1.jpg>`_ designed a method for promoting creativity, where each card offers a way to break mental blocks. In the subsequent years more and more editions of the deck of cards were made.

Unsurprisingly, considering the creative nature of programming, this works very well when trying to overcome a deadlock in the midst of coding. 

To understand more about this method, you should read `<http://www.rtqe.net/ObliqueStrategies>`_ which also serves as the original sources for every deck in this module.

This Python module and terminal command gives you one Oblique Strategy per run, taken from any of the original three decks or from the fourth special one. This comprises the first edition (1975), the second one (1978), the third one (1979), and the fourth one (1996), which has a `pretty interesting story <http://www.rtqe.net/ObliqueStrategies/Edition4.html>`_ 

------------

Installing
==========

.. code:: bash

    pip install obliquestrategies

Usage
=====

.. code:: python

    >>> from obliquestrategies import get_strategy
    >>> print(get_strategy())
    Work at a different speed

Deck editions can be specified by edition number or edition year

.. code:: python

    >>> print(get_strategy(1))
    Trust in the you of now
    >>> print(get_strategy(1975))
    How would you have done it?

From a terminal
===============

.. code:: bash

    $ obliquestrategies
    What would your closest friend do?

And once again, editions can be specified by numer or year with the :code:`--edition` option.

.. code:: bash

    $ obliquestrategies --edition 2
    Turn it upside down
    $ obliquestrategies -e 1978
    Repetition is a form of change