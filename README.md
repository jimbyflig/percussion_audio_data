# percussion_audio_data

This is data associated with my senior honors thesis. There are multiple folders with audio 
data in them, which will be described here. Datasets can be described as either "healthy" or
"unhealthy," and a description of each will also be given when the data gathering process is 
described.

# LargeFlange - Between
This folder contains data taken from using a hammer to tap directly on a 17 inch flange, which
has 12 numbered bolts. All of these bolts were tightened to 210 ft-lb, and then one of them was
loosened. After one of the bolts was loosened, the hammer was used to tap on the flange
in the middle of the space between all of the bolts.

A file from this set is considered "healthy" if the tapping was done between two of the
tight bolts. A file from this set is considered "unhealthy" if it took place between one
healthy bolt and one unhealthy bolt.

File names are saved as follows: 17flange-(number of the loose bolt)-(The bolt numbers that
tapping took place between)-(trial number)


# LargeFlange - On
This folder contains data taken from using a hammer to tap on a the bolts of a 17 inch flange, 
which has 12 numbered bolts. All of these bolts were tightened to 210 ft-lb, and then one of them 
was loosened. After one of the bolts was loosened, the hammer was used to tap on the center of the
top of the bolts.

A file from this set is considered "healthy" if the tapping was done on a tight bolt. A file from 
this set is considered "unhealthy" if it took place on the loose bolt.

File names are saved as follows: 17flange-(number of the loose bolt)-(number of bolt tapped)

# Plate Data - 13and14 (and its validation set of data)
This folder contains data taken from using a hammer to tap on a the through bolts for two aluminum
plates. All of the bolts were at 40 ft-lb except for bolts 13 and 14. Four sets of data were taken with
this configuration. A file is considered healthy if the tapping was done on a tight bolt. A file is considered
unhealthy if it was done on the loose bolts, 13 or 14.

File names are saved as follows: Plates-loose13and14-(number of bolt tapped)-(set number)
