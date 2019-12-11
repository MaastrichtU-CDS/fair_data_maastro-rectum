# maastro-rectum

Please see the following files:

* [columnMapping.sparql]: to see all the inserted column mappings (owl:equivalentClass)
* [insertMappings.py]: to see all the inserted mappings for unique, categorical variables in the database.

The ontology, extracted by the [triplifier tool](https://gitlab.com/UM-CDS/fair/tools/triplifier), is given in [ontology.owl].
Additionally, [termMapping.sparql] describes a SPARQL INSERT query to insert mappings for unique, categorical database values. This is based on owl:equivalentClass and owl:Restriction.
