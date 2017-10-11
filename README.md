# pairwiseConnectionInstances
Instances used in the IJOC paper ``Lateness minimization in pairwise connectivity restoration problems" by I. Averbakh and J. Pereira

Instances are organized into two separate folders.

Folder “random” contains the randomly generated instances (described in Section 9.2 of the paper, with results reported in Section 9.3).

Each instance is located in a separate text file. We checked that the files were readable in most common text editors. Some issues were found in windows notepad, and thus we recommend the use of an alternative text editor (like wordpad).

Each instance is named using the following convention: n_x_rdd_y_inst_z, where x represents the number of nodes (such as 5, 6, ..., 100), y represents RDD (such as 0.2, 0.4, ..., 1.0), and z represents the instance number (from 0 to 19).
 
Folder “chilean” contains the instances derived from data on the 2010 Chilean earthquake (results reported in Section 9.4 of the paper).

Each instance is named using the following convention: chilean_rdd_y_inst_z, where y and z have the same meaning as for the random instances.

Each instance is coded as follows: 

Line 1. Number of nodes (n), number of edges (e) and number of relevant pairs (r).

Lines 2 to e+1. Edges. Each line represents an edge. The first two numbers correspond to the end points, the third number is the length of the edge.

Lines e+2 to e+r+1. Relevant pairs. Each line represents a relevant pair. The first two numbers correspond to the nodes and the third number provides the due date.

Note that nodes are numbered from 0 to n-1. Edges are ordered according to non-decreasing edge length, while relevant pairs are ordered according to the numbering of their endpoints.

Additional questions regarding the instances can be addressed to the authors of the paper by email. 



Instances are organized into two separate folders.

Folder “random” contains the randomly generated instances (described in Section 9.2 of the paper, with results reported in Section 9.3).

Each instance is located in a separate text file. We checked that the files were readable in most common text editors. Some issues were found in windows notepad, and thus we recommend the use of an alternative text editor (like wordpad).

Each instance is named using the following convention: n_x_rdd_y_inst_z, where x represents the number of nodes (such as 5, 6, ..., 100), y represents RDD (such as 0.2, 0.4, ..., 1.0), and z represents the instance number (from 0 to 19).
 
Folder “chilean” contains the instances derived from data on the 2010 Chilean earthquake (results reported in Section 9.4 of the paper).

Each instance is named using the following convention: chilean_rdd_y_inst_z, where y and z have the same meaning as for the random instances.

Each instance is coded as follows: 

Line 1. Number of nodes (n), number of edges (e) and number of relevant pairs (r).

Lines 2 to e+1. Edges. Each line represents an edge. The first two numbers correspond to the end points, the third number is the length of the edge.

Lines e+2 to e+r+1. Relevant pairs. Each line represents a relevant pair. The first two numbers correspond to the nodes and the third number provides the due date.

Note that nodes are numbered from 0 to n-1. Edges are ordered according to non-decreasing edge length, while relevant pairs are ordered according to the numbering of their endpoints.

Additional questions regarding the instances can be addressed to the authors of the paper by email. 

 
