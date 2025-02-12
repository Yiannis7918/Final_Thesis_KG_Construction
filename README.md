# About
This repository contains the implementation code and the intermediate and final results, related to the Master's Thesis: "Constructing a Knowledge Graph for EU Financial Regulations". This Thesis is a graduation prerequisite of the Master of Statistics & Data Science of KU Leuven, Leuven, Belgium. 

# Import the Final Rule-Based Knowledge Graph in Neo4j

The simple and fast instructions to load the Title III: Establishment and Structure of the Budget of the Financial Regulations Knowledge Graph are located in the "Import Title III Rule-Based KG in Neo4j" folder of this repository

# How to Interpret and Read this Repository 

1) This repository contains the implementation code around knowledge grah construction. 
 



# References 

1) The claucy module is installed and utilized as instructed in the public github repo of: https://github.com/mmxgn/spacy-clausie (https://github.com/mmxgn/spacy-clausie.git). The claucy module is required for the main rule-based methodology used in the notebook: "2.Triplets Extraction ClausIE.ipynb", to extract the triplets required for the knowledge graph construction. The claucy_pl.py script is directly imported from the https://github.com/mmxgn/spacy-clausie repo, in order to setup the claucy module locally and implement the clausIE method for IE as described in the paper: https://resources.mpi-inf.mpg.de/d5/clausie/clausie-www13.pdf

2) The code for the REBEL model for knowledge graph construction, is implemented, following the instructions of https://huggingface.co/Babelscape/rebel-large. 
