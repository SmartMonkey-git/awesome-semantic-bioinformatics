# Awesome Semantic Bioinformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated collection of tools, libraries, data standards, and repositories aimed at bridging the gap between the Semantic Web, knowledge graphs, and the biological sciences.

## Table of Contents
- [Infrastructure](#infrastructure)
- [Phenpacket Curation](#phenopacket-curation)
- [Text Mining](#text-mining)
- [Semantic Similarity](#semantic-similarity)
- [Statistical Tools](#statistical-tools)
- [Visualization](#visualization)
- [Resources](#resources)

## Infrastructure
##### Rust
- [ontology-registry](https://github.com/P2GX/ontology-registry) - Thread-safe, atomic downloading and local caching of OBO/BioRegistry files.
- [ontolius](https://github.com/ielis/ontolius) - A fast and safe crate for working with biomedical ontologies.
- [fastobo](https://github.com/fastobo/fastobo) - An OBO format parser and abstract syntax tree crate for Rust. Highly synergistic with tools like ontolius.
- [securiety](https://github.com/SmartMonkey-git/securiety) - A robust Rust crate for parsing and validating or parsing Compact Uniform Resource Identifiers (CURIEs).
- [drug-central-rs](https://github.com/SmartMonkey-git/drug-central-rs) - A Rust library for automating the setup, management, and querying of a DrugCentral PostgreSQL database.

##### Python
- [Pyphetools](https://github.com/VarenyaJ/2024-pyphetools-archive) - A mirror of the core utility for using the Python version of the phenopackets package together with pandas to create phenopackets from typical supplemental tables. **[Original Repository was removed from Github and PyPi package is under quarantine due to a worm attack](https://github.com/P2GX/prenatalppkt/issues/73)**
- [Phenopacket Store Toolkit](https://github.com/monarch-initiative/phenopacket-store-toolkit.git) - Toolkit for accessing, Q/C, and maintenance of Phenopacket Store
- [hpo-toolkit](https://github.com/ielis/hpo-toolkit) - A toolkit for working with Human Phenotype Ontology (HPO) and HPO disease annotations in Python.
- [oaklib](https://pypi.org/project/oaklib/) - Ontology Access Kit (OAK): A powerful Python library by the Monarch Initiative for accessing, querying, and manipulating ontologies.
- [RareLink](https://github.com/BIH-CEI/rarelink) - A REDCap-based framework for rare disease interoperability linking international registries to HL7 FHIR and GA4GH Phenopackets.
- [OVEr](https://github.com/P2GX/OVEr) - OVEr converts biomedical ontologies into semantic vector embedding databases, enabling accurate ontology term retrieval through natural language similarity search.
- [pronto](https://github.com/althonos/pronto) - A highly popular Python frontend to ontologies, designed to seamlessly parse OBO and OWL formats into Python objects.
- [pyobo](https://github.com/biopragmatics/pyobo) - A comprehensive tool for downloading, standardizing, and accessing nomenclature from OBO ontologies.

##### Java
- [ROBOT](https://github.com/ontodev/robot) - The definitive command-line tool for working with OWL ontologies. It is the gold standard used by the OBO Foundry for ontology automated builds and CI/CD pipelines.

##### Agnostic
- [BioRegistry](https://github.com/biopragmatics/bioregistry) - A community-driven integrative meta-registry of life science databases, ontologies, and other resources.

## Phenopacket Curation
##### Rust
- [PhenoXtract](https://github.com/P2GX/PhenoXtract) - PhenoXtract is a configurable ETL (Extract-Transform-Load) pipeline and crate written in Rust for converting tabular data sources (e.g. CSV or Excel) into Phenopackets v2.0.
- [phenoboard](https://github.com/P2GX/phenoboard) - Curation of individuals with Human Phenotype Ontology and GA4GH Phenopacket Schema.

##### Python
- [RareLink](https://github.com/BIH-CEI/rarelink) - A REDCap-based framework for rare disease interoperability linking international registries to HL7 FHIR and GA4GH Phenopackets.
- [PrenatalPPKT](https://github.com/P2GX/prenatalppkt.git) - A Python library for transforming raw prenatal sonography data into standardized GA4GH Phenopackets v2

## Text Mining
##### Rust
- [fenominal](https://github.com/P2GX/fenominal) - NLP tool to extract ontology terms from free text based on the BLAST algorithm.

##### Python
- [DEFTMatcher](https://github.com/psnairne/DEFTMatcher) - Dextrous and Extensible Free Text Matcher.

## Semantic Similarity
##### Rust
- [Phrank](https://github.com/SmartMonkey-git/phrank-rs) - Phrank is a high-performance, phenotype-driven similarity engine designed to calculate the similarity between patient cohorts.

##### Python
- [Phrank](https://github.com/SmartMonkey-git/phrank-rs) - Phrank is a high-performance, phenotype-driven similarity engine designed to calculate the similarity between patient cohorts.
- [setsim](https://github.com/P2GX/setsim) - A proof of concept of the summing similarity measure.

## Statistical Tools
##### Rust
- [Ontologizer](https://github.com/P2GX/ontologizer) - Fast and safe implementation of the Ontologizer — a tool for Gene Ontology (GO) enrichment analysis using Frequentist (hypergeometric test) or Bayesian (inference) methods.

##### Python
- [gpsea](https://github.com/P2GX/gpsea) - Python package for finding genotype-phenotype associations.
- [ppkt2synergy](https://github.com/P2GX/ppkt2synergy) - ppkt2synergy is a Python library for analyzing correlations and synergy in GA4GH Phenopacket cohorts.
- [PhEval](https://github.com/monarch-initiative/pheval.git) - A framework for empirical evaluation of phenotype matching and prioritisation.

##### Java
- [maxodiff](https://github.com/P2GX/maxodiff) - Medical Action Ontology terms for differential diagnosis.
- [Exomiser](https://github.com/exomiser/Exomiser.git) - A Tool to Annotate and Prioritize Exome Variants.
- [LIRICAL](https://github.com/TheJacksonLaboratory/LIRICAL) - LIRICAL (LIkelihood Ratio Interpretation of Clinical AbnormaLities) is designed to provide clinically interpretable computational analysis of phenotypic abnormalities.

## Visualization
##### Python
- [phenoblend](https://github.com/P2GX/phenoblend) - Phenoblend is an HPO-based phenotype–genotype visualization library.

## Resources
#### Datasets
- [Phenopacket Store](https://github.com/monarch-initiative/phenopacket-store.git) - Collections of GA4GH phenopackets that represent individuals with Mendelian diseases.

#### Standards
- [Phenopackets](https://github.com/ga4gh/phenopacket-schema) - An open standard for sharing disease and phenotype information.
- [Biolink Model](https://github.com/biolink/biolink-model) - A high-level, open-source data model for the standardization of biological and biomedical knowledge graphs.
- [OBO Foundry](https://github.com/OBOFoundry/OBOFoundry.github.io) - The Open Biological and Biomedical Ontology (OBO) Foundry principles, which set the gold standard for interoperable biological ontologies.

#### Ontologies
- [HPO](https://github.com/obophenotype/human-phenotype-ontology) - The Human Phenotype Ontology (HPO) provides a standardized vocabulary of phenotypic abnormalities encountered in human disease.
- [MONDO](https://github.com/monarch-initiative/mondo) - MonDO (Monarch Disease Ontology) is a semi-automatically constructed ontology that merges in multiple disease resources to yield a coherent merged ontology.
- [MAxO](https://github.com/monarch-initiative/MAxO) - The Medical Action Ontology (MAxO) provides a broad view of medical actions and includes terms for medical procedures, interventions, therapies, treatments, and recommendations.
- [Gene Ontology (GO)](https://github.com/geneontology/go-ontology) - The foundational resource for computational biology, providing a framework for the model of biology defining gene functions across species.
- [UBERON](https://github.com/obophenotype/uberon) - An integrated cross-species anatomy ontology representing a variety of entities classified according to traditional anatomical criteria. Highly synergistic with HPO and MONDO.
