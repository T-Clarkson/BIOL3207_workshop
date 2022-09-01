# BIOL3207_workshop

This repository is used for the purpose of the 2nd of September BIOL3207 workshop.

## Files

The git_fishes_student.rmd file is the annotated R script used for the coding using R studio. The R markdown format allows it to be knitted as an HTML for readability.

The OA_activitydat_20190302_BIOL3207.csv file is the data frame used in this repository.
OA_activitydat_20190302_BIOL3207_tidied.csv is the same data, after it has been tidied up, with any NA values removed and spelling errors corrected.

### OA_activitydat_20190302_BIOL3207.csv
columnHeading: descriptions	
-------------		-----------	
loc: Location, and year, where the data were collected. AIMS = Australian Institute of Marine Science; LIRS = Lizard Island Research Station
species: Species name; acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis	
treatment: Elevated CO2 [CO2] (850-1,050 µatm) or control [Control] (400 - 450 µatm) groups
animal_id: Fish identity
sl: Standard length of the fish in mm
size: Size grouping of the fish, separated at 15 mm standard length into 'big' or 'small'
activity: Number of seconds the fish was active per minute, averaged across the duration of the trial
comment: Comment with notes on the origin of the data

### OA_activitydat_20190302_BIOL3207_tidied.csv
columnHeading: descriptions
_________
species: Species name; acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis	
treatment: Elevated CO2 [CO2] (850-1,050 µatm) or control [Control] (400 - 450 µatm) groups
animal_id: Fish identity
sl: Standard length of the fish in mm
size: Size grouping of the fish, separated at 15 mm standard length into 'big' or 'small'
activity: Number of seconds the fish was active per minute, averaged across the duration of the trial

### .gitignore
This file is used to prevent GitHub from tracking various pathways throughout the processes of commiting and pushing files to the servers. Currently, any files added in the ./output/figures/ folder will be ignored, and will not be tracked.
