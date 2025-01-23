Introduction
============


.. image:: https://readthedocs.org/projects/adafruit-circuitpython-vl53l4cd/badge/?version=latest
    :target: https://docs.circuitpython.org/projects/vl53l4cd/en/latest/
    :alt: Documentation Status


.. image:: https://raw.githubusercontent.com/adafruit/Adafruit_CircuitPython_Bundle/main/badges/adafruit_discord.svg
    :target: https://adafru.it/discord
    :alt: Discord


.. image:: https://github.com/adafruit/Adafruit_CircuitPython_VL53L4CD/workflows/Build%20CI/badge.svg
    :target: https://github.com/adafruit/Adafruit_CircuitPython_VL53L4CD/actions
    :alt: Build Status


.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code Style: Black

This is a Python driver for the VL53L4CX time of flight range sensor, based on `veloyage's fork <https://github.com/veloyage/Adafruit_CircuitPython_VL53L4CD>`_ of the `Adafruit VL53L4CD driver <https://github.com/adafruit/Adafruit_CircuitPython_VL53L4CD>`_.

Adafruit has not released a Python driver for the VL53L4CX, so this fork is necessary to use the VL53L4CX with Python on a Raspberry Pi. veloyage's changes enable the driver to read the distances up to 250 cm, which is still not the full range of the sensor.

This fork simply renames the driver to `adafruit_vl53l4cx` to match the sensor name.

Relevant Links
----------------
* `Comment thread discussing VL53L4CX support <https://github.com/adafruit/circuitpython/issues/6351>`_
* `Adafruit VL53L4CD driver <https://github.com/adafruit/Adafruit_CircuitPython_VL53L4CD/blob/39fc7df54af911b7e4206a46c21bf4952e02f7f1/adafruit_vl53l4cd.py>`_
* `veloyage's fork of the Adafruit VL53L4CD driver <https://github.com/veloyage/Adafruit_CircuitPython_VL53L4CD>`_

Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_
* `Bus Device <https://github.com/adafruit/Adafruit_CircuitPython_BusDevice>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://circuitpython.org/libraries>`_
or individual libraries can be installed usi
`circup <https://github.com/adafruit/circup>`_.

Adafruit VL53L4CD Time of Flight Distance Sensor - ~1 to 1300mm - STEMMA QT / Qwiic

`Purchase one from the Adafruit shop <http://www.adafruit.com/products/5396>`_


Installing from PyPI
=====================
To install, clone this repo and install with pip:

.. code-block:: shell
    cd Adafruit_CircuitPython_VL53L4CD
    pip3 install .


Usage Example
=============

See examples/vl53l4cd_simpletest.py for basic usage example.