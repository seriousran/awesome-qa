# awesome-qa [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) 

_A curated list of the __Question Answering (QA)__ subject which is a computer science discipline within the fields of information retrieval and natural language processing (NLP)_

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [About QA](#about-qa)
  - [types of QA](#types-of-qa)
  - [Anlaysis and Parsing for Pre-processing in QA systems](#anlaysis-and-parsing-for-pre-processing-in-qa-systems)
  - [most QA systems have roughly 3 parts](#most-qa-systems-have-roughly-3-parts)
- [Events](#events)
- [Systems](#systems)
- [Codes](#codes)
- [Lectures](#lectures)
- [Slides](#slides)
- [Dataset Collections](#dataset-collections)
- [Datasets](#datasets)
- [Running Competitions in QA](#running-competitions-in-qa)
- [Concluded Competitions in QA](#concluded-competitions-in-qa)
- [Publications](#publications)
  - [The DeepQA Research Team in IBM Watson's publication within 5 years](#the-deepqa-research-team-in-ibm-watsons-publication-within-5-years)
  - [MS Research's publication within 5 years](#ms-researchs-publication-within-5-years)
  - [Google AI's publication within 5 years](#google-ais-publication-within-5-years)
  - [Facebook AI Research's publication within 5 years](#facebook-ai-researchs-publication-within-5-years)
- [Books](#books)
- [Links](#links)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## About QA
### types of QA
- Single-turn QA: answer without considering any context
- Conversational QA: use previsous conversation turns
#### subtypes of QA
- Knowledge-based QA
- Table/List-based QA
- Text-based QA
- Community-based QA
- Visual QA

### Anlaysis and Parsing for Pre-processing in QA systems
Lanugage Analysis
  1. [Morphological analysis](https://www.cs.bham.ac.uk/~pjh/sem1a5/pt2/pt2_intro_morphology.html)
  2. [Named Entity Recognition(NER)](mds/named-entity-recognition.md)
  3. Homonyms / Polysemy Analysis
  4. Syntactic Parsing (Dependency Parsing)
  5. Semantic Recognition

### most QA systems have roughly 3 parts
1. Fact extraction <br/>
    1. Entity Extraction <br/>
        1. [Named-Entity Recognition(NER)](mds/named-entity-recognition.md)
    2. [Relation Extraction](mds/relation-extraction.md) <br/>
2. Understanding the question
3. Generating an answer

## Events
- Wolfram Alpha launced the answer engine in 2009.
- IBM Watson system defeated top *[Jeopardy!](https://www.jeopardy.com)* champions in 2011.
- Apple's Siri integrated Wolfram Alpha's answer engine in 2011.
- Google embraced QA by launching its Knowledge Graph, leveraging the free base knowledge base in 2012.
- Amazon Echo | Alexa (2015), Google Home | Google Assistant (2016), INVOKE | MS Cortana (2017), HomePod (2017)

## Systems
- [IBM Watson](https://www.ibm.com/watson/) - Has state-of-the-arts performance. 
- [Facebook DrQA](https://research.fb.com/downloads/drqa/) - Applied to the SQuAD1.0 dataset. The SQuAD2.0 dataset has released. but DrQA is not tested yet.
- [MIT media lab's Knowledge graph](http://conceptnet.io/) - Is a freely-available semantic network, designed to help computers understand the meanings of words that people use.

## Codes
- [BiDAF](https://github.com/allenai/bi-att-flow)
  - official; tensorflow v1.2
  - [paper](https://arxiv.org/pdf/1611.01603.pdf)
- [QANet](https://github.com/NLPLearn/QANet)
  - Google; unofficial; tensorflow v1.5
  - [paper](#qanet)
- [R-Net](https://github.com/HKUST-KnowComp/R-Net)
  - MS; unofficially by HKUST; tensorflow v1.5
  - [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [R-Net-in-Keras](https://github.com/YerevaNN/R-NET-in-Keras)
  - MS; unofficial; keras v2.0.6
  - [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [DrQA](https://github.com/hitvoice/DrQA)
  - Facebook; official; pytorch v0.4
  - [paper](#drqa)
- [Bert](https://github.com/google-research/bert)
  - Google; official implementation; tensorflow v1.11.0
  - [paper](https://arxiv.org/abs/1810.04805)

## Lectures
- [Question Answering - Natural Language Processing](https://youtu.be/Kzi6tE4JaGo) - By Dragomir Radev, Ph.D. | University of Michigan | 2016.

## Slides
- [Question Answering with Knowledge Bases, Web and Beyond](https://github.com/scottyih/Slides/blob/master/QA%20Tutorial.pdf) - By Scott Wen-tau Yih & Hao Ma | Microsoft Research | 2016.
- [Question Answering](https://hpi.de/fileadmin/user_upload/fachgebiete/plattner/teaching/NaturalLanguageProcessing/NLP2017/NLP8_QuestionAnswering.pdf) - By Dr. Mariana Neves | Hasso Plattner Institut | 2017.

## Dataset Collections
- [NLIWOD's Question answering datasets](https://github.com/dice-group/NLIWOD/tree/master/qa.datasets)
- [karthinkncode's Datasets for Natural Language Processing](https://github.com/karthikncode/nlp-datasets)
- [sebastianruder's NLP-progess/Question answering](https://github.com/sebastianruder/NLP-progress/blob/master/question_answering.md)

## Datasets
- [AI2 Science Questions v2.1(2017)](http://data.allenai.org/ai2-science-questions/)
  - It consists of questions used in student assessments in the United States across elementary and middle school grade levels. Each question is 4-way multiple choice format and may or may not include a diagram element.
  - paper : http://ai2-website.s3.amazonaws.com/publications/AI2ReasoningChallenge2018.pdf
- [Children's Book Test](https://uclmr.github.io/ai4exams/data.html)
- It is one of the bAbI project of Facebook AI Research which is organized towards the goal of automatic text understanding and reasoning. The CBT is designed to measure directly how well language models can exploit wider linguistic context.
- [DeepMind Q&A Dataset; CNN/Daily Mail](https://github.com/deepmind/rc-data)
  - Hermann et al. (2015) created two awesome datasets using news articles for Q&A research. Each dataset contains many documents (90k and 197k each), and each document companies on average 4 questions approximately. Each question is a sentence with one missing word/phrase which can be found from the accompanying document/context.
  - paper: https://arxiv.org/abs/1506.03340
- [GraphQuestions](https://github.com/ysu1989/GraphQuestions)
  - On generating Characteristic-rich Question sets for QA evaluation.
- [LC-QuAD](http://sda.cs.uni-bonn.de/projects/qa-dataset/)
  - It is a gold standard KBQA (Question Answering over Knowledge Base) dataset containing 5000 Question and SPARQL queries. LC-QuAD uses DBpedia v04.16 as the target KB.
- [MS MARCO](http://www.msmarco.org/dataset.aspx)
  - This is for real-world question answering.
  - paper : https://arxiv.org/abs/1611.09268
- [MultiRC](https://cogcomp.org/multirc/)
  - A dataset of short paragraphs and multi-sentence questions
  - Paper: http://cogcomp.org/page/publication_view/833 
- [NarrativeQA](https://github.com/deepmind/narrativeqa)
  - It includes the list of documents with Wikipedia summaries, links to full stories, and questions and answers.
  - paper: https://arxiv.org/pdf/1712.07040v1.pdf
- [NewsQA](https://github.com/Maluuba/newsqa)
  - A machine comprehension dataset
  - paper: https://arxiv.org/pdf/1611.09830.pdf
- [Qestion-Answer Dataset by CMU](http://www.cs.cmu.edu/~ark/QA-data/)
  - This is a corpus of Wikipedia articles, manually-generated factoid questions from them, and manually-generated answers to these questions, for use in academic research. These data were collected by Noah Smith, Michael Heilman, Rebecca Hwa, Shay Cohen, Kevin Gimpel, and many students at Carnegie Mellon University and the University of Pittsburgh between 2008 and 2010.
- [SQuAD1.0](https://rajpurkar.github.io/SQuAD-explorer/)
  - Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.
  - paper: https://arxiv.org/abs/1606.05250
- [SQuAD2.0](https://rajpurkar.github.io/SQuAD-explorer/)
  - SQuAD2.0 combines the 100,000 questions in SQuAD1.1 with over 50,000 new, unanswerable questions written adversarially by crowdworkers to look similar to answerable ones. To do well on SQuAD2.0, systems must not only answer questions when possible, but also determine when no answer is supported by the paragraph and abstain from answering.
  - paper: https://arxiv.org/abs/1806.03822
- [Story cloze test](http://cs.rochester.edu/nlp/rocstories/)
  - 'Story Cloze Test' is a new commonsense reasoning framework for evaluating story understanding, story generation, and script learning. This test requires a system to choose the correct ending to a four-sentence story.
  - paper: https://arxiv.org/abs/1604.01696
- [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)
  - TriviaQA is a reading comprehension dataset containing over 650K question-answer-evidence triples. TriviaQA includes 95K question-answer pairs authored by trivia enthusiasts and independently gathered evidence documents, six per question on average, that provide high quality distant supervision for answering the questions. 
  - paper: https://arxiv.org/abs/1705.03551
- [WikiQA](https://www.microsoft.com/en-us/download/details.aspx?id=52419&from=https%3A%2F%2Fresearch.microsoft.com%2Fen-US%2Fdownloads%2F4495da01-db8c-4041-a7f6-7984a4f6a905%2Fdefault.aspx)
  - A publicly available set of question and sentence pairs for open-domain question answering.



## Running Competitions in QA

|   | Dataset     |                     | Since | Top Rank               | Model                  | over Human Performance |
|---|-------------|---------------------|-------|------------------------|------------------------|------------------------|
| 0 | MS MARCO V2 | Microsoft           | 2016~ | Baidu NLP              | VNET                   | partialy               |
| 1 | TriviaQA    | Univ. of Washington | 2017~ | mingyan                | ?                      | ?                      |
| 2 | SQuAD 2.0   | Univ. of Stanford   | 2018~ | PINGAN GammaLab        | PAML+BERT (ensemble)   | x                      |
| 3 | decaNLP     | Salesforce Research | 2018~ | Salesforce Research    | MQAN                   | x                      |

## Concluded Competitions in QA

|      | Dataset                                                     |           | Top Rank      | Model                                                                                                                                                          | over Human Performance  |
|------|-------------------------------------------------------------|-----------|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| 2016 | [Story Cloze Test](http://cs.rochester.edu/nlp/rocstories/) | LSDSem'17 | Radford et al | [Finetuned Transformer LM](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)            |                         |

## Publications
- Papers
  - ["Learning to Skim Text"](https://arxiv.org/pdf/1704.06877.pdf), Adams Wei Yu, Hongrae Lee, Quoc V. Le, 2017.
    : Show only what you want in Text
  - ["Deep Joint Entity Disambiguation with Local Neural Attention"](https://arxiv.org/pdf/1704.04920.pdf), Octavian-Eugen Ganea and Thomas Hofmann, 2017.
  - ["BI-DIRECTIONAL ATTENTION FLOW FOR MACHINE COMPREHENSION"](https://arxiv.org/pdf/1611.01603.pdf), Minjoon Seo, Aniruddha Kembhavi, Ali Farhadi, Hananneh Hajishirzi, ICLR, 2017.
  - ["Capturing Semantic Similarity for Entity Linking with Convolutional Neural Networks"](http://nlp.cs.berkeley.edu/pubs/FrancisLandau-Durrett-Klein_2016_EntityConvnets_paper.pdf), Matthew Francis-Landau, Greg Durrett and Dan Klei, NAACL-HLT 2016.
    - https://GitHub.com/matthewfl/nlp-entity-convnet
  - ["Entity Linking with a Knowledge Base: Issues, Techniques, and Solutions"](https://ieeexplore.ieee.org/document/6823700/), Wei Shen, Jianyong Wang, Jiawei Han, IEEE Transactions on Knowledge and Data Engineering(TKDE), 2014.
  - ["Introduction to “This is Watson"](https://ieeexplore.ieee.org/document/6177724/), IBM Journal of Research and Development, D. A. Ferrucci, 2012.
  - ["A survey on question answering technology from an information retrieval perspective"](https://www.sciencedirect.com/science/article/pii/S0020025511003860), Information Sciences, 2011.
  - ["Question Answering in Restricted Domains: An Overview"](https://www.mitpressjournals.org/doi/abs/10.1162/coli.2007.33.1.41), Diego Mollá and José Luis Vicedo, Computational Linguistics, 2007
  - ["Natural language question answering: the view from here"](), L Hirschman, R Gaizauskas, natural language engineering, 2001.
  - Entity Disambiguation / Entity Linking
    
### The DeepQA Research Team in IBM Watson's publication within 5 years
- 2015
  - "Automated Problem List Generation from Electronic Medical Records in IBM Watson", Murthy Devarakonda, Ching-Huei Tsou, IAAI, 2015.
  - ["Decision Making in IBM Watson Question Answering"](https://pdfs.semanticscholar.org/presentation/6285/0c8902f8e2a079b2fe356a73a21cea55c9d2.pdf), J. William Murdock, Ontology summit, 2015.
  - ["Unsupervised Entity-Relation Analysis in IBM Watson"](http://www.cogsys.org/papers/ACS2015/article12.pdf), Aditya Kalyanpur, J William Murdock, ACS, 2015.
  - "Commonsense Reasoning: An Event Calculus Based Approach", E T Mueller, Morgan Kaufmann/Elsevier, 2015.
- 2014
  - "Problem-oriented patient record summary: An early report on a Watson application", M. Devarakonda, Dongyang Zhang, Ching-Huei Tsou, M. Bornea, Healthcom, 2014.
  - ["WatsonPaths: Scenario-based Question Answering and Inference over Unstructured Information"](http://domino.watson.ibm.com/library/Cyberdig.nsf/1e4115aea78b6e7c85256b360066f0d4/088f74984a07645485257d5f006ace96!OpenDocument&Highlight=0,RC25489), Adam Lally, Sugato Bachi, Michael A. Barborak, David W. Buchanan, Jennifer Chu-Carroll, David A. Ferrucci*, Michael R. Glass, Aditya Kalyanpur, Erik T. Mueller, J. William Murdock, Siddharth Patwardhan, John M. Prager, Christopher A. Welty, IBM Research Report RC25489, 2014.
  - ["Medical Relation Extraction with Manifold Models"](http://acl2014.org/acl2014/P14-1/pdf/P14-1078.pdf), Chang Wang and James Fan, ACL, 2014.

### MS Research's publication within 5 years
- 2018
  - "Characterizing and Supporting Question Answering in Human-to-Human Communication", Xiao Yang, Ahmed Hassan Awadallah, Madian Khabsa, Wei Wang, Miaosen Wang, ACM SIGIR, 2018.
  - ["FigureQA: An Annotated Figure Dataset for Visual Reasoning"](https://arxiv.org/abs/1710.07300), Samira Ebrahimi Kahou, Vincent Michalski, Adam Atkinson, Akos Kadar, Adam Trischler, Yoshua Bengio, ICLR, 2018
- 2017
  - "Multi-level Attention Networks for Visual Question Answering", Dongfei Yu, Jianlong Fu, Tao Mei, Yong Rui, CVPR, 2017.
  - "A Joint Model for Question Answering and Question Generation", Tong Wang, Xingdi (Eric) Yuan, Adam Trischler, ICML, 2017.
  - "Two-Stage Synthesis Networks for Transfer Learning in Machine Comprehension", David Golub, Po-Sen Huang, Xiaodong He, Li Deng, EMNLP, 2017.
  - "Question-Answering with Grammatically-Interpretable Representations", Hamid Palangi, Paul Smolensky, Xiaodong He, Li Deng, 
  - "Search-based Neural Structured Learning for Sequential Question Answering", Mohit Iyyer, Wen-tau Yih, Ming-Wei Chang, ACL, 2017.
- 2016
  - ["Stacked Attention Networks for Image Question Answering"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Yang_Stacked_Attention_Networks_CVPR_2016_paper.html), Zichao Yang, Xiaodong He, Jianfeng Gao, Li Deng, Alex Smola, CVPR, 2016.
  - ["Question Answering with Knowledge Base, Web and Beyond"](https://www.microsoft.com/en-us/research/publication/question-answering-with-knowledge-base-web-and-beyond/), Yih, Scott Wen-tau and Ma, Hao, ACM SIGIR, 2016.
  - ["NewsQA: A Machine Comprehension Dataset"](https://arxiv.org/abs/1611.09830), Adam Trischler, Tong Wang, Xingdi Yuan, Justin Harris, Alessandro Sordoni, Philip Bachman, Kaheer Suleman, RepL4NLP, 2016.
  - ["Table Cell Search for Question Answering"](https://dl.acm.org/citation.cfm?id=2883080), Sun, Huan and Ma, Hao and He, Xiaodong and Yih, Wen-tau and Su, Yu and Yan, Xifeng, WWW, 2016.
- 2015
  - ["WIKIQA: A Challenge Dataset for Open-Domain Question Answering"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/YangYihMeek_EMNLP-15_WikiQA.pdf), Yi Yang, Wen-tau Yih, and Christopher Meek, EMNLP, 2015.
  - ["Web-based Question Answering: Revisiting AskMSR"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/AskMSRPlusTR_082815.pdf), Chen-Tse Tsai, Wen-tau Yih, and Christopher J.C. Burges, MSR-TR, 2015.
  - ["Open Domain Question Answering via Semantic Enrichment"](https://dl.acm.org/citation.cfm?id=2741651), Huan Sun, Hao Ma, Wen-tau Yih, Chen-Tse Tsai, Jingjing Liu, and Ming-Wei Chang, WWW, 2015.
- 2014
  - ["An Overview of Microsoft Deep QA System on Stanford WebQuestions Benchmark"](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Microsoft20Deep20QA.pdf), Zhenghao Wang, Shengquan Yan, Huaming Wang, and Xuedong Huang, MSR-TR, 2014.
  - ["Semantic Parsing for Single-Relation Question Answering"](), Wen-tau Yih, Xiaodong He, Christopher Meek, ACL, 2014.
  
### Google AI's publication within 5 years
- 2018
  - Google QA <a name="qanet"></a>
    - ["QANet: Combining Local Convolution with Global Self-Attention for Reading Comprehension"](https://openreview.net/pdf?id=B14TlG-RW), Adams Wei Yu, David Dohan, Minh-Thang Luong, Rui Zhao, Kai Chen, Mohammad Norouzi, Quoc V. Le, ICLR, 2018.
    - ["Ask the Right Questions: Active Question Reformulation with Reinforcement Learning"](https://openreview.net/pdf?id=S1CChZ-CZ), Christian Buck and Jannis Bulian and Massimiliano Ciaramita and Wojciech Paweł Gajewski and Andrea Gesmundo and Neil Houlsby and Wei Wang, ICLR, 2018.
    - ["Building Large Machine Reading-Comprehension Datasets using Paragraph Vectors"](https://arxiv.org/pdf/1612.04342.pdf), Radu Soricut, Nan Ding, 2018.
  - Sentence representation
    - ["An efficient framework for learning sentence representations"](https://arxiv.org/pdf/1803.02893.pdf), Lajanugen Logeswaran, Honglak Lee, ICLR, 2018.
  - ["Did the model understand the question?"](https://arxiv.org/pdf/1805.05492.pdf), Pramod K. Mudrakarta and Ankur Taly and Mukund Sundararajan and Kedar Dhamdhere, ACL, 2018.
- 2017
  - ["Analyzing Language Learned by an Active Question Answering Agent"](https://arxiv.org/pdf/1801.07537.pdf), Christian Buck and Jannis Bulian and Massimiliano Ciaramita and Wojciech Gajewski and Andrea Gesmundo and Neil Houlsby and Wei Wang, NIPS, 2017.
  - ["Learning Recurrent Span Representations for Extractive Question Answering"](https://arxiv.org/pdf/1611.01436.pdf), Kenton Lee and Shimi Salant and Tom Kwiatkowski and Ankur Parikh and Dipanjan Das and Jonathan Berant, ICLR, 2017.
  - Identify the same question
    - ["Neural Paraphrase Identification of Questions with Noisy Pretraining"](https://arxiv.org/pdf/1704.04565.pdf), Gaurav Singh Tomar and Thyago Duque and Oscar Täckström and Jakob Uszkoreit and Dipanjan Das, SCLeM, 2017.
- 2014
  - "Great Question! Question Quality in Community Q&A", Sujith Ravi and Bo Pang and Vibhor Rastogi and Ravi Kumar, ICWSM, 2014.

### Facebook AI Research's publication within 5 years
- 2018
  - [Embodied Question Answering](https://research.fb.com/publications/embodied-question-answering/), Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, and Dhruv Batra, CVPR, 2018
  - [Do explanations make VQA models more predictable to a human?](https://research.fb.com/publications/do-explanations-make-vqa-models-more-predictable-to-a-human/), Arjun Chandrasekaran, Viraj Prabhu, Deshraj Yadav, Prithvijit Chattopadhyay, and Devi Parikh, EMNLP, 2018
  - [Neural Compositional Denotational Semantics for Question Answering](https://research.fb.com/publications/neural-compositional-denotational-semantics-for-question-answering/), Nitish Gupta, Mike Lewis, EMNLP, 2018
- 2017
  - DrQA <a name="drqa"></a>
    - [Reading Wikipedia to Answer Open-Domain Questions](https://cs.stanford.edu/people/danqi/papers/acl2017.pdf), Danqi Chen, Adam Fisch, Jason Weston & Antoine Bordes, ACL, 2017.

## Books
- Natural Language Question Answering system Paperback - Boris Galitsky (2003)
- New Directions in Question Answering - Mark T. Maybury (2004)
- Part 3. 5. Question Answering in The Oxford Handbook of Computational Linguistics - Sanda Harabagiu and Dan Moldovan (2005)
- Chap.28 Question Answering in Speech and Language Processing - Daniel Jurafsky & James H. Martin (2017)

## Links
- [Building a Question-Answering System from Scratch— Part 1](https://towardsdatascience.com/building-a-question-answering-system-part-1-9388aadff507)
- [Qeustion Answering with Tensorflow By Steven Hewitt, O'REILLY, 2017](https://www.oreilly.com/ideas/question-answering-with-tensorflow)
- [Why question answering is hard](http://nicklothian.com/blog/2014/09/25/why-question-answering-is-hard/)


## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/share-your-work/public-domain/cc0/)

To the extent possible under law, [seriousmac](https://github.com/seriousmac) (the maintainer) has waived all copyright and related or neighboring rights to this work.
