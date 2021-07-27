# TNT Information

These are the macro-script used to run the MP analyses under extended implied weight. If you want to run any of these scripts, please follow the next steps.

1. Donwload the data for the corresponding script here. (e.g., If you will run Combined.run, then download the Combined.tnt file). Then, put files in the same directory.

2. Now make sure that the TNT executable is in the same folder and put this command.

```
#For Linux, use the terminal

tnt run Combined.run;

#For Windows, use the TNT's command window

run Combined.run;

```
3. The script will generate the following outputs:
  - **Combined_Loncho.ctf:** The most parsimonious trees in binary format.
  - **Combined_Loncho.tre:** The most parsimonious trees in Nexus format.
  - **Combined_Loncho_jack.tre:** The most parsimonious trees in Nexus format, after the Jackknife resampling (not useful).
  - **Combined_Loncho_sym.tre:** The most parsimonious trees in Nexus format, after the Symmetric resampling (not useful).
  - **Combined.txt:** The log file from the run. It displays all the information that TNT generates, useful if you wanna see Scores, Indices, etc ...

4. Finally, if you want to calculate tree statistics (i.e., Consistency, Retention and Rescaled Indices), download the "stats.run" script, put in the same folder where you ran the analysis and put the following commands.

```
#For Linux, use the terminal

tnt mxram 2000 proc Combined.tnt sh Combined_Loncho.ctf run stats.run;

#For Windows, use the TNT's command window

mxram 1000 proc Combined.tnt sh Combined_Loncho.ctf run stats.run;

```
