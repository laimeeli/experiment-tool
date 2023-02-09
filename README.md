This script takes an items file and turns it into a xxxxxx.turk.csv file with randomized lists of items, that can be uploaded onto AMT. The Lister creates Latin Square counterbalanced randomized lists from the items that it is given.

Once it is run, lister.py will ask for (a) the name of your raw items file, (b) which sections should be treated as fillers, (c) how many filler items you would like placed between each target item, (d) how many filler items you would like placed in the beginning and end of the experiment, (e) how many lists you would like to create, and (f) whether or not you would like the reverse of each list to also be created, to help reduce any ordering effects that may occur.

Note that as a default, no section is singled out to be used as fillers. You may to designate one or more sections as fillers and all the other sections will be treated as targets. Fillers and targets will be randomized separately and then combined according to the conditions you specified.

