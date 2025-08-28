This is the repository of the IN2SIGHT (GA.964481) project WP4 ("In-vivo validation of IN2SIGHT").

It contains at August 2025, two major jupiter codes.
Code_HE: Analysis_Hematoxylin-Eosin_Clustering.ipynb
AND 
Code_NLM: Analysis_NONLINEAR_Clustering.ipynb

Both files assume that the input data have been obtained by applying QuPath (ver: QuPath-0.5.1) to the image to be classified. 
We first use Code_HE to build the Binary Features Vectors (BFV) for as many cell types as possible gthat can be found in the tissue.
Then, we use the QuPath segmentation tool on a non-linear excitation image and apply Code_NLM to the QuPAth output giving in input also the set of BFV for each of the cell types.
