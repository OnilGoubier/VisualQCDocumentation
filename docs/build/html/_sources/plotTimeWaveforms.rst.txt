Plot Time Waveforms
===================

Time waveforms will be plotted in 2 ways:

* :ref:`Plot time waveforms of a station<plotTWS>` 
  
* :ref:`Plot time waveforms of a channel<plotTWC>` 
  

.. _plotTWS:

Plot time waveforms for a station
---------------------------------

Provide waveforms of all (or a subset of) channels of a station

To get more information for this command:

.. code-block:: console

   $plotTimeWaveformsS -h

To run the command:

.. code-block:: console

   $plotTimeWaveformsS SDSdirectory --station stationCode --startTime  "YYYY-MM-DDTHH:MM:SS" --endTime "YYYY-MM-DDTHH:MM:SS" [Options]

.. _plotTWC:

Plot time waveforms for a channel
---------------------------------

Create a time waveforms plot of a channel of all stations related to this channel.

To get more information for this command:

.. code-block:: console
 
   $plotTimeWaveformsC -h

To run the command:

.. code-block:: console

   $plotTimeWaveformsC SDSdirectory --channel channelCode --startTime  "YYYY-MM-DDTHH:MM:SS" --endTime "YYYY-MM-DDTHH:MM:SS" [Options]

