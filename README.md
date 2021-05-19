# BIM-NLQ Dataset for GB-NLQS
This repository includes the data for the research project of natural language query system for graph-based BIM (GB-NLQS). 
The BIM-NLQ dataset is divided into two parts:Part I and Part II.
Part I is used for framework development. It encompasses 110 natural language queries for Model A (70 from authors and 40 from BIM end-users);
Par II is used for testing the GB-NLQS framework. It encompassess 150 natural language queries for Model B,C,D. 
In the folders of Model A,B,C,D, both IFC-SPF file and TTL file(OWL) of the sample models are available. Since the TTL file of Model B and C are large, they are put into the realeases. 
The ground truth answers of the NLQs are not provided because (a)the query results are too large for some queries; (b) there are no gold-programs of the SPARQL queries.
For reuse of the BIM-NLQ dataset for testing, manual check is required to compare the query results against the provided IFC BIM models.  
