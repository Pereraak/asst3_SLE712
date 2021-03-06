# asst3_SLE712
Code to support assignment 3 tasks for unit SLE712

# myscript.sh
myscript.sh is a script to incorporate mismatches with msbar into a sequence and perform a blast search. 
The script is written in shell using bash syntax. formatdb is used to index the nucleotide database. The type of file used is nucleotide (-p F) and parse options were set to parse SeqId and create indexes (-o T). 
The EMBOSS tool msbar is used to mutate the sequence to assess the BLAST performance with the changing mismatch density. The types of point mutations performed are changes ( -point 4)  with none of block mutations or codon mutations ( -block 0, -codon 0). 
A loop has been created to run 100 test for each mismatch count introduced. The change of mismatch count from 275 to 525 presented a gradual drop of BLAST performance. The changes were initially performed in a working directory which was later copied to aat3_SLE712


# Gene Expression
RStudio codes for assessing a .tsv file

This file contains the codes to import a .tsv file to RStudio, read the file data and rearranging them accordingly. It includes the codes to perform certain mathematical operations such as estimating the mean value of the data set, making subsets of data and obtaining a pairs plot.


# Growth Data
 RStudio codes for assessing a .csv file

This file contains the codes to import a .csv file to RStudio, read the file data and rearranging them accordingly. It includes the codes to make subsets of data, perform certain mathematical operations such as calculating the mean values and standard deviations of sets of data and obtain boxplots.
