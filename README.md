AMR Ontology

Introduction

This repository contains a simple ontology on Antimicrobial Resistance (AMR) developed as part of a learning project using Protégé.

The aim of this project was to understand the fundamentals of ontology modelling, represent AMR-related concepts, and perform basic semantic queries using SPARQL.

Ontology Contents

The ontology includes the following classes:

Antibiotic
Pathogen
Organisation
SurveillanceSystem
Policy

Individuals

Antibiotics

Carbapenem
Oxacillin
Vancomycin

Pathogens

E. coli
Klebsiella pneumoniae
MRSA

Organisations

ECDC
RKI

Surveillance Systems

ARS
AVS

Policy

DART2030

Object Properties

The ontology currently includes the following object properties:

resistantTo
monitoredBy
developedBy
implementsPolicy
treats

These properties describe relationships between pathogens, antibiotics, organisations, surveillance systems, and policies.


SPARQL Queries

The repository also contains a collection of example SPARQL queries (`sparql_queries.rq`) used to retrieve information from the ontology, including:

* Listing antibiotics
* Listing pathogens
* Finding resistant pathogen-antibiotic pairs
* Retrieving organisations
* Retrieving surveillance systems



Software Used

* Protégé 5.6.9
* OWLViz
* OntoGraf
* SPARQL Query Plugin

---

## Repository Files

```
AMR_ontology.rdf
sparql_queries.rq
README.md
```

---

## Author

Yadvinder Kaur

M.Sc. Global Public Health

Deggendorf Institute of Technology, Germany
