AMR Ontology
Overview

This project presents an OWL ontology for Antimicrobial Resistance (AMR) surveillance developed in Protégé. The ontology models the relationships between bacterial isolates, pathogens, resistance genes, resistance mutations, resistance phenotypes, antibiotics, surveillance systems, healthcare facilities, organizations, and national AMR policies.

Ontology Extension

The ontology was extended from a simple classification model to include isolate-level semantic relationships, enabling a more meaningful representation of AMR surveillance data.

An example bacterial isolate (Example_Isolate_001) demonstrates how multiple AMR entities can be connected within a single knowledge graph.

The example isolate is linked to:

Species: Klebsiella pneumoniae
Resistance Gene: blaKPC-2
Resistance Mutation: ompK36 Loss of Function
Resistance Phenotype: Carbapenem Resistant
Antibiotic: Carbapenem
Sequence Type: ST258
Healthcare Facility: Hospital_A
Surveillance System: ARS
Object Properties

The ontology includes semantic relationships such as:

belongsToSpecies
carriesGene
hasMutation
hasPhenotype
resistantTo
hasSequenceType
collectedAt
reportsTo
associatedWithResistanceTo
confersResistanceTo
monitors
coordinates
governs
Example Knowledge Graph

The OntoGraf visualization demonstrates how an individual bacterial isolate connects genomic, phenotypic, clinical and surveillance information into a single semantic network.

This allows queries such as:

Which genes are associated with carbapenem resistance?
Which bacterial species carry blaKPC-2?
Which hospitals report isolates to ARS?
Which sequence types are associated with specific resistance phenotypes?
Repository Contents
AMR_ontology.rdf — RDF/XML ontology
AMR_Ontology.owx — Protégé project
sparql_queries.rq — Example SPARQL queries
OntoGraf screenshots
Software
Protégé
OWL 2
RDF/XML
OntoGraf
