# Covid-19-strongly-connected-components
Kosaraju's Strongly connected component (SCC) algorithm is used  for human protein pathways invoved in covid-19 infection.
Code implementation of SCC by Eric M.Fischer:

https://github.com/EricMFischer/strongly-connected-comp

We identified IL-2, IL-7, IL-9 and IL-15 as key molecules in covid-19 induced cytokine storm (see Huang et al. 2020).

We searched IntAct (https://www.ebi.ac.uk/intact/) of EMBL-EBI for human protein interactions (see index_humanpr_name.txt) and derived data for SCC evaluation (pid_nr.txt and pid_nr1.txt).

Output of SCC (see scc_result.txt) is evaluated and significant protein interactions are identified (pid_nr_res5.txt).
Paper Detailing this study is under preparation.

Huang,C, Wang,Y, Li,X, Ren,L, Zhao,J, Hu,Y, Zhang,L. 2020.Clinical features of patients infected with 2019 novel coronavirus in Wuhan, China. Lancet. 395: 497-506.
