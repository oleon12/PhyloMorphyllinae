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
  1. **Combined_Loncho.ctf:** The most parsimonious trees in binary format.
  2. **Combined_Loncho.tre:** The most parsimonious trees in Nexus format.
  3. **Combined_Loncho_jack.tre:** The most parsimonious trees in Nexus format, after the Jackknife resampling (not useful).
  4. **Combined_Loncho_sym.tre:** The most parsimonious trees in Nexus format, after the Symmetric resampling (not useful).
  5. **Combined.txt:** The log file from the run. It displays all the information that TNT generates, useful if you wanna see Scores, Indices, etc ...
