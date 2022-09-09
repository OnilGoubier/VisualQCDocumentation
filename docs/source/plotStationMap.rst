Plot A Map of Stations
======================

This command generates a map of all stations of a given network. 
Type the following help to see more explanation.

.. code-block:: console

   $ plotStationsMap -h

To create a map, use the following command

.. code-block:: console

   $ plotStationsMap [Option] stationXMLFilename

The input file is a station xml file containing metadata of all stations that will be plotted in the created map.

The following is the use of the plotStationsMap command with all optional arguments:

.. code-block:: console

   $ plotStationsMap -h
   usage: plotStationsMap [-h] [--output OUTPUTFILE] [--outFormat FMTID]
                       INPUTMETAFILE

   Provide a map of all stations (fournit carte géographique des stations du
   réseau)

   positional arguments:
     INPUTMETAFILE        <INPUTMETAFILE> input file, wildcards accepted (please
                       write the name with wildcards * between quotes, ex.
                       "*.xml")

   optional arguments:
     -h, --help           show this help message and exit
     --output OUTPUTFILE  <OUTPUTFILE> Optional output file name
     --outFormat FMTID    <FMTID> Optional format of output file (JPEG ro PNG)
