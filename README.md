# PureScan AI — exploration dermatologique

**Catégorie :** interface web expérimentale pour l'analyse visuelle de la peau · Studio Niko Design.

## Ce que fait l'application

L'interface actuelle est intitulée **« PureScan AI — Dermatologue v6.0 »**. Elle propose l'accès à la caméra, un parcours de scan cutané, un lancement d'analyse dermatologique, une section rapport et des espaces de navigation consacrés au nettoyage, aux produits, à la routine, au traitement et au chat.

Cette version **n'est pas un scanner général d'ingrédients alimentaires ou de composition de produits**, contrairement à ce qu'indiquaient des descriptions antérieures. Les rubriques « produits » et « traitement » ne prouvent pas l'efficacité, l'innocuité ni la personnalisation médicale des conseils.

## Comment l'explorer

Le point d'entrée est `index.html`. Pour l'afficher sur votre machine :

```sh
python3 -m http.server 8000
```

Ouvrir ensuite http://localhost:8000/. La caméra nécessite généralement **HTTPS ou localhost**, ainsi qu'une autorisation explicite. Certaines fonctions d'IA peuvent requérir un fournisseur ou une connexion externe.

## Précautions et niveau de validation

**Prototype de démonstration, non certifié comme dispositif médical.** Une photo ne permet pas de poser un diagnostic dermatologique fiable. Ne pas utiliser ses résultats pour choisir un traitement, remplacer une consultation ou exclure une lésion inquiétante. Vérifier les flux de données avant d'importer une image personnelle.

La présente documentation décrit les contrôles et sections visibles dans le code, **sans validation fonctionnelle, clinique ni audit de sécurité**.

[À quoi servent les autres projets du studio ?](https://github.com/Nikoju1977/Nikoju1977/blob/main/PROJECTS.md)
