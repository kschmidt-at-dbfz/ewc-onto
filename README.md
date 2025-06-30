# European Waste Catalogue Ontology

## Intoduction

The ewc-onto is the translation of the [European Waste Catalogue](http://data.europa.eu/eli/dec/2014/955/oj) (EWC) into an ontology. The hierarchy from the EWC was completely preserved, which means the ontology includes the 20 top-level categories (waste classes), subordinated the waste groups per waste class and usually as lowes level the residues per waste group. In the implementation of the EWC in the German law, four residue categories have an additional layer. This structure results in 991 classes in the ontology. These classes are named by their waste code from the EWC, which is two numbers per layer, and by their human understandable description. In this version (v1.0) English and German language are available. The structure of the ontology is depicted in Fig. 1.

![ewc-onto](docs/OntoPic_DetailAgriculture.png)

*Fig. 1. A view on the waste class 02 (wastes from agriculture, ...) as an example for the structure of the ontology.*

The information about the hazardousness, which is also included in the EWC, is implemented as an additional class in the ontology with two subclasses. The third layer of the waste tree is connected to the hazardousness tree.

## How to use

The ontology was developed with [Protégé](https://protege.stanford.edu/) and can be openend and transformed into other data types (owl, rdf) there without any problems.

## References
- [European Wase Catalogue](http://data.europa.eu/eli/dec/2014/955/oj) (2014/955/EU: Commission Decision of 18 December 2014 amending Decision 2000/532/EC on the list of waste pursuant to Directive 2008/98/EC of the European Parliament and of the Council Text with EEA relevance) from December 30 2014

## See also
- [An ontology to identify biogenic wastes and residues from bioeconomy](https://doi.org/10.37307/j.1863-9763.2025.06.03), published June 11 2025, publication language German
