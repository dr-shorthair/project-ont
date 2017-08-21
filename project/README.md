# ont/project
A core vocabulary for describing a project, any kind of project.

The goal is a 'core' ontology which can be extended for more domain specific applications. The design is influenced by
* VIVO-ISF http://vivoweb.org/ontology/core
* dbPedia http://dbpedia.org/ontology/Project

plus requirements from TDWG through the PPSR project.

Though the intention is to provide a re-usable ontology pattern with minimal dependencies, it was hard to look past PROV-O http://www.w3.org/ns/prov-o, specifically the prov:Activity class as a basis for a Project class, because of
1. its essence as a time-bounded thing with outputs
1. support for rich relationships with Agents and Entities

so a dependency on PROV-O is built in to the initial strawman at least. 

The goal is project description, not project management.

Alignments with FOAF, DOAP, and other project ontologies will be considered.
