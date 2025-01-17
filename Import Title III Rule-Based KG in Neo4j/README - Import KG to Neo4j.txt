The "Final_Rule_Based_KG_Title_III.graphml" graphml file should first be placed in the "Import" folder of the active Graph DBMS

Neo4j Desktop -> Current Graph DBMS -> ... -> Open Folder -> Import 

The following commands need to be executed in separate cells:

CALL apoc.import.graphml("Final_Rule_Based_KG_Title_III.graphml", {readLabels: true})

MATCH p=()-->()
RETURN p