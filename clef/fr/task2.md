
# SimpleText@CLEF-2021 Tâches pilotes

[Accueil](https://simpletext-madics.github.io/2021/clef/fr) | [Appel à communication](https://simpletext-madics.github.io/2021/clef/fr/CFP) | [Dates importantes](https://simpletext-madics.github.io/2021/clef/fr/dates) | [Tâches pilotes](https://simpletext-madics.github.io/2021/clef/fr/tasks)  
[Programme](https://simpletext-madics.github.io/2021/clef/fr/program) | [Publications](https://simpletext-madics.github.io/2021/clef/fr/publications) | [Organisation](https://simpletext-madics.github.io/2021/clef/fr/organisation) | [Contacts](https://simpletext-madics.github.io/2021/clef/fr/contacts) | [<img src="../EN.png" width="30">](https://simpletext-madics.github.io/2021/clef/en/task2)

---

## Directives pour les tâches pilotes de SimpleText

Nous vous invitons à soumettre aussi bien des passages automatiques que manuels ! Les interventions manuelles doivent être signalées.

---

[Accès](https://simpletext-madics.github.io/2021/clef/fr/tasks) | [Tâche pilote 1](https://simpletext-madics.github.io/2021/clef/fr/task1) | [Tâche pilote 2](https://simpletext-madics.github.io/2021/clef/fr/task2) | [Tâche pilote 3](https://simpletext-madics.github.io/2021/clef/fr/task3)

<br>

## Tâche pilote 2 : Identifier les concepts difficiles à comprendre pour les non experts - Simplification de contenu

L'objectif de cette tâche pilote est de déterminer quels termes (jusqu'à 10) nécessitent une explication et une contextualisation pour aider un lecteur à comprendre un texte scientifique complexe ; par exemple, en ce qui concerne une requête, les termes qui doivent être contextualisés (avec une définition, un exemple et/ou un cas d'utilisation).

*Fomat de sortie :*  

Liste des termes à contextualiser dans un fichier TSV tabulé avec les champs suivants :
* *run_id* : ID du passage commençant par team_id_
* *manual* : Si l'exécution est manuelle {0,1}
* *topic_id* : ID du sujet
* *passage_text* : Texte du passage
* *term* : Terme ou autre expression à expliquer
* *rank* : Importance de l'explication du terme

Run_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; manual &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; topic_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; passage_text &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; term &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rank

### Évaluation
Le regroupement de termes et de métriques automatiques (NDCG,...) seront utilisés pour évaluer ces résultats.

Exemple de SORTIE :

| run_id | manual | topic_id | passage_text | term | rank |
|:-------|:-------|:---------|:-------------|:-----|:-----|
| ST_1 | 1 | 1 | Automated decision making based on big data and machine learning (ML) algorithms can result in discriminatory decisions against certain protected groups defined upon personal data like gender, race, sexual orientation etc. Such algorithms designed to discover patterns in big data might not only pick up any encoded societal biases in the training data, but even worse, they might reinforce such biases resulting in more severe discrimination. The majority of thus far proposed fairness-aware machine learning approaches focus solely on the pre-, in- or post-processing steps of the machine learning process, that is, input data, learning algorithms or derived models, respectively. However, the fairness problem cannot be isolated to a single step of the ML process. Rather, discrimination is often a result of complex interactions between big data and algorithms, and therefore, a more holistic approach is required. The proposed FAE (Fairness-Aware Ensemble) framework combines fairness-related interventions at both pre- and postprocessing steps of the data analysis process. In the preprocessing step, we tackle the problems of under-representation of the protected group (group imbalance) and of class-imbalance by generating balanced training samples. In the post-processing step, we tackle the problem of class overlapping by shifting the decision boundary in the direction of fairness.| machine learning | 1 |
| ST_1 | 1 | 1 | Automated decision making based on big data and machine learning (ML) algorithms can result in discriminatory decisions against certain protected groups defined upon personal data like gender, race, sexual orientation etc. Such algorithms designed to discover patterns in big data might not only pick up any encoded societal biases in the training data, but even worse, they might reinforce such biases resulting in more severe discrimination. The majority of thus far proposed fairness-aware machine learning approaches focus solely on the pre-, in- or post-processing steps of the machine learning process, that is, input data, learning algorithms or derived models, respectively. However, the fairness problem cannot be isolated to a single step of the ML process. Rather, discrimination is often a result of complex interactions between big data and algorithms, and therefore, a more holistic approach is required. The proposed FAE (Fairness-Aware Ensemble) framework combines fairness-related interventions at both pre- and postprocessing steps of the data analysis process. In the preprocessing step, we tackle the problems of under-representation of the protected group (group imbalance) and of class-imbalance by generating balanced training samples. In the post-processing step, we tackle the problem of class overlapping by shifting the decision boundary in the direction of fairness.| societal biases | 2 |
| ST_1 | 1 | 1 | Automated decision making based on big data and machine learning (ML) algorithms can result in discriminatory decisions against certain protected groups defined upon personal data like gender, race, sexual orientation etc. Such algorithms designed to discover patterns in big data might not only pick up any encoded societal biases in the training data, but even worse, they might reinforce such biases resulting in more severe discrimination. The majority of thus far proposed fairness-aware machine learning approaches focus solely on the pre-, in- or post-processing steps of the machine learning process, that is, input data, learning algorithms or derived models, respectively. However, the fairness problem cannot be isolated to a single step of the ML process. Rather, discrimination is often a result of complex interactions between big data and algorithms, and therefore, a more holistic approach is required. The proposed FAE (Fairness-Aware Ensemble) framework combines fairness-related interventions at both pre- and postprocessing steps of the data analysis process. In the preprocessing step, we tackle the problems of under-representation of the protected group (group imbalance) and of class-imbalance by generating balanced training samples. In the post-processing step, we tackle the problem of class overlapping by shifting the decision boundary in the direction of fairness. | ML | 3 |