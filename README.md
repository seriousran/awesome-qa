# Awesome Question Answering [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) 

_A curated list of the __[Question Answering (QA)](https://en.wikipedia.org/wiki/Question_answering)__ subject which is a computer science discipline within the fields of information retrieval and natural language processing (NLP) toward using machine learning and deep learning_

_정보 검색 및 자연 언어 처리 분야의 질의응답에 관한 큐레이션 - 머신러닝과 딥러닝 단계까지_<br/>
_问答系统主题的精选列表，是信息检索和自然语言处理领域的计算机科学学科 - 使用机器学习和深度学习_

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Recent Trend](#recent-trend)
- [About QA](#about-qa)
- [Events](#events)
- [Systems](#systems)
- [Competitions in QA](#competitions-in-qa)
- [Publications](#publications)
- [Codes](#codes)
- [Lectures](#lectures)
- [Slides](#slides)
- [Dataset Collections](#dataset-collections)
- [Datasets](#datasets)
- [Books](#books)
- [Links](#links)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Recent Trend
### Recent QA Models
- UnifiedQA: Crossing Format Boundaries With a Single QA System (2020)
  - Demo: https://unifiedqa.apps.allenai.org/
- ProQA: Resource-efficient method for pretraining a dense corpus index for open-domain QA and IR. (2020)
  - paper: https://arxiv.org/pdf/2005.00038.pdf
  - github: https://github.com/xwhan/ProQA
- TYDI QA: A Benchmark for Information-Seeking Question Answering in Typologically Diverse Languages (2020)
  - paper: https://arxiv.org/ftp/arxiv/papers/2003/2003.05002.pdf
- Retrospective Reader for Machine Reading Comprehension
  - paper: https://arxiv.org/pdf/2001.09694v2.pdf
- TANDA: Transfer and Adapt Pre-Trained Transformer Models for Answer Sentence Selection (AAAI 2020)
  - paper: https://arxiv.org/pdf/1911.04118.pdf
### Recent Language Models
- [ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators](https://openreview.net/pdf?id=r1xMH1BtvB), Kevin Clark, et al., ICLR, 2020.
- [TinyBERT: Distilling BERT for Natural Language Understanding](https://openreview.net/pdf?id=rJx0Q6EFPB), Xiaoqi Jiao, et al., ICLR, 2020.
- [MINILM: Deep Self-Attention Distillation for Task-Agnostic Compression of Pre-Trained Transformers](https://arxiv.org/abs/2002.10957), Wenhui Wang, et al., arXiv, 2020.
- [T5: Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683), Colin Raffel, et al., arXiv preprint, 2019.
- [ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/abs/1905.07129), Zhengyan Zhang, et al., ACL, 2019.
- [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237), Zhilin Yang, et al., arXiv preprint, 2019.
- [ALBERT: A Lite BERT for Self-supervised Learning of Language Representations](https://arxiv.org/abs/1909.11942), Zhenzhong Lan, et al., arXiv preprint, 2019.
- [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692), Yinhan Liu, et al., arXiv preprint, 2019.
- [DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter](https://arxiv.org/pdf/1910.01108.pdf), Victor sanh, et al., arXiv, 2019.
- [SpanBERT: Improving Pre-training by Representing and Predicting Spans](https://arxiv.org/pdf/1907.10529v3.pdf), Mandar Joshi, et al., TACL, 2019.
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805), Jacob Devlin, et al., NAACL 2019, 2018.
### AAAI 2020
  - [TANDA: Transfer and Adapt Pre-Trained Transformer Models for Answer Sentence Selection](https://arxiv.org/pdf/1911.04118.pdf), Siddhant Garg, et al., AAAI 2020, Nov 2019.
### ACL 2019
  - [Overview of the MEDIQA 2019 Shared Task on Textual Inference,
Question Entailment and Question Answering](https://www.aclweb.org/anthology/W19-5039), Asma Ben Abacha, et al., ACL-W 2019, Aug 2019.
  - [Towards Scalable and Reliable Capsule Networks for Challenging NLP Applications](https://arxiv.org/pdf/1906.02829v1.pdf), Wei Zhao, et al., ACL 2019, Jun 2019.
  - [Cognitive Graph for Multi-Hop Reading Comprehension at Scale](https://arxiv.org/pdf/1905.05460v2.pdf), Ming Ding, et al., ACL 2019, Jun 2019.
  - [Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/abs/1906.05807), Minjoon Seo, et al., ACL 2019, Jun 2019.
  - [Unsupervised Question Answering by Cloze Translation](https://arxiv.org/abs/1906.04980), Patrick Lewis, et al., ACL 2019, Jun 2019.
  - [SemEval-2019 Task 10: Math Question Answering](https://www.aclweb.org/anthology/S19-2153), Mark Hopkins, et al., ACL-W 2019, Jun 2019.
  - [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://arxiv.org/abs/1905.07098), Wenhan Xiong, et al., ACL 2019, May 2019.
  - [Matching Article Pairs with Graphical Decomposition and Convolutions](https://arxiv.org/pdf/1802.07459v2.pdf), Bang Liu, et al., ACL 2019, May 2019.
  - [Episodic Memory Reader: Learning what to Remember for Question Answering from Streaming Data](https://arxiv.org/abs/1903.06164), Moonsu Han, et al., ACL 2019, Mar 2019.
  - [Natural Questions: a Benchmark for Question Answering Research](https://ai.google/research/pubs/pub47761), Tom Kwiatkowski, et al., TACL 2019, Jan 2019.
  - [Textbook Question Answering with Multi-modal Context Graph Understanding and Self-supervised Open-set Comprehension](https://arxiv.org/abs/1811.00232), Daesik Kim, et al., ACL 2019, Nov 2018.
### EMNLP-IJCNLP 2019
  - [Language Models as Knowledge Bases?](https://arxiv.org/pdf/1909.01066v2.pdf), Fabio Petron, et al., EMNLP-IJCNLP 2019, Sep 2019.
  - [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://arxiv.org/pdf/1908.07490v3.pdf), Hao Tan, et al., EMNLP-IJCNLP 2019, Dec 2019.
  - [Answering Complex Open-domain Questions Through Iterative Query Generation](https://arxiv.org/pdf/1910.07000v1.pdf), Peng Qi, et al., EMNLP-IJCNLP 2019, Oct 2019.
  - [KagNet: Knowledge-Aware Graph Networks for Commonsense Reasoning](https://arxiv.org/pdf/1909.02151v1.pdf), Bill Yuchen Lin, et al., EMNLP-IJCNLP 2019, Sep 2019.
  - [Mixture Content Selection for Diverse Sequence Generation](https://arxiv.org/pdf/1909.01953v1.pdf), Jaemin Cho, et al., EMNLP-IJCNLP 2019, Sep 2019.
  - [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849v1.pdf), Sewon Min, et al., EMNLP-IJCNLP, 2019, Sep 2019.
### Arxiv
  - [Investigating the Successes and Failures of BERT for Passage Re-Ranking](https://arxiv.org/abs/1905.01758), Harshith Padigela, et al., arXiv preprint, May 2019.
  - [BERT with History Answer Embedding for Conversational Question Answering](https://arxiv.org/abs/1905.05412), Chen Qu, et al., arXiv preprint, May 2019.
  - [Understanding the Behaviors of BERT in Ranking](https://arxiv.org/abs/1904.07531), Yifan Qiao, et al., arXiv preprint, Apr 2019.
  - [BERT Post-Training for Review Reading Comprehension and Aspect-based Sentiment Analysis](https://arxiv.org/abs/1904.02232), Hu Xu, et al., arXiv preprint, Apr 2019.
  - [End-to-End Open-Domain Question Answering with BERTserini](https://arxiv.org/abs/1902.01718), Wei Yang, et al., arXiv preprint, Feb 2019.
  - [A BERT Baseline for the Natural Questions](https://arxiv.org/abs/1901.08634), Chris Alberti, et al., arXiv preprint, Jan 2019.
  - [Passage Re-ranking with BERT](https://arxiv.org/abs/1901.04085), Rodrigo Nogueira, et al., arXiv preprint, Jan 2019.
  - [SDNet: Contextualized Attention-based Deep Network for Conversational Question Answering](https://arxiv.org/abs/1812.03593), Chenguang Zhu, et al., arXiv, Dec 2018.
### Dataset
  - [ELI5: Long Form Question Answering](https://arxiv.org/abs/1907.09190), Angela Fan, et al., ACL 2019, Jul 2019
  - [CODAH: An Adversarially-Authored Question Answering Dataset for
Common Sense](https://www.aclweb.org/anthology/W19-2008.pdf), Michael Chen, et al., RepEval 2019, Jun 2019.
  
## About QA
### Types of QA
- Single-turn QA: answer without considering any context
- Conversational QA: use previsous conversation turns
#### Subtypes of QA
- Knowledge-based QA
- Table/List-based QA
- Text-based QA
- Community-based QA
- Visual QA

### Analysis and Parsing for Pre-processing in QA systems
Lanugage Analysis
  1. [Morphological analysis](https://www.cs.bham.ac.uk/~pjh/sem1a5/pt2/pt2_intro_morphology.html)
  2. [Named Entity Recognition(NER)](mds/named-entity-recognition.md)
  3. Homonyms / Polysemy Analysis
  4. Syntactic Parsing (Dependency Parsing)
  5. Semantic Recognition

### Most QA systems have roughly 3 parts
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

## Competitions in QA

|   | Dataset          | Language      | Organizer           | Since | Top Rank               | Model                   | Status | Over Human Performance |
|---|------------------|---------------|---------------------|-------|-------------------------|-------------------------|--------|------------------------|
| 0 | [Story Cloze Test](http://cs.rochester.edu/~nasrinm/files/Papers/lsdsem17-shared-task.pdf) | English       | Univ. of Rochester    | 2016 | msap                   | Logistic regression | Closed | x                      |
| 1 | MS MARCO         | English       | Microsoft           | 2016  | YUANFUDAO research NLP  | MARS                    | Closed | o                      |
| 2 | MS MARCO V2      | English       | Microsoft           | 2018  | NTT Media Intelli. Lab. | Masque Q&A Style        | Opened | x                      |
| 3 | [SQuAD](https://arxiv.org/abs/1606.05250)            | English       | Univ. of Stanford   | 2018  | XLNet (single model)  |XLNet Team | Closed | o                      |
| 4 | [SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/)        | English       | Univ. of Stanford   | 2018  | PINGAN Omni-Sinitic | ALBERT + DAAF + Verifier (ensemble) | Opened | o                      |
| 5 | [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)         | English       | Univ. of Washington | 2017  | Ming Yan                | -                       | Closed | -                      |
| 6 | [decaNLP](https://decanlp.com/)          | English       | Salesforce Research | 2018  | Salesforce Research     | MQAN                    | Closed | x                      |
| 7 | [DuReader Ver1.](https://ai.baidu.com/broad/introduction)          | Chinese       | Baidu               | 2015  | Tryer                    | T-Reader (single)       | Closed | x                      |
| 8 | [DuReader Ver2.](https://ai.baidu.com/broad/introduction)          | Chinese       | Baidu               | 2017  | renaissance             | AliReader               | Opened | -                      |
| 9 | [KorQuAD](https://korquad.github.io/KorQuad%201.0/)    | Korean     | LG CNS AI Research | 2018  | Clova AI LaRva Team      | LaRva-Kor-Large+ + CLaF (single)  | Closed | o                      |
| 10 | [KorQuAD 2.0](https://korquad.github.io/)    | Korean     | LG CNS AI Research | 2019  | Kangwon National University | KNU-baseline(single model) | Opened | x                      |
| 11 | [CoQA](https://stanfordnlp.github.io/coqa/)    | English     | Univ. of Stanford | 2018  | Zhuiyi Technology | RoBERTa + AT + KD (ensemble) | Opened | o                      |

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

## Codes
- [BiDAF](https://github.com/allenai/bi-att-flow) - Bi-Directional Attention Flow (BIDAF) network is a multi-stage hierarchical process that represents the context at different levels of granularity and uses bi-directional attention flow mechanism to obtain a query-aware context representation without early summarization. 
  - Official; Tensorflow v1.2
  - [Paper](https://arxiv.org/pdf/1611.01603.pdf)
- [QANet](https://github.com/NLPLearn/QANet) - A Q&A architecture does not require recurrent networks: Its encoder consists exclusively of convolution and self-attention, where convolution models local interactions and self-attention models global interactions.
  - Google; Unofficial; Tensorflow v1.5
  - [Paper](#qanet)
- [R-Net](https://github.com/HKUST-KnowComp/R-Net) - An end-to-end neural networks model for reading comprehension style question answering, which aims to answer questions from a given passage.
  - MS; Unofficially by HKUST; Tensorflow v1.5
  - [Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [R-Net-in-Keras](https://github.com/YerevaNN/R-NET-in-Keras) - R-NET re-implementation in Keras.
  - MS; Unofficial; Keras v2.0.6
  - [Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)
- [DrQA](https://github.com/hitvoice/DrQA) - DrQA is a system for reading comprehension applied to open-domain question answering.
  - Facebook; Official; Pytorch v0.4
  - [Paper](#drqa)
- [BERT](https://github.com/google-research/bert) - A new language representation model which stands for Bidirectional Encoder Representations from Transformers. Unlike recent language representation models, BERT is designed to pre-train deep bidirectional representations by jointly conditioning on both left and right context in all layers. 
  - Google; Official implementation; Tensorflow v1.11.0
  - [Paper](https://arxiv.org/abs/1810.04805)

## Lectures
- [Question Answering - Natural Language Processing](https://youtu.be/Kzi6tE4JaGo) - By Dragomir Radev, Ph.D. | University of Michigan | 2016.

## Slides
- [Question Answering with Knowledge Bases, Web and Beyond](https://github.com/scottyih/Slides/blob/master/QA%20Tutorial.pdf) - By Scott Wen-tau Yih & Hao Ma | Microsoft Research | 2016.
- [Question Answering](https://hpi.de/fileadmin/user_upload/fachgebiete/plattner/teaching/NaturalLanguageProcessing/NLP2017/NLP8_QuestionAnswering.pdf) - By Dr. Mariana Neves | Hasso Plattner Institut | 2017.

## Dataset Collections
- [NLIWOD's Question answering datasets](https://github.com/dice-group/NLIWOD/tree/master/qa.datasets)
- [karthinkncode's Datasets for Natural Language Processing](https://github.com/karthikncode/nlp-datasets)

## Datasets
- [AI2 Science Questions v2.1(2017)](http://data.allenai.org/ai2-science-questions/)
  - It consists of questions used in student assessments in the United States across elementary and middle school grade levels. Each question is 4-way multiple choice format and may or may not include a diagram element.
  - Paper: http://ai2-website.s3.amazonaws.com/publications/AI2ReasoningChallenge2018.pdf
- [Children's Book Test](https://uclmr.github.io/ai4exams/data.html)
- It is one of the bAbI project of Facebook AI Research which is organized towards the goal of automatic text understanding and reasoning. The CBT is designed to measure directly how well language models can exploit wider linguistic context.
- [CODAH Dataset](https://github.com/Websail-NU/CODAH)
- [DeepMind Q&A Dataset; CNN/Daily Mail](https://github.com/deepmind/rc-data)
  - Hermann et al. (2015) created two awesome datasets using news articles for Q&A research. Each dataset contains many documents (90k and 197k each), and each document companies on average 4 questions approximately. Each question is a sentence with one missing word/phrase which can be found from the accompanying document/context.
  - Paper: https://arxiv.org/abs/1506.03340
- [ELI5](https://github.com/facebookresearch/ELI5)
  - Paper: https://arxiv.org/abs/1907.09190
- [GraphQuestions](https://github.com/ysu1989/GraphQuestions)
  - On generating Characteristic-rich Question sets for QA evaluation.
- [LC-QuAD](http://sda.cs.uni-bonn.de/projects/qa-dataset/)
  - It is a gold standard KBQA (Question Answering over Knowledge Base) dataset containing 5000 Question and SPARQL queries. LC-QuAD uses DBpedia v04.16 as the target KB.
- [MS MARCO](http://www.msmarco.org/dataset.aspx)
  - This is for real-world question answering.
  - Paper: https://arxiv.org/abs/1611.09268
- [MultiRC](https://cogcomp.org/multirc/)
  - A dataset of short paragraphs and multi-sentence questions
  - Paper: http://cogcomp.org/page/publication_view/833 
- [NarrativeQA](https://github.com/deepmind/narrativeqa)
  - It includes the list of documents with Wikipedia summaries, links to full stories, and questions and answers.
  - Paper: https://arxiv.org/pdf/1712.07040v1.pdf
- [NewsQA](https://github.com/Maluuba/newsqa)
  - A machine comprehension dataset
  - Paper: https://arxiv.org/pdf/1611.09830.pdf
- [Qestion-Answer Dataset by CMU](http://www.cs.cmu.edu/~ark/QA-data/)
  - This is a corpus of Wikipedia articles, manually-generated factoid questions from them, and manually-generated answers to these questions, for use in academic research. These data were collected by Noah Smith, Michael Heilman, Rebecca Hwa, Shay Cohen, Kevin Gimpel, and many students at Carnegie Mellon University and the University of Pittsburgh between 2008 and 2010.
- [SQuAD1.0](https://rajpurkar.github.io/SQuAD-explorer/)
  - Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.
  - Paper: https://arxiv.org/abs/1606.05250
- [SQuAD2.0](https://rajpurkar.github.io/SQuAD-explorer/)
  - SQuAD2.0 combines the 100,000 questions in SQuAD1.1 with over 50,000 new, unanswerable questions written adversarially by crowdworkers to look similar to answerable ones. To do well on SQuAD2.0, systems must not only answer questions when possible, but also determine when no answer is supported by the paragraph and abstain from answering.
  - Paper: https://arxiv.org/abs/1806.03822
- [Story cloze test](http://cs.rochester.edu/nlp/rocstories/)
  - 'Story Cloze Test' is a new commonsense reasoning framework for evaluating story understanding, story generation, and script learning. This test requires a system to choose the correct ending to a four-sentence story.
  - Paper: https://arxiv.org/abs/1604.01696
- [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)
  - TriviaQA is a reading comprehension dataset containing over 650K question-answer-evidence triples. TriviaQA includes 95K question-answer pairs authored by trivia enthusiasts and independently gathered evidence documents, six per question on average, that provide high quality distant supervision for answering the questions. 
  - Paper: https://arxiv.org/abs/1705.03551
- [WikiQA](https://www.microsoft.com/en-us/download/details.aspx?id=52419&from=https%3A%2F%2Fresearch.microsoft.com%2Fen-US%2Fdownloads%2F4495da01-db8c-4041-a7f6-7984a4f6a905%2Fdefault.aspx)
  - A publicly available set of question and sentence pairs for open-domain question answering.
  
### The DeepQA Research Team in IBM Watson's publication within 5 years
- 2015
  - "Automated Problem List Generation from Electronic Medical Records in IBM Watson", Murthy Devarakonda, Ching-Huei Tsou, IAAI, 2015.
  - "Decision Making in IBM Watson Question Answering", J. William Murdock, Ontology summit, 2015.
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
