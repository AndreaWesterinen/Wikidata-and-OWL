# Wikidata-and-OWL
Last updated: 20 February 2024

Resources to aid in using Wikidata in an RDF/OWL context.

Currently, there are two notebooks defined:

* Wikidata-Count-Ext-Links.ipynb which counts references to external resources across Wikidata entities that are properties or that are items in a subclassing hierarchy
  * Restricting items to ones in a subclassing hierarchy was done to avoid the many exact match references of instances
* Wikidata-Constraint-Violations.ipynb which returns Wikidata items with mandatory constraint violations (scraped from the web page, https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/Mandatory_constraints/Violations)
  * The Turtle format is explained in the first few cells of the notebook
  * The results are captured (in the file, constraint_violations.ttl) for the violations on 20 February 2024, approximately 6:30pm EST

Additional Turtle files, notebooks and tools will be pushed over the next few months.