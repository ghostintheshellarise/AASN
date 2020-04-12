# Abscisic Acid Signaling Network
<strong>Network interaction recovery using toy data from UCI Machine Learning Repository</strong> (http://archive.ics.uci.edu/ml/datasets/Abscisic+Acid+Signaling+Network)

<b>Abstract:</b> The objective is to determine the set of boolean rules that describe the interactions of the nodes within this plant signaling network. The dataset includes 300 (errata: only 260 distinct similations available in dataset) separate boolean pseudodynamic simulations using an asynchronous update scheme.

Each of the 260 simulations begin with a randomly generated initial condition, in order to ensure sampling of all of the steady states of the system. There are a total of 43 nodes in this dataset, with 5 ndoes being constants (errata: if you are looking at each simulation, the number of fixed nodes varied).

The results for 260 separate simulations are included in the dataset. Each simulation consists of a matrix of 0's and 1's, with 21 rows and 43 columns. The first row is the randomly generated initial condition for the particular simulation, with the next 20 rows being the output from the boolean pseudodynamics simulation. Each of the 43 columns represent the transient response of a particular node. The nodal names are identified at the top of the data file. A line of asterisks is used to separate the simulations from one another.

My work here is using different methods to

a. compute and assign a similarity/importance score to determine which pair of nodes should be joined together and
b. with correct direction of influence extracted.
  
Assumptions are made in each approach and you can find it in respective jupyter notebook.
