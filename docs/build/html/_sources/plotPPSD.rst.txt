Plot Power Spectral Densities
=============================

Probabilistic Power Spectral Densities will be computed for each channel of a station. The results of the computation will be plotted and saved in a npz file. See the section :ref:`Plot PPSD station channel<plotPPSDSC>` for more explanation.

The median of Power Spectral Densities will then computed using npz files for each channel. The section :ref:`Plot Median PSD of a channel<plotPPSDC>` 
  

.. _plotPPSDSC:

Plot Probabilistic Power Spectral Densities (PPSD)
--------------------------------------------------

Provide graphical representation of the ppsd of a station.
To get more information for this command:

.. code-block:: console

   $plotPPSDSC -h

To run the command: 

.. code-block:: console

   $plotPPSDSC SDSDirectory stationXMLFilename --station stationCode --channel channelCode --startTime  "YYYY-MM-DDTHH:MM:SS" --endTime "YYYY-MM-DDTHH:MM:SS" [Options]

.. _plotPPSDC:

Plot Median Power Spectral Densities (Median PSD)
-------------------------------------------------

Provide graphical representation of the median psd of a channel for all stations. The median PSD will be computed using npz files.
To get help for this command:

.. code-block:: console

   $plotPPSDC -h

To run the command:

.. code-block:: console

   $plotPPSDC stationXMLFilename channelCode [Options]


