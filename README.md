# Non-parametric MANOVA (Permanova) with bootstraps

Used in [Zrimec & Lapanje 2018: DNA structure at the plasmid origin-of-transfer indicates its potential transfer range](https://www.nature.com/articles/s41598-018-20157-y)

The Permanova method (Anderson et al. 2001) implemented in Matlab.
Bootstraps of input sequences are generated as permutations for the background distributions.

main script - create bootstraps, 
a. call main functions, calculate p-value (to do upload script) 
b. F calculaton with distance matrix input 
c. F calculation with sequence input and distances between all character pairs defined by second input matrix
