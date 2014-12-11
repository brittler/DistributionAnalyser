DistributionAnalyser
====================

Just a quick java program I wrote which analyses the distribution of values across a hash map, 
and provides a number of statistics. Based on a project from my Computer Science 367 course
at University of Wisconsin - Madison during fall of my freshman year, 2014.

Command line syntax: java DistributionAnalyser SRC_FILE.txt NUM_ELEMENTS TABLE_SIZE
  - where:
      * SRC_FILE      - is a .txt file containing one integer value per line
      * NUM_ELEMENTS  - is the number of elements (number of lines in SRC_FILE)
      * TABLE_SIZE    - is the first value listed in tableSizes.txt which when multiplied by .75 
                        is still larger than NUM_ELEMENTS

Ideally NUM_ELEMENTS and TABLE_SIZE would be automated and the command line arguments 
unnecessary, but I was too lazy for that.

Code's also uncommented. Sorry about that.
