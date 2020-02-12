# SiG Ontology, RDF, LOD

This is the collaborative platform to work together around the topic TEI, RDF, Ontologies and Linked Open Data. 

* The idea is to define all relevant usecase scenarios in which someone wants to transform a TEI document into RDF triples.
* To keep it pragmatic. To see how others are modelling, referencing and working with their data. 
* An open platform to exchange ideas on the topic and collect examples and solutions.
* From my point of view, a completely different topic is to formalize TEI as an ontology. 
* In the Git we can try out and discuss examples, transformations, tools, technologies and so on together and perhaps we can find generic workflows/adaptations in the TEI to deal with these problems.


### Working Mailing List
* subscribe from this page: https://listserv.brown.edu/cgi-bin/wa?SUBED1=TEI-ONTO-SIG&A=1
* or send an email to listserv@listserv.brown.edu with no subject line and the single line in the email body: subscribe TEI-ONTO-SIG your name

### Contact

* Christopher Pollin, (christopher.pollin(at)uni-graz.at)
* Christian-Emil Smith Ore, (c.e.s.ore(at)iln.uio.no)


## Main UseCase-Scenarios

Accordingly different use-scenarios seem to be relevant for me. But that could also be an issue, of course.

### Scenario 1: The whole TEI document is transformed

I'll have to try it out: https://github.com/ajstanley/TEI_to_RDF

### Scenario 2: Already deep-structured elements are transformed to RDF

#### t:biblFull SZD-project.

* http://glossa.uni-graz.at/o:szd.bibliothek/TEI_SOURCE
* http://glossa.uni-graz.at/o:szd.bibliothek/RDF


### Scenario 3: Certain semantic structures in a document are transformed to RDF

#### @ana 

* http://gams.uni-graz.at/context:depcha

## Open tickets in relation to TEI-RDF-LOD-Ontology

A good starting point might be the open tickets at https://github.com/TEIC/TEI/issues, which deal with RDF, LOD, Ontology:

* Encoding RDF relationships in TEI (TEI+RDFa and alternatives): https://github.com/TEIC/TEI/issues/1860
* clarify how to encode short-form citations #1431: https://github.com/TEIC/TEI/issues/1431
* ...

### Scenario 4: ...

## Controlled Vocabularies and Linking

### Scenario 1: References refer to extern taxonomies/vocabularies (Wikidata, GND, VIAF...etc.)

### Scenario 2: The teiHeader/structure inside the teiHeader is the authority / how to publish TEI-Taxonomies

## Further topics of interest (this can of course be extended)

* Ontology alignment (to Upper-Level Ontologies, between Domain-specific Ontologies) like CIDOC-CRM
* Publication of LOD-Data (metaphacts seems to be really cool: https://www.metaphacts.com/product)
* Analysis of Data (InfoVis etc.)
* Retrieval and Discovery od LOD 

## Tools, technologies, data standards

### Define RDF 'inside' XML 

* RDFa: http://rdfa.info/ 
* Borriello, Marta, Christian Dirschl, Axel Polleres, Phil Ritchie, Frank Salliau, Felix Sasaki, und Giannis Stoitsis. „From XML to RDF Step by Step: Approaches for Leveraging XML Workflows  with Linked Data“. In XML Prague 2016. Conference Proceedings, 121–38. Prague, 2016.
* DuCharme, Bob, und John Cowan. „Make Your XML RDF-Friendly“. Xml.Com (blog), 30. Oktober 2002. https://www.xml.com/pub/a/2002/10/30/rdf-friendly.html.


### Transform XML to RDF

* Xtriples: https://xtriples.lod.academy/index.html
* RDFe – expression-based mapping of XML documents to RDF triples: https://www.parsqube.de/publikationen/rdfe-expression-based-mapping-of-xml-documents-to-rdf-triples/
* XSLT 
* ...

#### Validating RDF: 

* SHACL
* ...

## Other Topics

* <graph>
* bibl/@ref
* CIDOC vs. TEI

# Notes 11.11.2019

* 1 Welcome
* 2 Who are we?
* 3 Practicalities: New email list, will be organized either by Brown or ADHO
* 4 New co-convener: Christopher Pollin, Graz
* 5 Common workspace, wiki, github was discussed, no final decision taken.
* 6 Presentation: C-E Ore: Texts and linked data
* 7 What to do next and what to focus?

Some keywords from the discussion:
a) Make and publish XSL examples for transforming elements to rdf in compliance with different conceptual models
b) Study alignment of the TEI elements for real world information and upper level ontologies
c) Use cases of information extraction, enrichment

















