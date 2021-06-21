
# SimpleText@CLEF-2021 Pilot tasks

[Home](https://simpletext-madics.github.io/2021/clef/en) | [Call for papers](https://simpletext-madics.github.io/2021/clef/en/CFP) | [Important dates](https://simpletext-madics.github.io/2021/clef/en/dates) | [Pilot tasks](https://simpletext-madics.github.io/2021/clef/en/tasks)  
[Program](https://simpletext-madics.github.io/2021/clef/en/program) | [Publications](https://simpletext-madics.github.io/2021/clef/en/publications) | [Organisers](https://simpletext-madics.github.io/2021/clef/en/organisers) | [Contact](https://simpletext-madics.github.io/2021/clef/en/contact) | [<img src="../FR.png" width="30">](https://simpletext-madics.github.io/2021/clef/fr/task1)

---

## SimpleText Pilot Task Guidelines

We invite you to submit both automatic and manual runs! Manual intervention should be reported.

---

[Access](https://simpletext-madics.github.io/2021/clef/en/tasks) | [Pilot task 1](https://simpletext-madics.github.io/2021/clef/en/task1) | [Pilot task 2](https://simpletext-madics.github.io/2021/clef/en/task2) | [Pilot task 3](https://simpletext-madics.github.io/2021/clef/en/task3)

<br>

## Pilot Task 1: Selecting passages to include in a simplified summary - Content Simplification

Given an article from a major international newspaper general audience, this pilot task aims at retrieving from a large scientific bibliographic database with abstracts, all passages that would be relevant to illustrate this article. Extracted passages should be adequate to be inserted as plain citations in the original paper.

*Output format:*  
 
A maximum of 1000 passages to be included in a simplified summary in a TSV (Tab-Separated Values) file with the following fields:
* *run_id*: Run ID starting with team_id_
* *manual*: Whether the run is manual {0,1}
* *topic_id*: Topic ID
* *doc_id*: Source document ID
* *passage*: Text of the selected passage
* *rank*: Passage rank

*run_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; manual &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; topic_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; doc_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; passage &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rank*

### Evaluation  
Sentence pooling and automatic metrics will be used to evaluate these results. The relevance of the source document will be evaluated as well as potential unresolved anaphora issues.

OUTPUT example:

| run_id | manual | topic_id | doc_id | passage | rank |
|:-------|:-------|:---------|:-------|:--------|:-----|
| ST1_1 | 1 | 1 | 3000234933 | People are becoming increasingly comfortable using Digital Assistants (DAs) to interact with services or connected objects. | 1 |
| ST1_1 | 1 | 1 | 3003409254 | big data and machine learning (ML) algorithms can result in discriminatory decisions against certain protected groups defined upon personal data like gender, race, sexual orientation etc. | 2 |
| ST1_1 | 1 | 1 | 3003409254 | Such algorithms designed to discover patterns in big data might not only pick up any encoded societal biases in the training data, but even worse, they might reinforce such biases resulting in more severe discrimination. | 3 |
