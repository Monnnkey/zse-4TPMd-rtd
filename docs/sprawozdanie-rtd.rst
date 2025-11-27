Sprawozdanie-rst
================

Nagłówki
--------

.. code-block:: rst

   ===================
   Nagłówek poziomu 1
   ===================

===================
Nagłówek poziomu 1
===================

.. code-block:: rst

   Nagłówek poziomu 2
   ^^^^^^^^^^^^^^^^^^

Nagłówek poziomu 2
^^^^^^^^^^^^^^^^^^

.. code-block:: rst

   Nagłówek poziomu 3
   ~~~~~~~~~~~~~~~~~~

Nagłówek poziomu 3
~~~~~~~~~~~~~~~~~~

.. code-block:: rst

   Nagłówek poziomu 4
   """"""""""""""""""

Nagłówek poziomu 4
""""""""""""""""""

Akapit informacyjny (tzw. „tytułowy”)
-------------------------------------

.. code-block:: rst

   To jest zwykły akapit.
   -------------------
   Akapit informacyjny
   -------------------

To jest zwykły akapit.
Akapit informacyjny
-------------------

Uwagi, podpowiedzi, ostrzeżenia
-------------------------------

.. code-block:: rst

   .. note::
      To jest notatka

.. note::
   To jest notatka

.. code-block:: rst

   .. tip::
      To jest podpowiedź

.. tip::
   To jest podpowiedź

.. code-block:: rst

   .. warning::
      Uważaj na to!

.. warning::
   Uważaj na to!

Kod liniowy (inline)
--------------------

.. code-block:: rst

   Użyj metody ``System.out.println()`` w Javie.

Użyj metody ``System.out.println()`` w Javie.

Kod blokowy
-----------

.. code-block:: rst

   .. code-block:: python

      def hello():
          print("Witaj w reST!")

.. code-block:: python

   def hello():
       print("Witaj w reST!")

Odnośniki (linki)
-----------------

.. code-block:: rst

   `Moje repozytorium na GitHubie <https://github.com/Monnnkey/zse-4TPMd-rtd>`_

`Moje repozytorium na GitHubie <https://github.com/Monnnkey/zse-4TPMd-rtd>`_

Listy nienumerowane
-------------------

.. code-block:: rst

   - pierwszy element
   - drugi element
   - trzeci element

- pierwszy element
- drugi element
- trzeci element

Listy numerowane
----------------

.. code-block:: rst

   1. Pierwszy
   2. Drugi
   #. Automatyczna numeracja też działa

1. Pierwszy
2. Drugi
#. Automatyczna numeracja też działa

Obrazki
-------

.. code-block:: rst

   .. image:: https://tiny.pl/06yd8xzf
      :alt: Wojfer
      :width: 300px
      :align: center

.. image:: https://tiny.pl/06yd8xzf
   :alt: Wojfer
   :width: 400px
   :align: center

Tabele – prosta składnia
------------------------

.. code-block:: rst

   =====  =====  =======
   A      B      A and B
   =====  =====  =======
   False  False  False
   True   False  True
   False  True   True
   True   True   True
   =====  =====  =======

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  =======
