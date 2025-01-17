# About
This repository contains the implementation code and the intermediate and final results, related to the Master's Thesis: "Constructing a Knowledge Graph for EU Financial Regulations". This Thesis is a graduation prerequisite of the Master of Statistics & Data Science of KU Leuven, Leuven, Belgium. 


# References 

1) The claucy module is installed and utilized as instructed in the public github repo of: https://github.com/mmxgn/spacy-clausie (https://github.com/mmxgn/spacy-clausie.git). The claucy module is required for the main rule-based methodology used in the notebook: "2.Triplets Extraction ClausIE.ipynb", to extract the triplets required for the knowledge graph construction. The claucy_pl.py script is directly imported from the https://github.com/mmxgn/spacy-clausie repo, in order to setup the claucy module locally and implement the clausIE method for IE as described in the paper: https://resources.mpi-inf.mpg.de/d5/clausie/clausie-www13.pdf

2) The code for the REBEL model for knowledge graph construction, is implementeed, following the instructions of https://huggingface.co/Babelscape/rebel-large. 
