<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Relation Extraction](#relation-extraction)
  - [Contents](#contents)
  - [Publications](#publications)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Relation Extraction

## Contents
- [A Survey of Deep Learning Methods for Relation Extraction](#pb1), 2017 (Citations: 6)
- [Joint extraction of entities and relations using reinforcement learning and deep learning](#pb2), 2017 (Citations: 2)
- [On the recursive neural networks for relation extraction and entity recognition](#pb3), 2013 (Citations: 6)
- [Relation extraction and scoring in DeepQA](#pb4), 2012 (Citations: 58)
- [Automatic knowledge extraction from documents](#pb5), 2012 (Citations: 123)
- [PRISMATIC: inducing knowledge from a large scale lexicalized relation resource](#pb6), 2010 (Citations: 35)
- [A review of relation extraction](#pb7), 2007 (Citations: 118)
- [REXTOR: A System for Generating Relations from Natural Language](#pb8), 2000 (Citations: 83)

## Publications
- #### <a name="pb1"></a> ["A Survey of Deep Learning Methods for Relation Extraction"](https://arxiv.org/pdf/1705.03645.pdf), Kumar, Shantanu, arXiv preprint, 2017. (Citations: 6)

- #### <a name="pb2"></a> ["Joint extraction of entities and relations using reinforcement learning and deep learning"](https://pdfs.semanticscholar.org/e0e5/9f42cfda8d34310adaa69f708db07c99b06f.pdf), Feng, Y., Zhang, H., Hao, W., & Chen, G, Computational intelligence and neuroscience, 2017. (Citations: 2)

- #### <a name="pb3"></a> ["On the recursive neural networks for relation extraction and entity recognition"](https://arxiv.org/pdf/1705.03645.pdf), Khashabi, Daniel, Computational intelligence and neuroscience, 2013. (Citations: 6)

- #### <a name="pb4"></a> ["Relation extraction and scoring in DeepQA"](http://brenocon.com/watson_special_issue/09%20relation%20extraction%20and%20scoring.pdf), C. Wang, A. Kalyanpur, J. Fan, B. K. Boguraev, and D. C. Gondek, IBM Journal, 2012. (Citations: 58)
  - Rule-based relation extraction
  - Statistical approaches for relation extraction and passage scoring'
  
- #### <a name="pb5"></a> ["Automatic knowledge extraction from documents"](http://brenocon.com/watson_special_issue/05%20automatic%20knowledge%20extration.pdf), J. Fan, A. Kalyanpur, D. C. Gondek, and D. A. Ferrucci, IBM Journal, 2012. (Citations: 123)
  - PRISMATIC is used as a knowledge resource for QA in Watson
  - PRISMATIC is built using a suite of natural-language processing (NLP) tools that include a dependency parser, a rule-based NER, and a co-reference resolution component. The PRISMATIC creation process consists of three phases.
    1. Corpus processingVDocuments are annotated by a suite of components that perform dependency parsing, co-reference resolution, NER, and relation detection.
    2. Frame extractionVFrames are extracted on the basis of the dependency parses and associated annotations. This phase implements the first stage of our approach.
    3. Frame projectionVFrame projections of interest (e.g., S-V-O projections) are identified over all frames, and frequency information for each projection is tabulated. This phase produces the aggregate statistics from the extracted frames used to infer additional semantics.
    
- #### <a name="pb6"></a> ["PRISMATIC: inducing knowledge from a large scale lexicalized relation resource"](https://dl.acm.org/citation.cfm?id=1866790), J Fan, D Ferrucci, D Gondek, A Kalyanpur, NAACL HLT, 2010. (Citations: 35)
  - This paper presents PRISMATIC, a large scale lexicalized relation resource that is automatically created over 30 gb of text.
  - The authors' focus has been on building the infrastructure and gathering the data.
  
  ![](/images/img-002.png)
  
- #### <a name="pb7"></a> ["A review of relation extraction"](https://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction.pdf), Bach, Nguyen, and Sameer Badaskar, iterature review for Language and Statistics II, 2007. (Citations: 118)
   
- #### <a name="pb8"></a> ["REXTOR: A System for Generating Relations from Natural Language"](http://www.anthology.aclweb.org/W/W00/W00-1107.pdf), Boris Katz and Jimmy Lin, ACL, 2000. (Citations: 83)
  - The application of natural language processing (NLP) techniques to information retrieval promises to generate representational structures that better capture the semantic content of documents. 
  In particular, syntactic analysis can highlight the relationships between various terms and phrases in a sentence, which will allow us to distinguish between the example pairs given above and answer queries with higher precision than traditional IR systems. 
  However, a syntactically-informed representational structure faces the problem of Hnguistic variations, the phenomenon in which similar semantic content may be expressed in different surface forms.  
  - REXTOR(Relations EXtracTOR) provides two separate grammars: one for extracting arbitrary entities from documents, and the other for building relations from the extracted items. 
  
  ![](/images/img-001.png)
  
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
