Knowledge Graph Import Instructions:

1. The "Final_Rule_Based_KG_Title_III.graphml" graphml file should first be placed in the "Import" folder of the active Graph DBMS (Neo4j Desktop -> Current Graph DBMS -> ... -> Open Folder -> Import)
2. The APOC Pluggin of the Neo4j DBMS Instance needs to be Installed 
3. The following line: apoc.import.file.enabled=true needs to be manually added to the configuration file of the Neo4j DBMS Instance (Neo4j Desktop -> Current Graph DBMS -> ... -> Open Folder -> Configuration)
4. Neo4j GRAPH DBMS Versions that the database import was tested on were 4.4.0 and 4.1.0
5. The commands below should be executed in separate cells of the Neo4j Desktop

CALL apoc.import.graphml("Final_Rule_Based_KG_Title_III.graphml", {readLabels: true})

MATCH p=()-->()
RETURN p
