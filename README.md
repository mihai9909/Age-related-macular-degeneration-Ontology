# Age-related Macular Degeneration (AMD) Ontology

## Overview

The Age-related Macular Degeneration (AMD) Ontology has been created using Protégé 5.5.0. The ontology is based on the AMD clinical guidelines and the AMD literature. The ontology is designed to represent the AMD domain and to support the development of AMD decision support systems.

## Ontology

The AMD Ontology is available in the [Age-Related Macular Degeneration.rdf](Age-Related Macular Degeneration.rdf) file. The ontology is organized into the following classes:

- AMD
- Aggravation
- Disease
    - AMD=Age-related Macular Degeneration
- Eye part
- Group of people
- Imaging technique
- Sign
    - Early sign
    - Late sign
- Symptom
- Treatment
    - Medical procedure
    - Medication

The ontology includes the following properties:

- affects
- causes
- impairs
- monitors
- treats
- presentIn

## Queries

A dataset of natural language queries and their corresponding SPARQL queries is available in the [Hugging Face repository](https://huggingface.co/datasets/mihai9909/Age-related-Macular-Degeneration-NL2SPARQL).

## License

This ontology is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

