## What is RDF
: Framework for representing information(espeically metadata about web resource) in the Web
- Resouce
- Description
- Framework
: for Machine processible, readable, understandable Linked Data from web as database
: has a [Graph Model](#graph-model)

### Events
- mid 1990s: MCF(Meta Content Framework) - Ramanathan V. Guha & Tim Bray
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
