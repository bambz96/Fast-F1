.. F1 Telemetry documentation master file, created by
   sphinx-quickstart on Fri Nov 29 01:37:14 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


=====================
Fast F1 documentation
=====================

For the passionate F1 nerds.


Check out the examples: :doc:`examples/index`

Or take a look at the gallery for some inspiration:
:doc:`examples_gallery/index`


There are also some great articles and examples written by other people. They
provide a nice overview about what you can do with FastF1 and might help you
to get started.

  - `Accessing Formula-1 Race's historical data using Python (medium.com) <https://pandeyparul.medium.com/accessing-formula-1-races-historical-data-using-python-b7c80e544f50>`_
  - `Formula 1 Data Analysis Tutorial - 2021 Russian GP: "To Box, or Not to Box?" (medium.com) <https://medium.com/@jaspervhat/formula-1-data-analysis-tutorial-2021-russian-gp-to-box-or-not-to-box-da6399bd4a39>`_
  - `How I Analyze Formula 1 Data With Python: 2021 Italian GP (medium.com) <https://medium.com/@jaspervhat/how-i-analyze-formula-1-data-with-python-2021-italian-gp-dfb11db4b73>`_



Introduction
============

FastF1 gives you access to F1 lap timing, car telemetry and position,
tyre data, weather data and weekend information among others.
No formula1 account is needed.

The module is designed around Pandas, Numpy and Matplotlib. This makes it easy
to use while offering lots of possibilities for data analysis and
visualization.

FastF1 handles big chunks of data (~50-100mb per session) so most of the
information is stored locally as cached requests (be aware).

All data is downloaded from two sources:

    - The official f1 data stream ->
      `f1-live <https://www.formula1.com/en/f1-live.html>`_
    - Ergast web api -> `ergast.com <http://ergast.com/mrd/>`_

Have fun!


Installation
============

It is recommended to install FastF1 using pip:

    pip install fastf1

Note that Python 3.8 or higher is required.
(The live timing client does not support Python 3.10, therefore full
functionality is only available with Python 3.8 and 3.9)

Alternatively, a wheel or a source distribution can be downloaded from the
Github releases page or from Pypi.


.. toctree::
   ← Back to Github <https://github.com/theOehrly/Fast-F1>

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   examples/index
   examples_gallery/index
   fastf1
   core
   api
   utils
   plotting
   livetiming
   legacy

.. toctree::
   :maxdepth: 1
   :caption: Information:

   time_explanation
   howto_accurate_calculations
   known_bugs
   troubleshooting
   changelog


==================
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


For questions feel free to contact me:
oehrly@mailbox.org