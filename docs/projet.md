
Vous allez réaliser (par groupes d'une dizaine de personnes) un projet d'urbanisation complet où vous allez simuler la mise en place d'une architecture d'entreprise urbanisée pour une entreprise de votre invention. 

# Délivrables Attendus

   * Un rapport détaillé, décrivant les étapes de conception du système et les choix d'implémentation.
   * Un repository Github (ou équivalent) comportant le code du système, bien organisé et commenté, et le fichier XML (Open Exchange File) du projet Archimate.
   * Une présentation et une démo, de 15 minutes (Date à définir avant les examens finaux).

# Note

Ce projet composera 70% de la note de TP, les 30% restants seront sur l'assiduité et la consistance dans la réalisation des TPs.

# Supports nécessaires

Pour réaliser ce projet, je vous donne ici les supports dont vous aurez besoin:

| Lien        | Description                          |
| :---------- | :----------------------------------- |
| [![Tutoriel](img/projet/tutoriels.png)](files/ArchiSurance_case_study.pdf)      | Tutoriel: Archisurance Case Study  |
| [![Archimate](img/projet/archi.png)](https://www.archimatetool.com/download/)       | Télécharger Archi : Archimate Modeler |
| [![Fondamentaux d'Archimate](img/projet/nuls.png)](https://www.urbanisation-si.com/archimate-pour-les-nuls-les-fondamentaux-1)      | Archimate pour les nuls: Les fondamentaux |
| [![Templates TOGAF](img/projet/catalogue.png)](https://github.com/leonux/architecture-work/tree/master/Togaf-material/TOGAF_9_Templates)      | Templates de délivrables TOGAF |

# Description du Projet

Vous allez concevoir une entreprise imaginaire (à l'instar de Archisurance, dont je vous ai donné le tutoriel), qui contenait à la base un ensemble d'applications éparpillées sur plusieurs départements. Il vous a été demandé en tant qu'équipe de créer une architecture urbanisée permettant d'assurer les besoins suivants pour votre entreprise:

   * Assurer des communications fluides entre les différentes applications et services de l'entreprise.
   * Unifier le langage utilisé par les différents départements.
   * Synchroniser les données et gérer les dépendances et les redondances.
   * Éviter au maximum de changer les habitudes de travail des équipes, surtout celles des départements RH et finance.

On vous demande de respecter les principes TOGAF pour votre nouveau système. Vous allez donc utiliser Archimate pour créer et concevoir les diagrammes nécessaires pour chacune des étapes de l'ADM (suivre pour cela l'approche dans le tutoriel). Ces diagrammes seront ensuite utilisés pour décider de l'architecture technique à mettre en place. 
Une fois la conception globale réalisée, vous devez développer un POC (_proof of concept_) d'un système urbanisé simplifié, respectant les contraintes suivantes:

   * Avoir au moins 5 services sur 2 ou 3 départements différents.
   * Créer au moins 2 processus métiers reliant ces services. 
   * Utiliser les outils vus en TP (ou équivalents) de façon à avoir:
      * Un API gateway
      * Au moins deux ESBs
      * Un serveur de workflow.


# Rendus 

## Rapport

Le rapport **s'adresse aux responsables techniques, pour la plupart ayant une idée sur TOGAF (certains mêmes sont certifiés TOGAF)**. Il devra être complet et présenter les informations suivantes:
   
   * Une description du métier de l'entreprise, et de la problématique à résoudre.
   * L'état actuel de l'entreprise (avant urbanisation).
   * Les différents diagrammes et architectures, en respectant la méthode ADM (commencer par les besoins métiers pour arriver aux besoins techniques).
   * Présentation des choix techniques réalisés.
   * Présentation des résultats d'implémentation et d'exécution des workflows.

## Présentation

La présentation finale devra durer 15 minutes au maximum (avec 5 minutes de questions/réponses) et **sera adressée au chef de l'entreprise ainsi qu'aux différents départements (pas aux responsables techniques)**. Vous devez donc savoir présenter l'intérêt du nouveau système (qui va coûter en temps et argent à toutes les parties prenantes) et de valoriser le POC que vous avez développé avec les quelques services sélectionnés. 


## Le jour de la présentation

Il faut apporter le rapport imprimé avec vous le jour de la présentation. Chaque groupe va présenter son travail devant l'enseignante et ses autres camarades, qui vont jouer le rôle des différent intervenants dans l'entreprise. Vous êtes libres de choisir le format de la présentation.
