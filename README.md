# Model-of-Pleistocene-Glacial-Cycles
Supplementary to ESD paper 
"A Theory of Pleistocene Glacial Rhythmicity" by MY Verbitsky, M Crucifix, DM Volobuev
Accepted for publication in Earth System Dynamics (2018).

This package presents the supplementary MatLab scripts to reproduce results of the paper

Scripts were tested under MatLab R2015b.

Usage: unpack folders “Script 1”, ‘’Script 2”, Script 3”, each folder contains all necessary data.

Please, run script run_V….m in specified folder to reproduce figures of the paper. Please change parameters of the model inside the script:   

Fig. 2 left: Script 1, g2=0.2, g3=0.25, e=0.

Fig. 2 right: Script 1, g2=0.2, g3=0.25, e=0.01

Figs. 3, 4, 5 (low left, low right), 6: Script 1

Fig. 7: Script 2, e=0.07, 0.082, 0.11

Fig. 8: Script 1 alpha=0, k=0, e=0.03

Fig. 9: Script 2 alpha=0, k=0, e=0.045; FS=e*(1.*sin(2.*pi*t/23.)+0.*sin(2.*pi*t/41.));

Fig. 10: Script 1 alpha=0, k=0, e=0.11, S0=2, Y0 = [3.5 0. 2.]

Fig. 11: Script 1 b=1.57

Fig. 12 Script 3
