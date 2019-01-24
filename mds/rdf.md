# Resrouce Description Framework(RDF)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [What is RDF](#what-is-rdf)
  - [Events](#events)
  - [Timeline of Sementic Web Language](#timeline-of-sementic-web-language)
  - [Graph Model](#graph-model)
  - [Graph Expression in Language](#graph-expression-in-language)
  - [RDF dataset](#rdf-dataset)
  - [Technical Specifications introduced by RDF PRIMER](#technical-specifications-introduced-by-rdf-primer)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## What is RDF
: Framework for representing information(espeically metadata about web resource) in the Web
  - Resouce
  - Description
  - Framework
: For Machine processible, readable, understandable Linked Data from web as database
: Has a [Graph Model](#graph-model)
- RDF Schema
  - RDF Schema gives additional information(Domain, Range) about preoperty.
  - Describe the type(or Class) of Resource. ex)Book, Person, Publisher
- RDF Syntac

### Events
- Mid 1990s: MCF(Meta Content Framework) - Ramanathan V. Guha & Tim Bray
(Apple)
- 1997: MCF/XML - Ramanathan V. Guha & Tim Bray
- 1998: RDF - W3C

### Timeline of Sementic Web Language
- 1970s: Ontology (information science)
- 1996 : XML (W3C WD)
- 1997 : RDF (W3C WD)
- 1998 : RDF Scheme (W3C WD)
- 1999 : DAML
- 1999 : OIL (Europe IST Project)
- 2000 : DAML+OIL
- 2002 : OWL (W3C WD)
- 2004 : SPARQL (WD)

### Graph Model
- Subject --- Predicate ---> Object
- Resource --- Property, Relation ---> Resource, Literal
- URL or Blank Node --- URL ---> URL or Literal
- ex) http:///dbpedia.org/resource/Billie_Jean has a singer whose value is Michael Jackson
  - Subject: http:///dbpedia.org/resource/Billie_Jean (URI)
    - Predicate: http://www.example.com/terms/singer (URI)
    - Object: Michael_Jackson (Literal)
    - +Predicate: http://www.example.com/terms/released (URI)
    - +Object: 1983-01-02 (Literal)
- ex) extension
  - Subject: http:///dbpedia.org/resource/Billie_Jean (URI)
    - Predicate: http://www.example.com/terms/singer (URI)
    - Object: http:///dbpedia.org/resource/Michael_Jackson (URI)
      - Predicate: http://www.example.com/terms/name (URI)
      - Object: Michael_Jackson (Literal)
      - Predicate: http://www.example.com/terms/age (URI)
      - Object: 44 (Literal)
    - Predicate: http://www.example.com/terms/released (URI)
    - Object: 1983-01-02 (Literal)
    
### Graph Expression in Language
- Turtle: a text based format, easy to scribble, easy to read
- JSON-LD
- RDF/XML: an XML based format, hard to read/write

### RDF dataset
- Wikidata: free, from wikimedia
- DBpedia: extracted from Wikipedia infoboxes
- WordNet
- Europeana
- VIAF
- [datahub.io](): List for usable Linked Datasets

### Technical Specifications introduced by RDF PRIMER
- JSON-LD - Manu Sporny, Gregg Kellogg, Markus Lanthaler, Editors. 
  - JSON-LD 1.0 16 January 2014. W3C Recommendation. 
  - URL : http://www.w3.org/TR/json-ld/ 
- LINKED-DATA -  Tim Berners-Lee. Linked Data . Personal View, imperfect but published. 
  - URL : http://www.w3.org/DesignIssues/LinkedData.html 
- N-QUADS - Gavin Carothers. 
  - RDF 1.1 N-Quads. W3C Recommendation 25 February 2014. 
  - URL : http://www.w3.org/TR/2014/REC-n-quads-20140225/. 
  - The latest Edition is available at http://www.w3.org/TR/n-quads/
- N-TRIPLES - Gavin Carothers, Andy Seabourne. 
  - RDF 1.1 N-Triples . W3C Recommendation 25 February 2014. 
  - URL : http://www.w3.org/TR/2014/REC-n-triples-20140225/ . 
  - The latest edition is available at http://www.w3.org/TR/n-triples/ 
- OWL2-OVERVIEW - W3C OWL Working Group. 
  - OWL 2 Web Ontology Language Document Overview (Second Edition) 11 December 2012.  W3C Recommendation. 
  - URL : http://www.w3.org/TR/owl2-overview/ 
- RDF-PRIMER - Frank Manola; Eric Miller. RDF Primer 10 February 2004. W3C Recommendation. 
  - URL : http://www.w3.org/TR/rdf-primer/
- RDF-SYNTAX-GRAMMAR - Fabien Gandon; Guus Schreiber. 
  - RDF 1.1 XML Syntax 9 January 2014. W3C Proposed Edited Recommendation. 
  - URL : http://www.w3.org/TR/rdf-syntax-grammar/
- RDF11-CONCEPTS - Richard Cyganiak, David Wood, Markus Lanthaler. 
  - RDF 1.1 Concepts and Abstract Syntax. W3C Recommendation 25 February 2014. 
  - URL :http://www.w3.org/TR/2014/REC-rdf11-concepts-20140225/ . 
  The latest Edition is available at http://www.w3.org/TR/rdf11-concepts/ 
- RDF11-DATASETS - Antoine Zimmermann. 
  - RDF 1.1 : On Semantics of RDF Datasets . W3C Working Group Note 25 February 2014. 
  - The latest version is available a thttp://www.w3.org/TR/rdf11-datasets/ . 
- RDF11-MT - Patrick J. Hayes, Peter F. Patel-Schneider. 
  - RDF 1.1 Semantics. W3C Recommendation 25 February 2014. 
  - URL : http://www.w3.org/TR/2014/REC-rdf11-mt-20140225/ . 
  - The latest Edition is available at http://www.w3.org/TR/rdf11-mt/ 
- RDF11-NEW - David Wood. 
  - What 's New in RDF 1.1 . W3C Working Group Note 25 February 2014. 
  - The latest version is available at http://www.w3.org/TR/rdf11-new/ . 
- RDF11-SCHEMA - Dan Brickley, RV Guha. RDF Schema 1.1 . 
  - W3C Recommendation 25 February 2014. 
  - URL : http://www.w3.org/TR/2014/REC-rdf-schema-20140225/ . 
  - The latest Published version is available at HTTP : //www.w3.org/TR/rdf-schema/ . 
- RDF11-XML - Fabien Gandon, Guus Schreiber. 
  - RDF 1.1 XML Syntax . W3C Recommendation 25 February 2014. 
  - URL : http://www.w3.org/TR/2014/REC-rdf-syntax-grammar-20140225/ . 
  - The latest published version is available at http://www.w3.org/TR/rdf-syntax-grammar/ . 
- RDFA-LITE -  Manu Sporny. 
  - RDFa Lite 1.1 7 June 2012. W3C Recommendation. 
  - URL : http://www.w3.org/TR/rdfa-lite/ 
- RDFA-PRIME - Ivan Herman; Ben Adida; Manu Sporny; Mark Birbeck. 
  - RDFa 1.1 Primer - Second Edition 22 August 2013. W3C Note. \
  - URL :http://www.w3.org/TR/rdfa-primer/ - 
- RFC3987 - M. Durst; M. Suignard. Internationalized Resource Identifiers (IRIs).
  - January 2005. RFC. 
  - URL : http://www.ietf.org/rfc/rfc3987.txt
- SPARQL11-ENTAILMENT - Birte Glimm; Chimezie Ogbuji. 
  - SPARQL 1.1 Entailment Regimes 21 March 2013. W3C Recommendation. 
  - URL : http://www.w3.org/TR/sparql11-entailment/ 
- SPARQL11-OVERVIEW - The W3C SPARQL Working Group. 
  - SPARQL 1.1 Overview 21 March 2013. W3C Recommendation. 
  - URL : http://www.w3.org/TR/sparql11-overview/ 
- SPARQL11-UPDATE - Paul Gearon; Alexandre Passant; Axel Polleres. 
  - SPARQL 1.1 Update 21 March 2013. W3C Recommendation. 
  - URL :http://www.w3.org/TR/sparql11-update/ 
- TRIG - Gavin Carothers, Andy Seaborne. 
  - W3C Recommendation 25 February 2014. 
  - URL :http://www.w3.org/TR/2014/REC-trig-20140225/ . 
  - The latest Edition is available at HTTP : //www.w3.org/TR/trig/ 
- TURTLE - Eric Prud'hommeaux, Gavin Carothers. 
  - RDF 1.1 Turtle : Terse RDF Triple Language. 
  - W3C Recommendation 25 February 2014. 
  - URL :http://www.w3.org/TR/2014/REC-turtle-20140225/ . 
  - The latest edition is available at http://www.w3.org/TR/turtle/
