# named-entity-recognition

Named-entity recognition (NER) (also known as entity identification, entity chunking and entity extraction) is a subtask of information extraction that seeks to locate and classify named entities in text into pre-defined categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, etc.

Most research on NER systems has been structured as taking an unannotated block of text, such as this one:

Jim bought 300 shares of Acme Corp. in 2006.

And producing an annotated block of text that highlights the names of entities:

[Jim]Person bought 300 shares of [Acme Corp.]Organization in [2006]Time.

In this example, a person name consisting of one token, a two-token company name and a temporal expression have been detected and classified.

State-of-the-art NER systems for English produce near-human performance. For example, the best system entering MUC-7 scored 93.39% of F-measure while human annotators scored 97.60% and 96.95%.[1][2]

(Wikipedia; https://en.wikipedia.org/wiki/Named-entity_recognition)

### 읽어볼만한 자료들
- [Python 게임 서버 안녕하십니까? 몬스터 슈퍼리그 게임 서버 - SMARTSTUDY 박준철](https://www.slideshare.net/joongom/ndc2017-python)
  - Game Server: Flask
  - DB: SQLAlchemy

### 써볼만한 기능을 가진 사이트들

- [RegExr](https://regexr.com)

- ETRI의 <s>공공</s> 인공지능 <s>오픈</s> API·DATA 서비스 포털(http://aiopen.etri.re.kr
  - 장점: 한국어에 대한 수준 높은 언어 분석(형태소 분석), 어휘관계 분석, 질문 분석, 음성 인식 API 제공.
  - 단점: 키 발급받아야 사용가능하고, 그다지 공공·오픈 이라는 느낌이 들지 않음
