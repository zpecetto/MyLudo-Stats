# Tables n8n

Les CSV contiennent uniquement les en-têtes d’origine, sans aucune ligne de collection. Créez les tables dans votre projet n8n, puis sélectionnez-les dans tous les nœuds Data Table concernés.

L’import CSV permet de reprendre les noms des colonnes. Sans données, vérifiez les types ci-dessous ; si votre version refuse un CSV vide, créez ces colonnes manuellement. Les colonnes système de n8n (`id`, `createdAt`, `updatedAt`) ne sont pas à ajouter aux modèles.

## Jeux de société

| Colonne | Type |
|---|---|
| `Nom` | string |
| `statuts` | string |
| `genre` | string |
| `categorie` | string |
| `prix` | string |
| `annee_sortie` | string |

Documentation : [Data tables n8n](https://docs.n8n.io/data/data-tables/).
