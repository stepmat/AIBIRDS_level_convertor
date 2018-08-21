# AIBIRDS_level_convertor
This program can convert levels between the Science Birds .xml format, and the official Angry Birds .json format.

Run the converter with two parameters, the level file to be converted and the file to convert it into.

e.g. python converter.py level-04.xml level1-1.json

This program can bidirectionally convert between the two formats.

Please note that the program cannot currently convert scaled Science-Birds objects.

If using the Iratus Aves level generator (https://github.com/stepmat/IratusAves), the "add_slopes" parameter must be set to false in order to generate levels that can then be successfully converted.
