%%%%%%%%%%%%%%%%%%%%% DISCLAIMER %%%%%%%%%%%%%%%%%%%%%\
Under no circumstances shall the uploader be liable for any indirect, incidental, consequential, special or exemplary damage arising out of or in connection with your access or use of or inability to access or use the uploaded data, whether or not the damages were foreseeable and whether or not the user was advised of the possibility of such damages.\
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%\
These repository contains the data corresponding to the publication:
"Efficient Database Generation for Data-driven Security Assessment of Power Systems"
by F Thams, A Venzke, R Eriksson, S Chatzivasileiadis
arXiv preprint arXiv:1806.01074
https://arxiv.org/pdf/1806.01074.pdf


These data collections contains a collection of operating points of the NESTA 162 Bus system classified as N-1 secure and small-signal stable or not.

The Nesta 162 Bus system is part of the "The Nicta Energy System Test Case Archive"

"NESTA, the NICTA energy system test case archive" by
C. Coffrin, D. Gordon, P. Scott in
arXiv preprint arXiv:1411.0359
(https://arxiv.org/pdf/1411.0359.pdf)

Details of the model used and details of the system requirements leading to the classification can be found in the aforementioned paper.
 
Each of the uploaded files contains a 'operation_points' matrix, in which every row represents a single operating point of the NESTA 162 Bus System. The first 12 columns correspond to the 12 generators, the following 284 columns represent the corresponding active power flows,  the following 284 columns represent the corresponding reactive power flows and the last column represents the classification whether the minimal damping ratio of the base case and all N considered contingency is above or equal to 3% (zeta_min >= 3%) (=1) or not (=0). 

The considered contingencies are given as below with each number representing the number of the row of the lines in the mpc.branch matrix.\

br_IDs=[6,8,10,11,12,17,18,22,23,24,25,26,27,30,31,32,36,37,38,39,40,41,43,44,45,47,49,50,51,52,53,54,56,57,62,63,64,65,66,67,68,69,70,73,75,77,85,86,87,89,90,91,92,93,95,96,97,98,100,101,106,107,108,112,113,114,115,116,117,118,122,123,126,127,130,133,136,138,139,140,143,144,145,146,147,148,149,150,151,153,156,157,160,162,165,166,168,169,172,173,174,178,179,186,194,197,202,205,207,209,213,215,224,226,227,229,230,232,234,235,237,238,242,243,244,245,246,247,248,249,250,251,252,253,254,255,256,257,259,260,261,262,263,264,266,267,270,272,273,274,275,276,278,279,282,283]';\
