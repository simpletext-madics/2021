
# SimpleText@CLEF-2021 Tâches pilotes

[Accueil](https://simpletext-madics.github.io/2021/clef/fr) | [Appel à communication](https://simpletext-madics.github.io/2021/clef/fr/CFP) | [Dates importantes](https://simpletext-madics.github.io/2021/clef/fr/dates) | [Tâches pilotes](https://simpletext-madics.github.io/2021/clef/fr/tasks)  
[Programme](https://simpletext-madics.github.io/2021/clef/fr/program) | [Publications](https://simpletext-madics.github.io/2021/clef/fr/publications) | [Organisation](https://simpletext-madics.github.io/2021/clef/fr/organisation) | [Contacts](https://simpletext-madics.github.io/2021/clef/fr/contacts) | [<img src="../EN.png" width="30">](https://simpletext-madics.github.io/2021/clef/en/task1)

---

## Directives pour les tâches pilotes de SimpleText

Nous vous invitons à soumettre aussi bien des passages automatiques que manuels ! Les interventions manuelles doivent être signalées.

---

<button>[Accès](https://simpletext-madics.github.io/2021/clef/fr/tasks)</button> | <button>[Tâche pilote 1](https://simpletext-madics.github.io/2021/clef/fr/task1)</button> | <button>[Tâche pilote 2](https://simpletext-madics.github.io/2021/clef/fr/task2)</button> | <button>[Tâche pilote 3](https://simpletext-madics.github.io/2021/clef/fr/task3)</button>

<br>

## Tâche pilote 1 : Sélectionner les passages à inclure dans un résumé simplifié - Simplification de contenu

Cette tâche pilote vise à retrouver, dans une grande base de données bibliographiques scientifiques avec résumés, tous les passages qui seraient pertinents pour illustrer un article d'un grand journal international grand public. Les passages extraits doivent pouvoir être insérés comme de simples citations dans l'article original.

*Format de sortie :*  
 
Un maximum de 1000 passages à inclure dans un résumé simplifié dans un fichier TSV (Tab-Separated Values) avec les champs suivants :
* *run_id* : ID du passage commençant par team_id_
* *manual* : Si l'exécution est manuelle {0,1}
* *topic_id* : ID du sujet
* *doc_id* : ID du document source
* *passage* : Texte du passage sélectionné
* *rank* : Rang de passage

*run_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; manual &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; topic_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; doc_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; passage &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rank*

### Évaluation  
Le regroupement de phrases et les métriques automatiques seront utilisés pour évaluer ces résultats. La pertinence du document source sera évaluée ainsi que les éventuels problèmes d'anaphore non résolus.

Exemple de SORTIE :

| run_id | manual | topic_id | doc_id | passage | rank |
|:-------|:-------|:---------|:-------|:--------|:-----|
| ST1_1 | 1 | 1 | 3000234933 | People are becoming increasingly comfortable using Digital Assistants (DAs) to interact with services or connected objects. | 1 |
| ST1_1 | 1 | 1 | 3003409254 | big data and machine learning (ML) algorithms can result in discriminatory decisions against certain protected groups defined upon personal data like gender, race, sexual orientation etc. | 2 |
| ST1_1 | 1 | 1 | 3003409254 | Such algorithms designed to discover patterns in big data might not only pick up any encoded societal biases in the training data, but even worse, they might reinforce such biases resulting in more severe discrimination. | 3 |  
