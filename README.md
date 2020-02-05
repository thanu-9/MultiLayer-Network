# Functional-Multiplex-PageRank

%++++++++ Functional Multiplex PageRank ++++++++++++++++++++++++++++

This folder contains MATLAB codes for calculating the 
Functional Multiplex PageRank:

) MultiRank_Nodes_Layers .m
the actual MultiRank algorithm generating a ranking of node and a ranking of layers for every parameter values
gamma, s, a.
2) MultiRank.m evaluating the Multirank for different values of gamma in the interval (0,3) for  given values of s and a.
3) MultiRank_plots.m is the code to generate the plots of the top rank nodes and layers

4) The datasets of the European Air Multiplex Transportation Network
EUAirTransportation_layers.txt
EUAirTransportation_nodes.txt
EUAir Transportation_multiplex.edges

5) The file read_airports.m to read the above dataset and put in in the format to be read by the MATLAB codes.


6) functionalPageRank_duplex.m

	calculating the Functional Multiplex PageRank of a duplex 
	network given the influence vector z=[z^(1,0),z^(0,1),z^(1,1)].

7) fPR.m

	calculating the Functional Multiplex PageRank of a duplex network 
	for all values of the influence vector.
	This code makes use of the code functionalPageRank_duplex.m
	
8) functionalPageRank_multiplicity.m

	calculating the Functional Multiplex PageRank of a multiplex network 
	with arbitrary number of layers and with a specific influence vector 
	depending only of the multiplicity of the overlap of the links.

9) fPRm.m

	calculating the Functional Multiplex PageRank of a multiplex network 
	with arbitrary number of layers with varying influence parameters.
	This code makes use of the code functionalPageRank_multiplicity.m


These codes are produced by the following people in the reference.

Reference:

 [1]   C. Rahmede, J.Iacovacci, A. Arenas and G. Bianconi, 
"Centralities of Nodes and Influences of Layers in Large Multiplex Networks"
 arxiv:1703.05833 (2017).

 [2]  J. Iacovacci, C. Rahmede, A. Arenas and G. Bianconi, "Functional Multiplex PageRank." 
        arxiv:1608.06328 (2016)  

 (c) Jacopo Iacovacci (mriacovacci@hotmail.it) 
     Christoph Rahmede (c.rahmede@kit.edu)
     Ginestra Bianconi (g.bianconi@qmul.ac.uk)  
