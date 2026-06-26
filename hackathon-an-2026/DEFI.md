# DEFI.md

### Nom du défi
Cahier de Doléances 2.0 : connecter les citoyens aux bons élus grâce à l'IA

### Description courte
Une plateforme qui recueille les doléances des citoyens et utilise l'IA pour suggérer l'élu compétent (maire, député, sénateur, conseiller départemental ou régional), puis analyse, classe et synthétise ces remontées afin d'offrir à chaque élu une vision claire et objectivée des attentes réelles de ses administrés.

### Porteur
Adam Assim Dumont — AdamIA

### Description longue

**Le constat**

Les citoyens veulent être entendus, mais ne savent pas toujours à qui s'adresser. Une demande sur une école relève de la commune ; une question fiscale, du législateur ; un transport régional, du conseil régional. Résultat : des doléances mal orientées, des élus submergés de messages hors de leur champ de compétence, et un sentiment d'impuissance partagé des deux côtés.

**La solution**

Une plateforme citoyenne où chacun dépose sa doléance en langage naturel. L'IA accomplit alors trois tâches :

1. **Qualification et orientation** — elle identifie l'échelon territorial et la compétence concernée, puis *suggère* l'élu destinataire pertinent (maire, député, sénateur, conseiller départemental ou régional). L'orientation reste une recommandation, jamais un envoi automatique : le citoyen garde la main.

2. **Analyse et classement** — elle catégorise les sujets, détecte les signaux faibles et les tendances, et agrège les doléances par thème et par territoire.

3. **Restitution** — elle produit pour chaque élu un tableau de bord synthétique : volumes, priorités, évolution dans le temps, attentes dominantes.

**L'enjeu démocratique**

Redonner de la lisibilité au dialogue citoyen-élu. Côté citoyen : l'assurance d'être orienté vers la bonne personne. Côté élu : une connaissance fine et objectivée des attentes, fondée sur la donnée plutôt que sur l'intuition ou le seul courrier le plus bruyant.

**Le déroulé pour le hackathon**

- Interface citoyenne de dépôt d'une doléance en langage naturel.
- Moteur d'orientation IA reliant la doléance à l'échelon et à l'élu compétents, en s'appuyant sur les jeux de données des députés et sénateurs en exercice.
- Tableau de bord élu : agrégation, classement thématique et synthèse des remontées.

Stack envisagée : Next.js, Supabase, API d'un modèle de langage pour la qualification et la synthèse.

### Contributeurs
- Adam Assim Dumont

### Ressources utilisées

- [x] `an-deputes-en-exercice` — Députés en exercice ✺ Assemblée nationale
- [x] `an-deputes-senateurs-ministres-par-legislature` — Députés, sénateurs et ministres d'une législature ✺ Assemblée nationale
- [x] `an-questions-gouvernement` — Questions de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [x] `an-questions-gouvernement-ecrites` — Questions écrites de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [x] `an-questions-gouvernement-orales` — Questions orales de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [x] `senat-senateurs` — Sénateurs ✺ Sénat
- [x] `senat-questions-gouvernement` — Questions orales et écrites du Sénat au Gouvernement ✺ Sénat
- [x] `an-et-co-database-regroupement-toutes-donnees` — Base de données unifiée Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
- [x] `an-et-co-serveur-mcp-regroupement-toutes-donnees` — Serveur MCP - Accès unifié Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
- [x] `an-et-co-api-regroupement-toutes-donnees` — API - Accès unifié Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
