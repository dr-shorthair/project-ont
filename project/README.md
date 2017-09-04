# ont/project
A core vocabulary for describing a project, any kind of project.

The goal is a 'core' ontology which can be extended for more domain specific applications. The design is influenced by
* VIVO-ISF http://vivoweb.org/ontology/core
* dbPedia http://dbpedia.org/ontology/Project

plus requirements from TDWG through the PPSR project.

The goal is project description, not project management. The core Project class is modeled as a specialization of the Activity class from PROV-O http://www.w3.org/ns/prov-o, adding properties commonly required for describing projects. Otherwise, the Project ontology has no dependencies except for the standard RDF/OWL infrastructure.

Alignments with FOAF, DOAP, and other project ontologies will be considered.
