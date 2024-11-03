# GMinR
This is a script (set of scripts) to run basic Geometric Morphometric analyses in R. 
***

The script is designed to run on the fish data collected from the west Island of Montreal during the 2024 field season. For the script to run, the proper libraries must be installed on your computer. Cmds to do this are included (19-22) but are currently commented out. To activate, remove the "#" in front of lines 21-22.

The script will load a readied '.TPS' file into R using the geomoprh 'readland.tps' cmd. The data come across as scaled (scaling was included during landmarking), and each individual's landmark configuration is loaded. Individuals are identified from their ID entry (also fixed during landmarking). The script also needs another file containing the metadata (in csv format), which are the environmental variables collected during sampling.

With all the data entered, the scripts should provide all the basic analyses you might need. At the very end, there is an example on how to calculate the morphological disparity, which is nearly the same as morphological diversity. In this case, because the morphological diversity is based on the overall shape of the fish --> and that shape in most fishes is a functional trait, one could consider this to also represent functional morphological diversity. 

To use the script you will need the TPS and the metadata files. You can access the FISH2024L.TPS or the FISH2024R.TPS file(s) from *myCourses* at this point. Similarly, you can also download the F2024-METACSV.csv file from the same location. The script will not work properly without both files. Please note, that you will need to tell R where the files are located on your computer (on line 41 of the script), and what files to use specifically, on lines 44 and 48. 

#### There are no guarantees on the script, so use at your own risk
*** 

I hope you find this useful.

Written by Denis Roy Oct 2024.
