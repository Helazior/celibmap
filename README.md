# Célib' Map — le site

Carte interactive de la France : pour chaque canton ou ville, combien de personnes de votre sexe
visent les mêmes partenaires que vous, pour combien de partenaires disponibles — selon le sexe,
l'âge et l'orientation. Statut conjugal, enfants au foyer, couples de même sexe, saison des
mariages, niveau de vie, vote, satisfaction dans la vie : tout en cartes et en fiches.

**Voir le site : https://celibmap.fr/**

Ce dépôt contient uniquement le site **compilé** (HTML, JavaScript, CSS, données agrégées au
format JSON, contours TopoJSON, pages de partage, `sitemap.xml`). Le code source et le pipeline
de calcul ne sont pas publiés. La méthode complète est expliquée dans le site, bouton « Méthode ».

## Données et sources

- **Insee**, recensement de la population 2022, fichiers détail « Individus localisés au
  canton-ou-ville » (exploitation complémentaire) ; état civil 2024 (naissances, mariages) ;
  Filosofi 2021 (niveau de vie). Contours IGN Admin Express via Etalab.
- **Ined**, enquête Envie 2023 ; **Inserm-ANRS-MIE**, enquête CSF 2023 ; **Insee**, enquête
  Famille et logements 2011 (correction des couples non cohabitants, marchés de même sexe).
- **Ministère de l'Intérieur**, présidentielle 2022 par commune (data.gouv.fr) ; repères
  Cevipof, Ifop.
- **Santé publique France**, Baromètre 2024 (satisfaction dans la vie, par région).
- **INJEP / ministère des Sports**, recensement 2023 des licences sportives géocodé par l'Insee.
- **Stanford**, How Couples Meet and Stay Together 2017 (mois de la rencontre).

Tous les chiffres sont des estimations statistiques sur des territoires, jamais sur des
personnes. Les unités de moins de 200 personnes pondérées ne sont pas classées.

## Signaler une erreur

Ouvrez une *issue* dans ce dépôt en indiquant l'adresse de la page (le lien « Partager » la
copie) et ce qui vous semble faux.

## Licence

Voir [`LICENSE.md`](LICENSE.md) : données sous Licence Ouverte 2.0 (Etalab), site
© Clément Gindrier.
