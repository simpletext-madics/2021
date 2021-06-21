
# SimpleText@CLEF-2021 Tâches pilotes

[Accueil](https://simpletext-madics.github.io/2021/clef/fr) | [Appel à communication](https://simpletext-madics.github.io/2021/clef/fr/CFP) | [Dates importantes](https://simpletext-madics.github.io/2021/clef/fr/dates) | [Tâches pilotes](https://simpletext-madics.github.io/2021/clef/fr/tasks)  
[Programme](https://simpletext-madics.github.io/2021/clef/fr/program) | [Publications](https://simpletext-madics.github.io/2021/clef/fr/publications) | [Organisation](https://simpletext-madics.github.io/2021/clef/fr/organisation) | [Contacts](https://simpletext-madics.github.io/2021/clef/fr/contacts) | [<img src="../EN.png" width="30">](https://simpletext-madics.github.io/2021/clef/en/tasks)

---

## Directives pour les tâches pilotes de SimpleText

Nous vous invitons à soumettre aussi bien des passages automatiques que manuels ! Les interventions manuelles doivent être signalées.

---

<button>[Accès](https://simpletext-madics.github.io/2021/clef/fr/tasks)</button> | <button>[Tâche pilote 1](https://simpletext-madics.github.io/2021/clef/fr/task1)</button> | <button>[Tâche pilote 2](https://simpletext-madics.github.io/2021/clef/fr/task2)</button> | <button>[Tâche pilote 3](https://simpletext-madics.github.io/2021/clef/fr/task3)</button>

<br>

## Accès
Veuillez vous inscrire à l'atelier SimpleText@CLEF afin d'accéder aux données : [http://clef2021-labs-registration.dei.unipd.it/](http://clef2021-labs-registration.dei.unipd.it/)  
Après l'inscription, vous recevrez un courriel contenant les informations nécessaires pour vous connecter au serveur de données : [https://guacamole.univ-avignon.fr](https://guacamole.univ-avignon.fr)

### Soumission des résultats :
Les participants doivent placer leurs résultats dans le dossier Documents créé pour leur utilisateur.

### 2021 - Dataset
Pour cette édition, nous utilisons le Citation Network Dataset : DBLP+Citation, ACM Citation network ([https://www.aminer.org/citation](https://www.aminer.org/citation)). Un index Elasticsearch est mis à la disposition des participants et est accessible via une API GUI. Cet index est adapté pour :
*	Appliquer des méthodes de base de recherche de passages basées sur des modèles de RI vectoriels ou linguistiques,
*	Générer des modèles d'allocation de Dirichlet latente,
*	Former des Graph Neural Networks pour la recommandation de citations, comme c'est le cas sur [https://stellargraph.readthedocs.io/](https://stellargraph.readthedocs.io/) par exemple, 
*	Appliquer des Transformers bidirectionnels profonds pour l'expansion des requêtes,
*	Et bien plus encore ...

### 2021 - Requêtes
Pour cette édition, les requêtes sont une sélection de titres de presse récents du Guardian enrichis de mots-clés extraits manuellement du contenu de l'article. Il a été vérifié que chaque mot-clé permet d'extraire au moins 5 résumés pertinents. L'utilisation de ces mots-clés est facultative.

*Format d'entrée pour toutes les tâches :*
* Sujets au format MD

<img src="../Query1.png">

* Articles en texte intégral du Guardian (lien, dossier query_related_content avec textes intégraux au format MD)
*	Index ElasticSearch sur le serveur de données suivant (par exemple) : [https://guacamole.univ-avignon.fr/nextcloud/index.php/apps/files/?dir=/simpleText/queries&fileid=570352](https://guacamole.univ-avignon.fr/nextcloud/index.php/apps/files/?dir=/simpleText/queries&fileid=570352)
* Dépôt complet du DBLP au format JSON.GZ
* Extraction des résumés DBLP pour chaque sujet dans le format MD suivant (doc_id, year, abstract) :

<img src="../MDformat.png">
