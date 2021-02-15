## Here the following files are provided

**MTORi_sif_cplex_single.txt**: Contains the Benchamrk Analysis result when we ask for one single solution to be provided. In *Source* we have the source of each interaction,
in *Target* column we have the targets of each interaction in the solution and in *Weight* column we have the weights assigned to each interaction based on how often they appear
among the solutions provided (in this case they are all 1 since we have asked for one single solution to be obtained).

**MTORi_sif_cplex_multiple.txt**: Contains the Benchamrk Analysis result when we ask for 100 optimal solutions to be provided. In this case only 18 are provided since this is 
the number of all the optimal solutions that could be enumerated for a zero gap tolerance value. In *Source* we have the source of each interaction, in *Target* column we have 
the targets of each interaction in the solution and in *Weight* column we have the weights assigned to each interaction based on how often they appear among the solutions provided.

**MTORi_sif_cplex_combined.txt**: Contains the Benchamrk Analysis result when we ask for 100 optimal solutions to be provided. In this case only 18 are provided since this is 
the number of all the optimal solutions that could be enumerated for a zero gap tolerance value and all the inferred sites (those that were not measured) were combined into
one node for better visualization. In *Source* we have the source of each interaction, in *Target* column we have the targets of each interaction in the solution and in *Weight* 
column we have the weights assigned to each interaction based on how often they appear among the solutions provided.
