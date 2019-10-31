Tutorial 2 (AIA data ananysis)
*******************************

Importing and ploting data
==========================

Solar Dynamics Observatory is of the most successfull missions by NASA in 2010 which aids the routine observations of Sun in different channels. Atmospheric Imaging Assembly is one of the instruments on board SDO which looks at different layers of Sun. Angular resolution of AIA is about 1″ (arcsec). It uses a variety of filters in parallel to gather 8 images of the Sun every 12 seconds. Each observation retruns an image of visible solar disk at an resolution of 4096x4096 pixels.

Different channels/filters in AIA observe different layers of the Sun. This il help us track variousactivities that are going on in the solar atmosphere.

+-------------+------------+--------------------------+----------------------------+
| AIA channel | Region of solar atmosphere            | Characteristic temperature |
+=============+=======================================+============================+
| 450.0 nm    | Photosphere                           | 5777 K                     |
+-------------+---------------------------------------+----------------------------+
| 30.4 nm     | Chromosphere & transition region      | 50000 K                    |
+-------------+---------------------------------------+----------------------------+
| 17.1 nm     | Queit corona, upper transition region | :math:`1.2 \times 10^6 K \& 2\times 10^7` K |
+-------------+---------------------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+
.. |             |                            |                            |
.. +-------------+----------------------------+----------------------------+

We will download some of the data ad plot them using `SunPy <https://sunpy.org/>`_.



.. toctree::
   :maxdepth: 1

   Example 1: Download and plot full-disc observations of Sun(AIA) <notebooks/AIA-Example-1.ipynb>


See :download:`this example script <notebooks/AIA-Example-1.py>`.

