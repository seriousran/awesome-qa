# Relation Extraction

## Publications
- ["REXTOR: A System for Generating Relations from Natural Language"](http://www.anthology.aclweb.org/W/W00/W00-1107.pdf), Boris Katz and Jimmy Lin, ACL, 2000.
  - The application of natural language processing (NLP) techniques to information retrieval promises to generate representational structures that better capture the semantic content of documents. 
  In particular, syntactic analysis can highlight the relationships between various terms and phrases in a sentence, which will allow us to distinguish between the example pairs given above and answer queries with higher precision than traditional IR systems. 
  However, a syntactically-informed representational structure faces the problem of Hnguistic variations, the phenomenon in which similar semantic content may be expressed in different surface forms.  
  - REXTOR(Relations EXtracTOR) provides two separate grammars: one for extracting arbitrary entities from documents, and the other for building relations from the extracted items. 
  
  ![](images/img-001.png)
  
  - relation and extraction rules
    ```
    Eztraction Rules:
      NounGroup := (PRPZ|DT)? {JJX*} {(NNPX|NNX|NNPS|NNS)+};
      PrepositionalPhrase := IN {NounGroup} ;
      ComplexNounGroup := {NounGroup} {PrepositionalPhrase};
    Relation Rules:
      NounGroup :=> <{0} 'describes' [1]>;
      ComplexNounGroup :=>
        <[0],NounGroup[1]
        ;related-to;
        [1],PrepositionalPhrase[0], NounGroup[1]>; 
    ```
    PRPZ: part-of-speech tag for possessive pronouns
    DT: " for determiners
    JJX: " for adjectives
    JJR: " for comparative adjectives
    JJS: " for uperlative adjectives
    NNX: " for singular or mass nouns
    NNS: " for plural nouns
    NNPX: " for singular proper nouns
    NNPS: " for plural proper nouns
    IN: " for prepositions
    
