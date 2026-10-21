# Architecture Logicielle – Séance 1 · MVC, MVP, MVVM

M1 Data Engineer · INGETIS

TP 1 réalisé par **Oliver GBAGUIDI** et **Namory SOUMAHORO**.

## Contenu

| Dossier | Contenu |
|---|---|
| `mvc/` | Exemple du cours : Todo-list en MVC |
| `mvp/` | Exemple du cours : formulaire de connexion en MVP |
| `mvvm/` | Exemple du cours : panier en MVVM |
| `tp1-Oliver_GBAGUIDI-Namory_SOUMAHORO/` | Notre TP 1 |

Dans le dossier du TP :

- `sequences.md` : étapes 1 à 3 (analyse des trois patterns, diagrammes de séquence Mermaid, explication de la règle des 60 caractères) ;
- `comparaison.md` : étape 4 (comparaison MVC / MVP / MVVM et question de spécialité Data) ;
- `TodoModel.js` : ajout de la règle « 60 caractères maximum » ;
- `TodoModel.regle.test.js` : tests de cette règle.

## Lancer les tests

Prérequis : Node.js 20 ou plus récent, aucune dépendance à installer.

```bash
node --test tp1-Oliver_GBAGUIDI-Namory_SOUMAHORO/TodoModel.regle.test.js
```

Tous les tests de la séance :

```bash
node --test mvc/*.test.js mvp/*.test.js mvvm/*.test.js tp1-Oliver_GBAGUIDI-Namory_SOUMAHORO/*.test.js
```

## Voir les exemples dans le navigateur

Les pages utilisent des modules ES : il faut les servir avec un petit serveur local, par exemple :

```bash
npx serve .
```

puis ouvrir `mvc/index.html`, `mvp/index.html`, `mvvm/index.html` ou `tp1-Oliver_GBAGUIDI-Namory_SOUMAHORO/index.html`.
