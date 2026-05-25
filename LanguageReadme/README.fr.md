<p align="center">
  <strong>-------> |</strong>
  <a href="/LanguageReadme/README.md">中文</a> |
  <a href="/LanguageReadme/README.ru.md">Russian</a> |
  <a href="/LanguageReadme/README.en.md">English</a> |
  <a href="/LanguageReadme/README.fr.md">Français</a>
  <strong>| <-------</strong>
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/xszyou)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](https://github.com/xszyou/fay-ue5/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/xszyou?style=flat&logo=github&label=Stars&color=orange)](https://github.com/xszyou)

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../images/icon.png" alt="Fay">
    <img alt="Project Logo" src="../images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h2>UE5 Digital Human Project (Metahuman)</h2>
</div>

---

- [Ce projet est un projet open-source complet de digital human basé sur UE, pouvant être utilisé avec le framework Fay pour réaliser divers scénarios d'application : animateur virtuel, promotion en direct, guide de produits, assistant vocal, assistant vocal à distance, interaction avec un digital human, recruteur digital et évaluation psychologique, Jarvis, Her](https://github.com/xszyou/Fay)

- Pour rejoindre le groupe de discussion, veuillez suivre le compte public : fay数字人. Adresse du document : [​‌metahuman(ue) - Feishu Cloud Document](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# Démarrage du digital human UE
| | |
|-------------:|:-------------|
| **ID du cours**     | `course-1775792095810` |
| **Auteur**       | `郭泽斌` |
| **Version**       | `1.0.` |
| **Nombre de chapitres**     | `5` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package du cours** | [Démarrage du digital human UE.zip](<../UE 数字人启动.zip>) |

## Couverture

![Couverture Démarrage du digital human UE](<../images/course1/cover.png>)

## Table des matières

> 1. Exigences matérielles
> 2. Installer et démarrer le framework Fay
> 3. Activer le microphone et l'éveil, désactiver le haut-parleur
> 4. Télécharger et exécuter le package de fonctionnement du digital human UE
> 5. Vérification de la connexion et test de dialogue

---

## Section 1 : Exigences matérielles

![Support de cours](<../images/course1/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7ème génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7ème génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installer et démarrer le framework Fay

![Support de cours](<../images/course1/section-02-01.png>)

La première étape pour démarrer le digital human UE consiste à installer et démarrer le framework Fay.

Fay est le moteur principal de la solution de digital human présentée ici, responsable du traitement de la reconnaissance vocale, de la génération de dialogue et de la synthèse vocale.

Veuillez d'abord suivre l'URL du document officiel fourni dans le bloc de code à droite pour télécharger et installer Fay. Le document officiel contient une description complète des dépendances requises et des étapes d'installation. Veuillez suivre les instructions à la lettre.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour les messages, les personnages, MCP, etc.

Sur la page d'accueil de Fay, dans le coin inférieur gauche, se trouve un bouton vert circulaire bien visible. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois démarré avec succès, le voyant d'état de Fay s'allumera, indiquant que le système est en cours d'exécution et prêt à se connecter au digital human UE.

> [!NOTE]
> Documentation officielle du framework Fay
> Veuillez suivre les instructions à l'URL ci-dessous pour télécharger, installer et démarrer Fay.
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer les services Fay.

---

## Section 3 : Activer le microphone et l'éveil, désactiver le haut-parleur

![Support de cours](<../images/course1/section-03-01.png>)

Une fois Fay démarré, la prochaine étape essentielle consiste à vérifier que le microphone est activé, que le haut-parleur est désactivé et que la fonction d'éveil est activée.

Le modèle de digital human UE présenté aujourd'hui ne dispose pas d'un module de captation audio indépendant. Il dépend du matériel local exécutant Fay. Cependant, il possède un module de lecture audio indépendant qui jouera les fichiers audio générés par Fay. Ces fichiers audio doivent cependant être lus sur la même machine.

Si la fonction d'éveil de Fay est désactivée et que vous ne disposez pas de matériel de captation audio professionnel, Fay pourrait capter les sons émis par le digital human lui-même, provoquant un effet de boucle sonore qui dégraderait gravement l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, êtes-vous là ?" pour vérifier si Fay reçoit correctement votre voix.

---

## Section 4 : Télécharger et exécuter le package de fonctionnement du digital human UE

![Support de cours](<../images/course1/section-04-01.png>)

Une fois que Fay est prêt, la prochaine étape consiste à télécharger et démarrer le package de fonctionnement du digital human UE.

Veuillez télécharger la dernière version du package de fonctionnement du digital human UE à l'URL ci-dessous. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire dédié, puis double-cliquez sur le fichier exécutable (.exe) contenu dans le dossier.

Une fois le package démarré, le digital human UE apparaîtra dans une fenêtre indépendante. Vous verrez une figure virtuelle vêtue d'une tenue professionnelle blanche se tenir sur une scène.

Après le démarrage, le digital human tentera automatiquement de se connecter au service Fay en cours d'exécution sur la machine locale. Ce processus de connexion est entièrement automatisé, vous n'avez pas besoin de configurer manuellement le réseau ou l'adresse. Ce design simplifie grandement le processus de déploiement, permettant aux utilisateurs non techniques de se familiariser rapidement et de réduire les obstacles à la mise en place d'un système complet de digital human.

> [!NOTE]
> Adresse de téléchargement du package de fonctionnement du digital human UE
> 
> Après téléchargement, décompressez l'archive et double-cliquez sur le fichier exécutable (.exe) contenu.
> 
> Une fois démarré, le digital human se connectera automatiquement au service Fay en cours d'exécution sur la machine locale.
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

---

## Section 5 : Vérification de la connexion et test de dialogue

![Support de cours](<../images/course1/section-05-01.png>)

La dernière étape consiste à vérifier si la connexion entre le digital human UE et Fay a été établie avec succès, puis à effectuer un test de dialogue complet.

Une fois le digital human UE démarré, revenez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le digital human UE s'est connecté avec succès au service Fay, et que la communication bidirectionnelle est entièrement établie.

Une fois la connexion confirmée, vous pouvez parler dans le microphone pour saluer le digital human. Essayez de dire : "Bonjour, pouvez-vous vous présenter ?" et observez la réaction du digital human.

Si vous voyez le digital human changer d'expression et de mouvements de bouche, et que vous entendez une réponse vocale claire dans la fenêtre de fonctionnement du digital human UE, félicitations, vous avez réussi à démarrer et connecter le digital human UE !

À ce stade, tout le processus de démarrage du digital human UE est terminé. Vous disposez maintenant d'un partenaire digital capable d'écouter, de parler et d'interagir. Vous pouvez commencer à explorer davantage de scénarios d'application intéressants.

---
---

# Édition du projet digital human UE
| | |
|:-------------|:-------------|
| **ID du cours**     | `course-1775804088429` |
| **Auteur**       | `郭泽斌` |
| **Version**       | `1.0.0` |
| **Nombre de chapitres**     | `11` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package du cours** | [Édition du projet digital human UE.zip](<../UE 数字人工程编辑.zip>) |

## Couverture

![Couverture Édition du projet digital human UE](<../images/course2/cover.png>)

## Table des matières

> 1. Exigences matérielles
> 2. Installer et démarrer le framework Fay
> 3. Activer le microphone et l'éveil, désactiver le haut-parleur
> 4. Installer Epic Games Launcher
> 5. Installer UE 5.6 Engine
> 6. Télécharger et décompresser le package du projet digital human UE
> 7. Installer les plugins
> 8. Démarrer le projet
> 9. Vérifier les plugins
> 10. Aperçu du projet en cours d'exécution
> 11. Vérification de la connexion et test de dialogue

---

## Section 1 : Exigences matérielles

![讲义](<../images/course2/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installer et lancer le framework Fay

![讲义](<../images/course2/section-02-01.png>)

La première étape pour démarrer un Metahuman dans UE consiste à installer et lancer le framework Fay.

Fay est le framework central qui pilote cette solution de Metahuman. Il gère des étapes clés telles que la reconnaissance vocale, la génération de dialogues et la synthèse vocale.

Veuillez tout d'abord télécharger et installer Fay en suivant l'URL de la documentation officielle fournie dans le bloc de code à droite. La documentation officielle contient une description complète des dépendances requises et des étapes d'installation. Suivez les instructions à la lettre.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une console simple, avec un menu à gauche contenant des entrées pour des fonctionnalités telles que Messages, Personnage, MCP, etc.

Sur la page d'accueil de Fay, en bas à gauche, se trouve un grand bouton rond vert pour allumer le système. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est opérationnel et prêt à se connecter avec le Metahuman d'UE.

> [!NOTE]
> Documentation officielle du framework Fay pour Metahuman
> 
> Veuillez suivre les instructions à l'URL suivante pour télécharger, installer et démarrer Fay :
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> Une fois l'installation terminée, cliquez sur le bouton rond vert en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.

---

## Section 3 : Activer le microphone et le réveil, désactiver le haut-parleur

![讲义](<../images/course2/section-03-01.png>)

Après avoir démarré Fay, l'étape suivante essentielle consiste à vérifier que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée. 

Le modèle de Metahuman présenté aujourd'hui ne dispose pas de module de captation sonore indépendant. Il doit donc s'appuyer sur Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture audio indépendant qui jouera l'audio généré par Fay, mais cet audio doit également être émis sur la même machine.

Si la fonction de réveil de Fay est désactivée et que vous ne disposez pas de matériel de captation sonore professionnel, Fay risque de capter les sons émis par le Metahuman lui-même, ce qui peut entraîner une boucle d'écho et nuire gravement à l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez tester le microphone en disant : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir votre voix correctement.

---

## Section 4 : Installer Epic Games Launcher

![讲义](<../images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel d'Unreal Engine à l'adresse suivante : https://www.epicgames.com pour télécharger l'installateur d'Epic Games et procéder à son installation.

> 
> 
> Site officiel d'UE : https://www.epicgames.com
> 
> 

---

## Section 5 : Installer Unreal Engine 5.6

![讲义](<../images/course2/section-05-01.png>)

Ensuite, ouvrez Epic Games Launcher, sélectionnez l'onglet "Unreal Engine" sur la gauche, puis choisissez "Bibliothèque" dans la barre supérieure. Cliquez sur le bouton "+" à côté de la version du moteur, sélectionnez la version 5.6 dans le menu déroulant qui apparaît sous le bloc du moteur, cliquez sur "Installer" et attendez la fin de l'installation.

> 
> Remarque : La version 5.6 n'apparaît pas dans les illustrations de l'auteur car elle est déjà installée.
> 

---

## Section 6 : Télécharger et décompresser le package de projet Metahuman UE

![讲义](<../images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et démarrer le package de projet Metahuman UE.

Veuillez télécharger la dernière version du package de projet Metahuman UE à l'adresse suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire distinct pour une utilisation ultérieure.

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## Section 7 : Installer les plugins

Une fois l'installation de la version 5.6 du moteur terminée, vous pouvez rechercher et installer les plugins illustrés via Epic Games Launcher. Bien entendu, vous pouvez également demander les fichiers des plugins au personnel de la communauté Fay Metahuman. Décompressez les plugins dans le répertoire "plugins" du projet Metahuman.

---

## Section 8 : Démarrer le projet

![讲义](<../images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire et attendez que le démarrage soit terminé. Assurez-vous d'avoir au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

---

## Section 9 : Vérifier les plugins

![讲义](<../images/course2/section-09-01.png>)

Après le démarrage du projet, cliquez sur le menu "Outils", sélectionnez "Plugins", puis "Installés". Assurez-vous que les 4 plugins installés précédemment sont bien activés.

---

## Section 10 : Lancer l'aperçu du projet

![讲义](<../images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton "Exécuter" en haut. Vous verrez alors le Metahuman en mode aperçu. Le Metahuman se connectera automatiquement à Fay.

---

## Section 11 : Vérifier la connexion et tester le dialogue

![讲义](<../images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le Metahuman UE et Fay a bien été établie, puis à effectuer un test de dialogue complet.

Une fois le Metahuman UE démarré, retournez à l'interface de gestion de Fay. En haut à gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le Metahuman UE est connecté avec succès au service Fay et que le lien de communication bidirectionnel est entièrement établi.

Une fois la connexion confirmée, vous pouvez saluer le Metahuman via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du Metahuman.

Si vous voyez le Metahuman changer d'expression faciale et de mouvement des lèvres, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution de Metahuman UE, félicitations ! Vous avez réussi à démarrer et connecter le Metahuman UE.

À ce stade, tout le processus de démarrage du Metahuman UE est terminé. Vous disposez maintenant d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez désormais explorer de nombreux scénarios d'application intéressants.

---
---

# Groupe d'échange UE (pour obtenir gratuitement les plugins et échanger en toute tranquillité)
![交流群](<../images/1280X1280.JPEG>)