# Wikidata-and-OWL
Last updated: 16 March 2024

Resources to aid in using Wikidata in a Semantic Web context.

The current repository holds various documents and notebooks in different subdirectories: 

* _papers_ subdirectory contains the document, __Understanding Wikidata__
  * Abstract: Wikidata is the largest, open, general-purpose and multi-lingual knowledge base currently available. It holds information on over 100M entities  (both concepts, lexemes and instances), and is accessible and editable by both humans and computers. This makes Wikidata extremely valuable as a data source to supplement, validate and extend existing knowledge bases and applications. To effectively utilize Wikidata in a Semantic Web application, one must understand its design, terminology and correspondence with ontological concepts (especially RDF and OWL). Explaining these items is the purpose of this paper.
* _notebooks_ subdirectory holds two Jupyter notebooks:
   * Wikidata-Count-Ext-Links.ipynb which counts references to external resources across Wikidata entities that are properties or that are items in a subclassing hierarchy
     * Restricting items to ones in a subclassing hierarchy was done to avoid the many exact match references of instances
   * Wikidata-Constraint-Violations.ipynb which returns Wikidata items with mandatory constraint violations (scraped from the web page, https://www.wikidata.org/wiki/Wikidata:Database_reports/Constraint_violations/Mandatory_constraints/Violations)
     * The Turtle format is explained in the first few cells of the notebook
     * The results are captured (in the file, constraint_violations.ttl) for the violations on 20 February 2024, approximately 6:30pm EST

Additional Turtle files, papers, notebooks and tools will be published over time.