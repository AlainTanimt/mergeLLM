# Fusion de LLM 

> Un projet pour fusionner plusieurs modèles de langage pour enrichir les capacités de génération de texte.

## Description
Ce projet vise à combiner les capacités de plusieurs modèles de langage (LLM) afin d’améliorer la génération de texte et d’explorer les performances résultantes d’une approche de fusion. En exploitant les caractéristiques uniques de chaque modèle, la fusion permet d’obtenir des réponses plus cohérentes, diversifiées, ou adaptées à des tâches spécifiques.

Inspiré par un tutoriel de Toward Data Science, ce projet inclut un code adaptable qui permet aux utilisateurs de choisir différents modèles et de définir les paramètres de la fusion. Le résultat est un modèle hybride capable de capter les points forts de chacun pour produire des résultats enrichis en matière de génération de texte et d’analyse de données textuelles.

L’objectif principal est de proposer une solution pratique pour expérimenter avec des modèles de langage de façon modulaire et flexible, en fonction des besoins et des ressources de l’utilisateur.

## Fonctionnalités
- Fusion de plusieurs modèles de langage pour augmenter la précision de génération de texte.
- Options pour enregistrer et tester le modèle fusionné.

## Prérequis
- Python 3.8+
- torch
- transformers
- mergekit

## Conseils
-Fusion des modèles : La fusion de plusieurs modèles de langage ne nécessite pas de GPU, elle peut être effectuée sur CPU sans impact significatif sur les performances. Vous pouvez donc réaliser cette étape sur un environnement CPU standard, ce qui la rend plus accessible même pour les utilisateurs sans GPU.

-Inférence : Pour l'inférence (génération de texte à partir du modèle fusionné), un environnement équipé de GPU est recommandé. Un GPU permet de réduire le temps de génération et d’améliorer les performances globales, particulièrement pour des tâches de génération de texte en temps réel ou pour des modèles volumineux.

## Références
[Article de Towards Data Science](https://towardsdatascience.com/merge-large-language-models-with-mergekit-2118fb392b54)
[Modèle de LLM issue de la fusio sur Hugging Face](https://huggingface.co/AlainTa/Marcoro14-7B-slerp)
