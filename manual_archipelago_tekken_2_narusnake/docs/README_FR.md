# Manuel Archipelago pour Tekken 3

## Bienvenue !
Bienvenue dans mon manuel Archipelago pour **Tekken 3** sur Playstation. Pour ce **Manual Archipelago**, j'utilise la version **Tekken 3 (Everything Unlocked)** ou si vous avez déjà une sauvegarde avec tout débloqué ça marche aussi. Il est fortement conseillé d'avoir une save 100% pour pouvoir finir une seed.

## État du projet
Ce projet est actuellement en **bêta**. Je prévois d’ajouter de nombreuses fonctionnalités supplémentaires dans les futures mises à jour, comme détaillé dans la section **Fonctionnalités futures** ci-dessous.

## Ce Manual Archipelago comporte le jeu complet ainsi que tous ses modes de jeu solo.

## Informations Personnages
Il y a différentes choses à savoir avant de commencer une seed sur les personnages :
- **Kuma et Panda** sont considérés comme 2 personnages différents même s'ils partagent le même ending (pour Panda, il faut utiliser les touches croix et rond de votre manette Playstation)
- **Eddy et Tiger**, comme pour Kuma et Panda, ce sont deux personnages différents à la différence qu'ils ne partagent pas la même fin (pour jouer avec Tiger il faut appuyer sur Triangle sur Eddy)
- **Mokujin** est différencié comme deux sexes différents : **(M) Male** (pour jouer avec lui la touche carré ou triangle) et **(F) Female** (pour jouer avec elle la touche croix et rond). Vous n’êtes pas obligés de faire les checks avec les deux, c'est juste pour de futurs goals la différenciation.

## Informations Modes de jeu
- **Arcade Mode** : Vous devez juste finir le **Mode Arcade** avec chaque personnage que vous avez de disponible.
- **Team Battle** : Gagner les combat dans chaque choix de nombre de personnage.
- **Survival Mode** : Juste le mode survie avec des checks à 10 victoires pour chaque perso à l'heure actuelle.
- **Tekken Ball** : Battre son adversaire au volley ball mais **vous pouvez affronter uniquement les personnages jouables que vous avez débloqués**.
- **Tekken Force** : Finir le mode de jeu avec chaque personnage.

## Bugs connus
- Le goal **All Arcade Mode Clear** ne fonctionne pas pour le moment dans la logique du spoiler log, cependant ça ne vous empêche pas de le faire manuellement, ça casse juste le spoiler log.

## Goals
- **All Arcade Mode Clear**  
  Terminez le **Mode Arcade** avec chaque personnage à l'exception de Mokujin qu'on n'est pas obligé de faire avec les deux sexes (ça ferait trop de doublons).

- **All Arcade Mode Clear with Boys**  
  Terminez le **Mode Arcade** avec chaque personnage masculin. **Mokujin(M)** et **Gon** sont inclus.

- **All Arcade Mode Clear with Girl**  
  Terminez le **Mode Arcade** avec chaque personnage féminin. **Mokujin(F)** et **Panda** inclus.

- **All Tekken Ball Mode Clear**  
  Terminez le **Mode Tekken Ball** avec chaque personnage à l'exception de **Mokujin** qu'on n'est pas obligé de faire avec les deux sexes (ça ferait trop de doublons). Je tiens à souligner que pour ce goal vous devez lire l'information importante dans la section **Tekken Ball**.

- **All Tekken Ball Mode Clear with Boys**  
  Terminez le **Mode Tekken Ball** avec chaque personnage masculin. **Mokujin(M)** et **Gon** sont inclus. Je tiens à souligner que pour ce goal vous devez lire l'information importante dans la section **Tekken Ball**.

- **All Tekken Ball Clear with Girl**  
  Terminez le **Mode Tekken Ball** avec chaque personnage féminin. **Mokujin(F)** et **Panda** inclus. Je tiens à souligner que pour ce goal vous devez lire l'information importante dans la section **Tekken Ball**.

- **All Time Attack Mode Clear**  
  Terminez le **Mode Time Attack** avec chaque personnage à l'exception de **Mokujin** qu'on n'est pas obligé de le faire avec les deux sexes (ça ferait trop de doublons).

- **All Time Attack Mode Clear with Boys**  
  Terminez le **Mode Time Attack** avec chaque personnage masculin. **Mokujin(M)** et **Gon** sont inclus.

- **All Time Attack Mode Clear with Girl**  
  Terminez le **Mode Time Attack** avec chaque personnage féminin. **Mokujin(F)** et **Panda** inclus.

- **All Tekken Force Mode Clear**  
  Terminez le **Mode  Tekken Force** avec chaque personnage à l'exception de **Mokujin** qu'on n'est pas obligé de le faire avec les deux sexes (ça ferait trop de doublons).

- **All Tekken Force Mode Clear with Boys**  
  Terminez le **Mode  Tekken Force** avec chaque personnage masculin. **Mokujin(M)** et **Gon** sont inclus.

- **All Tekken Force Mode Clear with Girl**  
  Terminez le **Mode  Tekken Force** avec chaque personnage féminin. **Mokujin(F)** et **Panda** inclus.

- **King of Iron Fist Tournament Token**  
  Terminer en récupérant tous les tokens qui se nomment : KIFT Emblem.

## Fonctionnalités futures (provisoires)
- **Nouveaux Goals** : Des goals supplémentaires pour varier encore plus les plaisirs.
- **Pouvoir exclure certains modes de jeu** : Pour le moment tous les modes sont inclus dans la randomization de la seed.
- **Des nouveaux checks** : Des futurs checks seront disponibles pour le mode Team Battle et des checks un peu fun basés sur le lore de **TEKKEN**.
- **Réglages de difficulté** : Intégration de niveaux de difficulté ajustables dans la génération d’objets et pouvoir l'exclure aussi.

## Notes de version

### Version 1.0.0 : Release Update
**Modifications**
- Ajout de check sur chaque personnal pour les mode survival, Tekken Ball et Rivalité
- Correction du personnage Bosconovitch car il etait mal orthographier
- Tekken for et team battle mode logique revue
- Ajout d'un item de progression de tekken forces stages , team battle et tekken ball a la génération de la seed

### Version 0.3.0 : Team Battle Update

**Modifications**  
- création de l'item **Progressive Team Battle Select** en progressive
- création des check pour le **Mode Team Battle**
- Reformulation des **catégorie** et **requires** du fichier `locations.json` pour reduire le nombre de ligne.
- Ajout de la catégorie **Boy** et **Girl** dans `items.json` pour reduire la taille des **requires** des **goals**

### Version 0.2.0 : Goal Update

**Modifications**  
- Ajout des items des ballons pour le **Mode Tekken Ball**.  
- Ajout des progressives levels pour le **Mode  Tekken Force**.  
- Restructuration des fichiers `items.json` et `locations.json`.
- Ajout des plusieur **Goal**.

### Version 0.1.1

**Modifications**  
- Correction de la logique de **Mokujin** pour qu'on puisse faire ses checks avec l'un ou l'autre personnage.  
- Correction du goal **All Arcade Mode Clear** pour faire l'un des deux **Mokujin**.

### Version 0.1.0

**Modifications**  
- Création des objets pour les catégories **Personnages**, **Game Mode** et **Difficulty**.  
- Ajout des 2 Goals cités plus haut.  
- Ajout de tous les checks pour chaque personnage pour les **modes Arcade, Time Attack, Survivor, Tekken Ball, Tekken Force**.

## Comment contribuer
Toutes les contributions sont les bienvenues :

- **Retours** : Jouez et partagez vos impressions sur le gameplay et la documentation.  
- **Code** : Envoyez des *pull requests* avec des corrections de bugs ou de nouvelles fonctionnalités.  
- **Documentation** : Améliorez ce fichier **README** ou ajoutez d’autres documents.

## Contact
Si vous avez des questions ou si vous êtes streamer, n’hésitez pas à nous contacter sur le Discord Archipelago ou à ouvrir une issue sur GitHub. Je répondrai dès que possible.

Nous avons hâte de voir comment vous contribuerez à l’évolution de ce projet !
