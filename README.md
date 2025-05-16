# Usage de l'intelligence artificielle pour les professionnels du droit - B3 (HEAD)

contact : rdassignies [at] protonmail.ch

## Informations utiles
Sur cette page, vous trouverez toutes les informations utiles pour le cours :

- [le syllabus](https://docs.google.com/document/d/1tMo-4-vbf_abE_ZPOGAkT80tw-468RPH_prowdSG2k4/edit?usp=sharing),
- les documents associés aux cours,
- les exercices pratiques.
- [my.beekast.com](https://my.beekast.com/kast/6806760bd6878e4e24d88fd4/presentation)

## Objectifs du cours 
Ce cours a un double objectif. 

Tout d’abord, il vise à donner aux futurs juristes une culture d’interface, c’est-à-dire une bonne appréhension de l’Intelligence Artificielle (IA) dans ses différentes dimensions - technique, sécuritaire, et sociétale - et de comprendre ses implications juridiques. 

Ensuite, il a pour ambition de fournir aux étudiants des bases techniques pour comprendre et implémenter les outils informatiques qu’ils utiliseront dans leur quotidien au sein de leur pratique professionnelle. 

# Modalité d'examen : 
- Contrôle continue (40% de la note)
- Devoir à la maison (60% de la note)

# Devoir à la maison pour le 16 mai 2025

- Résumé du cours sur les notions essentielles vues en cours le 15 mai 2025 
- Rédiger un prompt system à partir du style d'un auteur 

***********
## Les fiches de cours 
### Les modèles de langage

https://drive.google.com/file/d/13UQluiO1kiZx5gOeRiTP-zVqUvL8SIiV/view?usp=sharing 

### IA, les fondamentaux

https://drive.google.com/file/d/1dsUim_xLJlEjH44FmxNHCwYOVRnVspfb/view?usp=sharing



## Les modèles en complément de ChatGPT : 

**Outil notebookLM** :

https://notebooklm.google.com/ 

https://mistral.ai/fr/

https://claude.ai

https://mapify.so/fr/app/new

## Les notebooks

### Les notebooks et pages sur la regression linéaire et les réseaux de neurones
https://colab.research.google.com/drive/1Veq38eBTALfimrhl6BrGo3BTQ-pbMf6B#scrollTo=soeuaBRhGMDU 

https://colab.research.google.com/drive/14CnE-dfNStOE1epLo8glFuVrxXYGtE8m

https://lab.dassignies.law/pedagogie/regression_lineaire_manuelle/

https://lab.dassignies.law/pedagogie/regression_lineaire_automatique/ 


## Exemples

### Exemples de jeu de données 

[https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1)

## Le prompting

## Définition et bonnes pratiques

https://github.com/rdassignies/prompting (exemples)

https://drive.google.com/file/d/1MGYT3YKJJ0tqsgGo7u4-IPofz2O2MyT4/view?usp=sharing (resumé ) 

Pour aller plus loin: 
https://learnprompting.org/docs/introduction

**Claude prompt leak**

https://raw.githubusercontent.com/asgeirtj/system_prompts_leaks/refs/heads/main/claude.txt 

**jailbreak**

https://huggingface.co/datasets/rubend18/ChatGPT-Jailbreak-Prompts

https://learnprompting.org/docs/prompt_hacking/jailbreaking

https://gandalf.lakera.ai/intro?_gl=1*1cglg05*_gcl_au*MjI2NDkwMzYwLjE3MzEzNTk5MjU.

## Exercices de prompting

### Explorer un sujet : la reconnaissance faciale 

#### Elaborer sa base documentaire 

[Proposition de loi (n°1317 - 17ème législature)](https://www.assemblee-nationale.fr/dyn/17/textes/l17b1317_proposition-loi.pdf)
[Reconnaissance faciale - document CNIL 2019](https://www.cnil.fr/sites/cnil/files/atoms/files/reconnaissance_faciale.pdf)
[Réglement européen sur l'intelligence artificielle](https://eur-lex.europa.eu/legal-content/FR/TXT/PDF/?uri=OJ:L_202401689)

Elargir les recherches et trouver des documents pertinents. Quelles stratégies ? 

#### Explorer les documents 

Exploration des documents à l'aide de notebookLM

#### Générer des contenus 

Comment générer des fiches de cours, des tableaux de synthèse ... ? 


#### Rédiger un prompt qui illustre la notion de few-shot learning

Vous devez rédiger un prompt qui montre comment anonymiser des données. Pour cela, vous devez fournir au modèle trois exemples d’anonymisation.

#### Rédiger un prompt qui permet d'apprendre la notion de syllogisme juridique

Vous devez rédiger un prompt qui explique et illustre la notion de syllogisme.

La réponse doit être sauvegardée sous forme de fiche, au format PDF, pour vos révisions.

#### Rédiger un prompt pour résumer une notion apprise en cours

À partir d’un extrait d’un de vos cours, faites rédiger une synthèse sous forme de fiche.

Procédez à l’analyse critique de cette fiche et, si besoin, modifiez-la.

Cette fiche doit être sauvegardée au format PDF.

#### Générer une fiche d’arrêt à partir de cet arrêt de la Cour de cassation

Cet exercice illustre la notion de synthèse (résumé) et d’analyse.

[Code de déverrouillage d’un écran de téléphone et cryptologie – Cour de cassation](https://www.courdecassation.fr/toutes-les-actualites/2022/11/07/code-de-deverrouillage-dun-ecran-de-telephone-et-cryptologie)

[Arrêt sur Légifrance](https://www.legifrance.gouv.fr/juri/id/JURITEXT000046583035?init=true&page=1&query=21-83.146&searchField=ALL&tab_selection=all)

#### Générer l’analyse de cet arrêt et la critiquer

Cet exercice illustre la notion d’analyse (syllogisme).

> Mais attendu que si la faute de la victime n'exonère totalement le gardien qu'à la condition de présenter les caractères d'un événement de force majeure, cette exigence est satisfaite lorsque cette faute présente, lors de l'accident, un caractère imprévisible et irrésistible; qu'ayant retenu que la chute de Corinne sur la voie ne pouvait s'expliquer que par l'action volontaire de la victime, que le comportement de celle-ci n'était pas prévisible dans la mesure où aucun des préposés de la RATP ne pouvait deviner sa volonté de se précipiter contre la rame, qu'il n'avait été constaté aucun manquement aux règles de sécurité imposées au transporteur et que celui-ci ne saurait se voir reprocher de ne pas prendre toutes mesures rendant impossible l'action de personnes ayant la volonté de produire le dommage auquel elles s'exposent volontairement, la cour d'appel a décidé à bon droit que la faute commise par la victime exonérait la RATP de toute responsabilité.

#### Cas pratique : Demander à un chatbot de proposer des argumentations opposées

Cet exercice illustre la notion d’analyse.

Les parties se disputent sur la qualification des faits, car de celle-ci découle l’application du droit. Voici des situations juridiques. L’élément de qualification qui oppose les deux parties est également indiqué.

**Exemple** : M. Martel, ingénieur commercial, salarié de la société IBP, refuse de changer de lieu de travail car cela implique qu'il déménage à 800 km de son lieu de résidence habituel. Si la modification est substantielle, elle doit recevoir l'accord exprès du salarié, sinon elle n'est pas valable. Le changement de lieu de travail à plus de 800 km du lieu initialement prévu au contrat constitue-t-il une modification substantielle ou non substantielle du contrat de travail ?

## Pour aller plus loin

https://www.youtube.com/c/3blue1brown 

https://pll.harvard.edu/course/cs50-introduction-computer-science


