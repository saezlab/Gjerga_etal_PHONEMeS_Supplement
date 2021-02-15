## Here the following files are provided

**ednrb_network.txt:** The file contains the network solution after performing the PHONEMeS-mult analysis over the time-course EDNRB phosphorylation data. The network file
consists of a table with 4 columns. The *Source* column contains the protein ID's of the sources of each interaction, the *f50* column contains the weight associated to each of
the interactions in the network (that is how frequently an interaction appears across 100 solutions), the *tp* column contains the time-point ID in which an interaction
appears to become functional, and the *Target* column which contains the targets of each interaction.

**ednrb_network_20.txt:** The file contains the network solution with the most robust interactions of the ednrb_network (f50>=20).

**ednrb_attributes.txt:** The file contains the attributes associated with each node in the network for better visualization with [Cytoscape](https://cytoscape.org/). This table
has two columns. The *Species* column contains the protein ID's of each node/protein in the network while the *nodesP* column contains the attributes which can be assigned to each
of the nodes (D - target nodes; P - perturbed sites; NaN - inferred node).
