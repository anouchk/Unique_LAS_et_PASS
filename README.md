# Unique_LAS_et_PASS

Dans le <a href="https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-parcoursup/information/?timezone=Europe%2FBerlin&sort=tri">fichier open data du MESRI sur Parcoursup 2020</a>, j'ai commencé à explorer les différentes filières, et suis tombées sur les licences LAS et les PASS, les deux nouvelles voies d'accès aux études de santé.

J'ai extrait les variables qui me semblaient intéressantes, puis fait des calculs de sélectivité, de part de mention TB parmi les néobacheliers admis, ou de répartition de bac générale/techno/pro parmi les néobacheliers, par université.

La fonction unique() m'a permis de ne pas répéter les lignes inutiles. Et j'ai ensuite concaténé les deux bases avec un rbind().
