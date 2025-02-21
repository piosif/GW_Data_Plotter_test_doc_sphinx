.. App_draft_doc documentation master file, created by
   sphinx-quickstart on Thu Jan 30 17:38:26 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

GW Data Plotter
===============

**GW Data Plotter** is a desktop application that simplifies access to Gravitational Wave (GW) data 
and facilitates basic visualization and analysis.

The app allows users to download *public* gravitational wave data from the LIGO, Virgo, KAGRA, and 
GEO detectors via the `Gravitational Wave Open Science Center <https://gwosc.org>`_. 


.. Zenodo badge that points to the latest release
.. image:: https://img.shields.io/badge/dynamic/json?url=https://zenodo.org/api/records/13778827&label=DOI&query=$.doi&color=blue   
  :target: https://doi.org/10.5281/zenodo.13778827  

.. license badge
.. image:: https://img.shields.io/badge/License-GPL--3.0--or--later-blue
    :target: https://choosealicense.com/licenses/gpl-3.0/
    :alt: License: GPL-3.0-or-later 


.. NOTE: add brief text that answers the questions: 
.. What does this software do and why? 
.. what is the intended audience? 
.. How does the app meets peoples needs?
.. add brief text for motivation and context of the app.

- `Source Code @ GitHub <https://github.com/camurria/GW_Data_Plotter/>`_
- `Issue Tracker <https://github.com/camurria/GW_Data_Plotter/issues>`_

Installing the app
------------------

- The easiest way to install the app is to download and run the executable file suitable for your operating system from the 
  `Zenodo repository`_. 
- Executable files are available for Windows, Linux, and macOS.
- For further details on how to install the app, please refer to the :doc:`install` page.

.. toctree::
   :maxdepth: 2
   :caption: Contents

   Home <self>
   install
   get_data 
   plot_data
   explore_data
   links
   ack

License
-------

This software is licensed under the **GNU General Public License v3 or later (GPL-3+).**
Please read the `license`_ text for full details.

.. _Zenodo repository: https://zenodo.org/records/13778827
.. _license: https://choosealicense.com/licenses/gpl-3.0/

