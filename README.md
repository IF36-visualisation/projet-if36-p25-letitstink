# 📌 Proposition de projet

## 📖 Introduction

### 📊 Données
Nous utiliserons les données de **Match Data Downloads** fournies par **OraclesElixir.com**. Ces données couvrent plusieurs ligues professionnelles de League of Legends, notamment :
- **LCS (Amérique du Nord)**
- **LEC (Europe)**
- **LCK (Corée du Sud)**
- **LPL (Chine)**
- **PCS, CBLoL** et d'autres ligues internationales.

#### 📁 Format et structure des données
- Les fichiers sont au format **CSV**.
- Ils sont mis à jour **une fois par jour**.
- Les définitions des variables sont disponibles sur la [page dédiée](https://oracleselixir.com/definitions).

#### 📊 Contenu des données
- Nombre d'observations : **50**
- Nombre de variables : **20**
- Types de variables :
  - **Numériques** : Niveau du héros, santé du héros, Winrate, pourcentage d’utilisation, assists, kills, deaths, game time, total gold gagné...
  - **Catégoriques** : Nom du héros, rank, position (Top, Middle, Jungle, Bottom, Healer), résultats du jeu, items achetés...

#### 📊 Liste des observations
1. Équilibrage de certains héros
2. L'équilibre d'un équipement
3. Impact des changements de patchs sur la méta
4. Influence de la durée des parties sur les performances des joueurs
5. Évolution des stratégies en fonction des équipes
6. Comparaison des performances des rôles (Jungle, Mid, ADC, Support, Top)
7. Analyse des champions les plus joués et leur impact sur le winrate
8. Influence des objectifs neutres sur l’issue des parties
9. Comparaison des styles de jeu entre les différentes ligues
10. Corrélation entre le KDA et le rang des joueurs
11. Impact des bans de champions sur les résultats
12. Influence du first blood sur l’issue des parties
13. Analyse du scaling des équipes (early vs late game)
14. Évaluation des stratégies de split push
15. Impact du nombre de tours détruites sur les victoires
16. Étude du nombre de barons Nashor capturés et leur influence
17. Analyse du contrôle de la vision et impact sur les résultats
18. Influence du farming sur le gain de gold et l’issue des parties
19. Comparaison entre les équipes agressives et défensives
20. Relation entre les assists et le succès des équipes
21. Analyse des parties avec remontée de score
22. Comparaison des performances des équipes en playoffs et en saison régulière
23. Analyse du comportement des équipes en fin de partie
24. Étude du nombre de kills moyen par partie
25. Relation entre le temps de jeu et les stratégies adoptées
26. Influence des dragons capturés sur les victoires
27. Analyse du ratio gold par minute des équipes
28. Influence des picks exotiques sur les résultats
29. Impact des changements de composition d’équipe sur la performance
30. Analyse du taux de victoires des équipes favorites
31. Étude du nombre moyen de deaths par rôle
32. Influence de la méta sur les performances des ADC
33. Impact de la prise d’objectifs secondaires
34. Comparaison entre early et late game carries
35. Étude du taux de conversion des leads en victoires
36. Influence de la gestion de la jungle sur les résultats
37. Étude des win streaks et des losing streaks
38. Analyse de la draft et son impact sur le winrate
39. Impact de la composition des équipes sur la durée des parties
40. Comparaison des performances entre joueurs rookies et vétérans
41. Influence de la coordination en équipe sur le succès
42. Relation entre les statistiques individuelles et le succès collectif
43. Impact du mental et du tilt sur les performances
44. Étude des victoires surprises et upsets
45. Corrélation entre le nombre de wards placées et le winrate
46. Impact des paires botlane sur les performances des ADC
47. Étude du temps moyen passé en base
48. Comparaison du farm entre midlaners et ADC
49. Influence des pauses techniques sur le déroulement des parties
50. Analyse des performances des champions après buffs ou nerfs

#### 📊 Liste des variables
1. Niveau du héros
2. Nom du héros
3. Rank
4. Santé du héros
5. Winrate
6. Pourcentage d’utilisation
7. Concours
8. Position (Top, Middle, Jungle, Bottom, Healer)
9. Assists
10. Kills
11. Deaths
12. Game time
13. Game results
14. Total gold gagné à la fin du jeu
15. Items achetés
16. Nombre d'objectifs neutres capturés
17. Nombre de tours détruites
18. Nombre de dégâts infligés
19. Score de vision (warding, détection d'ennemis)
20. Participation aux kills (Kill Participation)

### 📌 Plan d’analyse
Nous souhaitons répondre aux questions suivantes :

#### 🔍 Questions principales
1. **Facteurs de victoire** : Quelles statistiques influencent le plus le résultat d’un match ?
2. **Performances des joueurs** : Quels sont les indicateurs clés de performance (KDA, participation aux kills, dégâts infligés) ?
3. **Tendances des ligues** : Y a-t-il des différences significatives entre les régions (LCS, LEC, LCK, etc.) ?
4. **Impact des méta-changements** : Comment les mises à jour du jeu affectent-elles les stratégies et performances ?

#### 📊 Comparaisons et analyses prévues
- **Comparaison entre ligues** : LCK vs LCS, LPL vs LEC...
- **Analyse des rôles** : Junglers vs Midlaners, ADCs vs Supports...
- **Corrélations entre statistiques** : Ratio gold/dégâts, participation aux kills et victoires...

#### ⚠️ Problèmes potentiels
- **Qualité des données** : Données manquantes ou bruit statistique.
- **Biais régionaux** : Les styles de jeu varient selon les régions.
- **Taille des échantillons** : Certaines ligues peuvent être sous-représentées.

Nos analyses se feront via **R Studio** pour la manipulation et la visualisation des données.

---
📁 **Les fichiers de données seront stockés dans le dossier dédié du repository.**
