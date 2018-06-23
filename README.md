# Welcome to the repository of the Extended BioV suite of programs

The original programs in the suite were originally written by Vamsee Reddy, many have been updated and new programs have been added by different members of the lab and collaborators.

Find below the list of programs available. Scripts developed by our group as dependencies are not listed here but are included in the distribution:  

**1.** protocol1.py  ([Manual](manuals/BioV_manual.pdf))  
**2.** protocol2.py  ([Manual](manuals/BioV_manual.pdf))  
**3.** gsat.py       ([Manual](manuals/BioV_manual.pdf))  
**4.** gblast3.py    ([Manual](manuals/BioV_manual.pdf))    
**5.** tmstats.py    ([Manual](manuals/BioV_manual.pdf))  
**6.** tss.py        ([Manual](manuals/BioV_manual.pdf))  
**7.** ssearch.py    ([Manual](manuals/BioV_manual.pdf))  
**8.** ancient.py    ([Manual](manuals/AR_INSTRUCTIONS.pdf))   
**9.** quod.py       ([Manual](https://github.com//khendarg/hvordan/blob/master/docs/quod.md))  
**10.** hvordan.py   ([Manual](https://github.com/khendarg/hvordan/blob/master/docs/hvordan.md))  
**11.** tmsplit.py  

---  

* **Note 1:**  
The BioV manual needs to be updated.  

* **Note 2:**  
Some modifications to protocol 2 and other programs
by Gabriel Moreno-Hagelsieb.   

* **Note 3:**  
Pranav Iddamsetty and Arturo Medrano added the scripts
_tmsplit.py_ and _tmsFunction.py_. These programs provide a 
command-line interface to cut transporter sequences
under the same criteria as the website:  
http://biotools.tcdb.org/bartms_split.html  

* **Note 4:**  
The program _gblast3.py_ was modified by Pranav Iddamsetty 
and Arturo Medrano to generate a tabulated file 
(_results.tsv_) with the same output as _results.html_. This 
will allow further automatic processing of gblast output 
(e.g. compare different outputs of gblast to identify 
commonalities/differences between trasporter systems in 
different genomes). This program was also modified to add 
annotated substrates in tcdb to the output.   

* **Note 5:**  
The programs _quod.py_, _tcblast.py_ and _hvordan.py_ were added 
by Kevin Hendargo and Arturo Medrano. The script quod.py 
runs WHAT from the command line on one or more sequences 
and is able to generate the plots in different formats and 
qualities. The script _tcblast.py_ provides functions to run 
blast against tcdb from the command line and provides 
graphical display that will be used by the last script 
_hvordan.py_, which runs blast and WHAT in order to generated 
an html ouput file that will help the user to make the 
biological interpretation of protocol2 top hits.  

