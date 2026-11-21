# Nettoyage et analyse des stocks d'un caviste en ligne

**Outil** : Python (pandas, matplotlib, seaborn, plotly) · **Projet 6** · BottleNeck

**Objectif** : fiabiliser 3 exports (ERP, site web, table de liaison) et en tirer des indicateurs pour décider.

**Démarche**
- Nettoyage et fusion : 3 fichiers → une base de 713 lignes, 9 anomalies traitées
- Détection des prix atypiques (boxplot, z-score, IQR)
- Analyse du CA, du stock, de la marge et des corrélations

**Résultats** (octobre)
- CA 119 494 € HT, stock 298 540 €, couverture 2,5 mois
- Champagne : 16,4 mois de couverture et la marge la plus faible (40,1 %)
- 25 références en rupture

**Recommandations**
- Champagne : réduire le stock et travailler la marge
- Références en rupture : seuil d'alerte et approvisionnements sécurisés
- Spiritueux : développer les ventes, la famille la plus rentable
- Stock immobilisé : déstocker les références à faible rotation
- Prix atypiques : les faire valider par le métier avant correction

**Compétences** : nettoyage, gestion des incohérences, analyses univariées et multivariées

**Fichiers** : `P6_notebook_082026.ipynb`, `P6_presentation_082026.pptx`
