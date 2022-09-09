Plot Instrument Responses
=========================

There are 2 kinds of plots for instrument responses:

* :ref:`Plot instrument responses for a station<plotIRS>` 
  
* :ref:`Plot instrument responses for a channel<plotIRC>` 
  

.. _plotIRS:

Plot instrument responses for a station
---------------------------------------

Create a plot instrument responses of a station with all its channels
To get more information about this plot command, type the following

.. code-block:: console

   $plotInstrumentResponseS -h

To create an image representing the responses of instruments used for a station, type:

.. code-block:: console

   $plotInstrumentResponseS [Options] stationXMLfilename --station stationCode

.. _plotIRC:

Plot instrument responses for a channel
---------------------------------------

Create a plot instrument response of a channel for all stations possessing this channel
Type the following command to get more explanation

.. code-block:: console

   $plotInstrumentResponseC -h

To create an image representing the responses of instruments used for a channel, type:

.. code-block:: console

   $plotInstrumentResponseS [Options] stationXMLfilename --channel channelCode
