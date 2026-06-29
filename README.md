# AMR Ontology

## Overview

This project presents a simple OWL ontology for Antimicrobial Resistance (AMR) developed using Protégé.

The ontology models the relationships between:

- Antibiotics
- Pathogens
- Surveillance Systems
- Organisations
- Policies

The project also demonstrates SPARQL queries for retrieving ontology information.

---

## Ontology Structure

### Classes

- Antibiotic
- Pathogen
- Organisation
- SurveillanceSystem
- Policy

### Individuals

Antibiotics
- Carbapenem
- Oxacillin
- Vancomycin

Pathogens
- MRSA
- E_coli
- K_pneumoniae

Organisations
- WHO
- ECDC
- RKI

Surveillance Systems
- ARS
- AVS

Policies
- DART2030

---

## Object Properties

- resistantTo
- monitoredBy
- developedBy
- implementsPolicy
- treats

---

## SPARQL Queries

Example queries included:

- List all antibiotics
- List all pathogens
- Retrieve resistant pathogen-antibiotic pairs
- Retrieve surveillance systems
- Retrieve organisations

The queries are available in:

```
sparql_queries.rq
```

---

## Software

- Protégé 5.6.9
- OWL API
- SPARQL Query Plugin
- OntoGraf
- OWLViz

---
## Ontology Visualization

The figure below shows the ontology structure created in Protégé.

![OntoGraf](screenshots/ontograf.png)

## Author

Yadvinder Kaur

M.Sc. Global Public Health

Deggendorf Institute of Technology

Germany
