=========
Pycgminer
=========

Python wrapper for `cgminer <https://github.com/ckolivas/cgminer>`_ RPC API.

.. image:: https://pypip.in/v/pycgminer/badge.png
        :target: https://crate.io/packages/pycgminer

.. image:: https://pypip.in/d/pycgminer/badge.png
        :target: https://crate.io/packages/pycgminer


Installation
------------

.. code-block::

    $ pip install pycgminer


QuickStart
----------

.. code-block:: python

    from pycgminer import CgminerAPI

    cgminer = CgminerAPI()

    summary = cgminer.summary()

    my_asic = cgminer.asc(0)


Donation
--------

If you like my work, please consider donating:

BTC 18ZcxHsKnc4a1AhnThQ2tiLVjQehxKaGFX


License (MIT)
-------------

Copyright (c) 2013 Thomas Sileo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
