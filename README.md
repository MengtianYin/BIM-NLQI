# BIM-NLQ Dataset for NLQ4BIM
This repository includes the data for the research project of natural language query for BIM (NLQ4BIM). 
The BIM-NLQ dataset is divided into two parts:Part I and Part II.
Part I is used for framework development. It encompasses 110 natural language queries for Model A (70 from authors and 40 from BIM end-users);
Par II is used for testing the NLQI4BIM. It encompassess 225 natural language queries for Model B,C,D.

In the folders of Model A,B,C,D, both IFC-SPF file and TTL file(OWL) of the sample models are available. Since the TTL file of Model B and C are large, they are put into the realeases. 

The ground truth answers of the NLQs are not provided because (a)the query results are too large for some queries; (b) there are no gold-programs of the SPARQL queries.
For reuse of the BIM-NLQ dataset for testing, manual check is required to compare the query results against the provided IFC BIM models.  

The ontology files in the folder only include the INLE ontology and the populated RDF files placed in each model folder (A,B,C,D). The INLE ontology resued the ontological resource from the ifcOWL ontology (IFC2x3 TC1), which can be found in https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/.   

The file "bimnlq.ttl" contains all the SPIN reasoning rules that were created in this study. Additionally, this study also resue the reasoning rules from the BIMSPARQL framework, which can be found in https://github.com/BenzclyZhang/BimSPARQL .
