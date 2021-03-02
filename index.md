<img src="simpletext-logo-blue%20(1).png" style="float:right; margin:0px 15px 15px 0px; cursor:pointer; cursor:hand; border:0" width="200" height="200"/>

# [English version here](https://simpletext-madics.github.io/2021/en)
# Atelier SimpleText – GDR IA (2021) 
**Simplification et Vulgarisation des Textes Scientifiques**


**Responsables**
* Liana Ermakova, HCTI, Univ. Bretagne Occidentale
* Josiane Mothe, IRIT, INS2i
* Eric Sanjuan, LIA, INS2i

* **Correspondant ComDIR :** Frédéric Bimbot

**Thématiques**

* Traitement automatique de la langue naturelle, Recherche d’information, Journalisme scientifique, Vulgarisation scientifique

**Données concernées**

* Articles scientifiques, Résumés des articles scientifiques, Articles Wikipedia, Articles du journalisme scientifique


**Contexte scientifique**

La culture scientifique, y compris les questions liées à la santé, est importante pour que les citoyens puissent prendre de bonnes décisions, évaluer la qualité de l’information, maintenir leur santé physiologique et mentale, et éviter de tomber dans les pièges des charlatans.

Par exemple, les histoires que les individus trouvent crédibles peuvent déterminer leur réponse à la pandémie COVID-19, y compris l’application de la distanciation sociale et l’utilisation de faux traitements médicaux dangereux. Malheureusement, les textes diffusés sur des médias sociaux qui maximisent leur viralité (propagation) en sollicitant nos émotions sont souvent plus directement accessibles que les publications scientifiques qui poursuivent un idéal d’objectivation et de recul.

L’amélioration de la compréhensibilité des textes et leur adaptation à différents publics reste un problème non résolu. Malgré l’existence des jeux de données comme WebSPlit et WikiSplit, la simplification automatique de textes est réduite à la tâche “Split and Rephrase” (Aharoni and Goldberg, 2018; Botha et al., 2018; Narayan et al., 2017). Un autre jeu de données existant est basé sur Simple Wikipedia (Coster and Kauchak, 2011). Bien qu’il y ait eu quelques tentatives pour aborder la question de la compréhensibilité du texte, elles sont principalement basées sur des formules de lisibilité, dont la capacité à réduire la difficulté du texte n’est pas démontrée de manière convaincante (Collins-Thompson and Callan, 2004; Leroy et al., 2013; Flesch, 1948; Gunning, 1968; Si and Callan, 2001). Les recherches récentes appliquent les modèles Transformers (BERT) pour simplifier des phrases (Fang and Stevens, 2019; Maruyama and Yamamoto, 2019; Zhao et al., 2018). Contrairement aux travaux précédents, l’atelier SimpleText visera le problème de manque de connaissances qui peut être un empêchement grave pour la compréhension du texte scientifique (O’Reilly et al., 2019).

L’amélioration de la compréhensibilité des textes et leur adaptation à différents publics posent des défis sociétaux, techniques et d’évaluation.

Il existe un large éventail de défis sociétaux importants que SimpleText vise à décrire plus précisément. La science ouverte est l’une d’entre elles. Rendre la recherche réellement ouverte et accessible à tous implique de les fournir sous une forme lisible et compréhensible au lecteur (Fecher and Friesike, 2014).

La simplification de textes doit également résoudre des défis techniques comme la sélection de passages importants, le résumé de ces passages, la lisibilité des textes, etc. SimpleText vise à un panorama de ses défis techniques en mobilisant différentes disciplines scientifiques concernées.

L’usage, l’usabilité et l’évaluation des textes simplifiés est un autre pan des sujets qu’abordera l’atelier SimpleText.

La vulgarisation scientifique est liée au journalisme scientifique. Contrairement à l’Action MADICS MADONA (Maîtriser l’Analyse interactive de DOnnées pour la NArration journalistique) qui vise la génération d’un article à partir de l’analyse des données structurée, l’atelier SimpleText est orienté vers la génération d’un article basée sur les données textuelles (publications scientifiques et leurs résumés).

**Bibliographie**

* Aharoni, R., Goldberg, Y., 2018. Split and Rephrase: Better Evaluation and a Stronger Baseline. ArXiv180501035 Cs.
* Botha, J.A., Faruqui, M., Alex, J., Baldridge, J., Das, D., 2018. Learning To Split and Rephrase From Wikipedia Edit History, in: Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. Presented at the EMNLP 2018, Association for Computational Linguistics, Brussels, Belgium, pp. 732–737. https://doi.org/10.18653/v1/D18-1080
* Collins-Thompson, K., Callan, J., 2004. A Language Modeling Approach to Predicting Reading Difficulty. Proc. HLTNAACL 4.
* Coster, W., Kauchak, D., 2011. Simple English Wikipedia: a new text simplification task, in: Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies. pp. 665–669.
* Fang, F., Stevens, M., 2019. Sentence Simpliﬁcation with Transformer-XL and Paraphrase Rules 10.
* Fecher, B., Friesike, S., 2014. Open science: one term, five schools of thought, in: Opening Science. Springer, Cham, pp. 17–47.
* Flesch, R., 1948. A new readability yardstick. J. Appl. Psychol. 32, p221-233.
* Gunning, R., 1968. The technique of clear writing. McGraw-Hill.
* Hasler, E., de Gispert, A., Stahlberg, F., Waite, A., Byrne, B., 2017. Source sentence simplification for statistical machine translation. Comput. Speech Lang. 45, 221–235. https://doi.org/10.1016/j.csl.2016.12.001
* Inui, K., Fujita, A., Takahashi, T., Iida, R., Iwakura, T., 2003. Text simplification for reading assistance: a project note, in: Proceedings of the Second International Workshop on Paraphrasing - Volume 16, PARAPHRASE ’03. Association for Computational Linguistics, USA, pp. 9–16. https://doi.org/10.3115/1118984.1118986
* Leroy, G., Endicott, J.E., Kauchak, D., Mouradi, O., Just, M., 2013. User evaluation of the effects of a text simplification algorithm using term familiarity on perception, understanding, learning, and information retention. J. Med. Internet Res. 15, e144.
* Maruyama, T., Yamamoto, K., 2019. Extremely Low Resource Text simpliﬁcation with Pre-trained Transformer Language Model. Int. Conf. Asian Lang. Process. 6.
* Narayan, S., Gardent, C., Cohen, S.B., Shimorina, A., 2017. Split and Rephrase, in: Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. Presented at the EMNLP 2017, Association for Computational Linguistics, Copenhagen, Denmark, pp. 606–616. https://doi.org/10.18653/v1/D17-1064
* O’Reilly, T., Wang, Z., Sabatini, J., 2019. How Much Knowledge Is Too Little? When a Lack of Knowledge Becomes a Barrier to Comprehension: Psychol. Sci. https://doi.org/10.1177/0956797619862276
* Si, L., Callan, J., 2001. A statistical model for scientific readability. Proc. Tenth Int. Conf. Inf. Knowl. Manag. 574–576.
* Siddharthan, A., 2002. An architecture for a text simplification system. Presented at the Proceedings of the Language Engineering Conference 2002 (LEC 2002).
* Zhao, S., Meng, R., He, D., Saptono, A., Parmanto, B., 2018. Integrating Transformer and Paraphrase Rules for Sentence Simplification, in: Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing. Presented at the EMNLP 2018, Association for Computational Linguistics, Brussels, Belgium, pp. 3164–3173. https://doi.org/10.18653/v1/D18-1355

#### Objectifs de l’Atelier et principales activités envisagées

Notre objectif premier est de réunir une communauté scientifique interdisciplinaires autour de ces sujets. Nous souhaitons fournir une définition la plus complète possible de la simplification et la vulgarisation des textes scientifiques. Nous envisageons d’organiser des journées d’études pour discuter des défis liés à la simplification et vulgarisation scientifique:
Sociétaux
Linguistiques 
Techniques
D’évaluation
Parallèlement, notre objectif est de réunir cette communauté pour répondre à des challenges de type campagne d’évaluation sur la simplification de textes scientifiques. Nous envisageons trois possibles tâches:
La recherche des connaissances de base
La création des résumés automatiques de  plusieurs documents sur un sujet
La simplification d’un texte scientifique
Cette activité sera réalisée par des équipes multidisciplinaires par exemple en s’appuyant sur des publications scientifiques issues de la plateforme ISTEX (https://www.istex.fr/) qui fournit l'ensemble de ses services sous la forme d'une API Web ou d’autres collections que les organisateurs proposeront à la communauté. L’accès à l'ensemble des ressources de l'API sans demande d'autorisation préalable est autorisé dans la cadre d'activités de recherche. Nous envisageons également d’utiliser des articles Wikipédia et des articles de journalisme scientifique.
