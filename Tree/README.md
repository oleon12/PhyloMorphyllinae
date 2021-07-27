# Tress

Most parsimonious trees from all five <a href="https://github.com/oleon12/PhyloMorphyllinae/tree/main/Matrix" >matrices</a>  in binary format. To read these trees, you have to download the respective matrix data, put the tree, data files and TNT executable in the same directory and run the following command:

```
#For Linux, use the terminal

./tnt mxram 2000 proc Combined.tnt sh Combined.ctf tplot -export Combined.tre;

#For Windows, use the TNT's command window

mxram 1000 proc Combined.tnt sh Combined.ctf tplot -export Combined.tre;

```
